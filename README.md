I have set up an OPENAI API Key, You can update it if you want.

Next steps to do : 

Edit config/config.example.yml to set your tokens and run 2 commands below
```
mv config/config.example.yml config/config.yml
mv config/config.example.env config/config.env
```

To run the code 
```
docker-compose --env-file config/config.env up --build
```

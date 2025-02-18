# minecraft-compose-stack


## How to run

1. Install docker + docker compose (see their instructions)
2. Configure the environment 
   - Add your own `.env` file to set host specific settings 
	 - ```bash 
	   cp _env.sample .env 
		 vim .env 
		 ``` 
	 - See `_env.sample` for a description of the options needed 
3. Bring up the stack: 
   ```bash 
	 # -d brings it up in the background 
	 docker compose up -d 
	 ```



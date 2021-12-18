# bratcoin

1. Clone the repository 
   ```git clone https://github.com/94bharathraj/bratcoin.git```

2. Enter the directory
   ```cd bratcoin```

3. Edit .env in this directory, the values of variables are present in the report
   ```vim .env```
   Paste the environment variables present in report
   ```
   INFURA_TOKEN=< to be copied from report >
   CONTRACT_ADDRESS=< to be copied from report >
   OWNER_ADDRESS=< to be copied from report >
   SUPER_SECRET_PRIVATE_KEY=< to be copied from report >
   
   ```
   To save 
    ```:wq!```

4. Two methods to run the distribution for transaction to accounts present in accounts.txt
   
   Method 1 :
   ```docker run 94bharathraj/bratcoin:4```

   OR 
   Method 2:
   ```docker-compose up```
   
   
Note: 
If docker is not installed , please follow steps from here:
https://docs.docker.com/get-docker/

If docker compose is not installed, please follow steps from here:
https://docs.docker.com/compose/install/

# btc_python_neo4j

This repository contains a Python script for parsing Bitcoin data and writing it to a Neo4j database. The script utilizes the Bitcoin RPC interface to fetch blockchain data and the Neo4j database to store and analyze the data.

#### Installation
Before running the parser and writer, you need to set up the required credentials. Follow the steps below to configure the credentials.json file:

Create a folder named .secrets in the root directory of the project if it doesn't exist.

Inside the .secrets folder, create a file named credentials.json.

Open the credentials.json file in a text editor.

Copy and paste the following JSON structure into the credentials.json file:

json

```
{
  "BitcoinRPC": {
    "rpc_user": "username",
    "rpc_password": "userpass"
  },
  "Neo4j": {
    "username": "neo4j",
    "password": "neo4j"
  }
}
```

Replace the placeholder values with your actual credentials. These credentials will be used to authenticate with the Bitcoin RPC interface and the Neo4j database.

Save and close the credentials.json file.

Once you have set up the credentials.json file, you can run the Jupyter Notebook.
# Home Assignment


In our team we are using some software technologies that we want you to be familiar with and also demonstrate your ability to understand and work with them.

In this task we want you to create a full stack app , that includes taking user input from a well designed UI and then preforming some procesing on the data (such as validation and metadata extraction)  and then doing some CRUD operations with a selected DB.


<details>
  <summary>Frontend</summary>

  - Create a user interface for uploading files , The UI needs to be designed to look like the [example](https://www.figma.com/file/d8dGyuJIbrbdJzEN0l3lSI/%D7%A4%D7%A8%D7%95%D7%99%D7%A7%D7%98-%D7%A2%D7%99%D7%A6%D7%95%D7%91-%D7%9E%D7%A8%D7%A5-2024?type=design&node-id=0-1&mode=design) we provided as much as you can.

</details>

<details>
  <summary>Backend</summary>

  - Deploy the infrastructure from the docker-compose.yaml file.

</details>

<details>
  using the same technologies that we are using in our team is a grate bonus 
  <summary>Technologies</summary>

  Minio, 
  Mongodb, 
  Node js ,
  React js , 
  TypeScript , 
  Docker

</details>

 
- Deploy the infrastructure from the docker-compose.yaml file.
 - Create a user interface for uploading files , The UI needs to be designed to look like the example we [provided](https://www.figma.com/file/d8dGyuJIbrbdJzEN0l3lSI/%D7%A4%D7%A8%D7%95%D7%99%D7%A7%D7%98-%D7%A2%D7%99%D7%A6%D7%95%D7%91-%D7%9E%D7%A8%D7%A5-2024?type=design&node-id=0-1&mode=design) as much as you can.
 - Create a Node js Server to receive the file you uploaded , Perform a validation on the files (only allow certain file extensions etc…) .
 - Extract metadata from the file (such as :  name , type , size , creation date, md5 hash of the file  ) .
 - Store the metadata in a mongo database . 
 - Store the file on a Minio server, use the hash of the file as the name for the file.
 - If the user uploads a file and its hash already exists in the database let the user know in the UI that this file already exists . 
 - Creat tests for your App. 
 - open a new private git repository commit and push the code to a branch called DEV. 

NOTE :  Using TypeScript and Git flow is a big bonus !

GOOD LUCK ! 

# Home Assignment


In our unit we are using some software technologies that we want you to be familiar with and also demonstrate your ability to understand and work with them.

For this task we picked these specific technologies :  Minio , Mongodb, Node js , React js , TypeScript , Docker .


 - Deploy the infrastructure for the assignment  using Docker compose on the .yaml file we provided . 
 - Create a user interface using React  for uploading files , The UI needs to be designed to look like the example we [provided](https://www.figma.com/file/d8dGyuJIbrbdJzEN0l3lSI/%D7%A4%D7%A8%D7%95%D7%99%D7%A7%D7%98-%D7%A2%D7%99%D7%A6%D7%95%D7%91-%D7%9E%D7%A8%D7%A5-2024?type=design&node-id=0-1&mode=design) as much as you can.
 - Create a Node js Server to receive the file you uploaded , Perform a validation on the files (only allow certain file extensions etc…) .
 - Extract metadata from the file (such as :  name , type , size , creation date, md5 hash of the file  ) .
 - Store the metadata in a mongo database . 
 - Store the file on a Minio server, use the hash of the file as the name for the file.
 - If the user uploads a file and its hash already exists in the database let the user know in the UI that this file already exists . 
 - Creat tests for your App. 
 - open a new private git repository commit and push the code to a branch called DEV. 

NOTE :  Using TypeScript and Git flow is a big bonus !

                                                                GOOD LUCK 

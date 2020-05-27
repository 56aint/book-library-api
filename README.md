This project is a boilerplate for creating an `express` app which uses `sequelize` to interact with `MYSQL` database.

## Getting Started
Create a new directory on your computer `mkdir 'your folder name'`
```bash
fork the repo
git clone git@github.com:56aint/book-library-api.git your-project-folder-name
cd your-project-folder-name
npm install
```
## NEXT >>> Set up your database
It is assumed that you have MYSQL running in a docker;
Install docker with: 
`sudo apt install docker.io`
Check  if docker is installed 
`docker --version`

You can set up a MYSQL image in a docker by running the following commands in your terminal:
```docker run -d -p 3306:3306 --name book-library-api-db -e MYSQL_ROOT_PASSWORD=<YOUR_PASSWORD> mysql``` 
**keep the password safe** 
```



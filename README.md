### Docker build instruction

## The command below builds Docker Client Image
docker build . -t mkomen/yolomy-client:v2.0.0

$ docker images

# Example
REPOSITORY                      TAG        ID              CREATED
mkomen/yolo-client              v2.0.0     d5135808c81e    1 minute ago


## The command below builds Docker backend Image
docker build . -t mkomen/yolomy-backend:v2.0.0

# running manualy without docker
Make sure that you have the following installed:
- [node](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-18-04) 
- npm 
- [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) and start the mongodb service with `sudo service mongod start`

## Navigate to the Client Folder 
 `cd client`

## Run the folllowing command to install the dependencies 
 `npm install`

## Run the folllowing to start the app
 `npm start`

## Open a new terminal and run the same commands in the backend folder
 `cd ../backend`

 `npm install`

 `npm start`

 ### Go ahead a nd add a product (note that the price field only takes a numeric input)
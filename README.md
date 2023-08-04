
# GIGIH MIDTERM FULLSTACK ENGINEERING

## Installation
1. clone the project repository to your local machine
```
git clone https://github.com/dwipradnyanaa/mid-term-fullstack-engineering
```
2. Open a terminal or command prompt, navigate to the project's root directory, and install the required dependencies by running:
```
npm install
```


## Configuration
Make sure you have MongoDB installed and running. By default, MongoDB runs on localhost and port 27017. If your MongoDB instance is running on a different host or port, make sure to update the connection settings in the ./config/development.json file.
```
{
    "PORT": 8080,
    "DB_URL": "mongodb://127.0.0.1:27017/tokopedia_play_db"
}
```


## Running Server
To start the Express.js server and run the API, run the following command in the terminal:
```
npm run dev
```

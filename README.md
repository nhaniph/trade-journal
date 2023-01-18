# Setup

 1. Run `npm install` in client and server directories
 2. Create a '.env' file in server directory with the variables `MONGO_URL` and `PORT`. Mongo URL is the connecting url for MongoDB. Port is usually 5001.
 3. Create a '.env.local' file in the client directory which has the variable `REACT_APP_BASE_URL`. This is just 'http://localhost:5001'
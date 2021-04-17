## Features

* SignUp / SignIn.
* Forgot password.
* Google Oauth Login.
* edit / delete your profile.
* Follow / Unfollow users.
* create / edit / delete posts.
* create / delete comments.
* Like / Unlike posts.
* Personal chat with users.

## To run the project locally

* clone this Repository by `git clone https://github.com/S-codes14/SnApp-App.git`.
* create a .env file and add these
    - `MONGO_URI=mongodb+srv://Sibongumusa:Southgate1@cluster0.jgqxi.mongodb.net/myFirstDatabase?retryWrites=true&w=majority`
    - `PORT=8080`
    - `JWT_SECRET=any-random-string-of-any-length`
    - `CLIENT_URL=http://localhost:3000`
* Inside the client create a .env file and add
    - `REACT_APP_API_URL=http://localhost:8080`
* Change the directory to /server in the terminal and run:
    - `npm install`
    - `node app.js`
* Change to the client in the terminal and run:
    - `npm install`
    - `npm start`
* Open your browser and enter url `http://localhost:3000`

## Tech Stack of this Project

* Frontend: Reactjs, Bootstrap Material, React-native
* Backend: Nodejs
* Framework: Expressjs
* Database: MongoDB


## Further Work

- [ ] Improve performancem - decrease loading time.
- [ ] Display status of users online/offline in chat.
- [ ] Add Notifications when someone follows/messages you or likes/comments on your post. 



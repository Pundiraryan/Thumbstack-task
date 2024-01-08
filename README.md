
# Chatify

Chatify is  a real time chat application with a super user friendly interface that allows users users to chat with other individuals, create  Chat Rooms and enjoy seamless communication with fellow members
 


## Features

- Real time communication facilitated by Socket.io
- Fully authenticated 
- Fully Responsive
- User actions indicated using Toast
- Typing status of user visible
- Users can create group chats




## Run Locally

Clone the project :

```bash
  git clone https://github.com/Pundiraryan/Thumbstack-task.git
```

Go to the project directory :

```bash
  cd Thumbstack-task
```

Rename .env.example into .env and put all credentials :

```bash
PORT=5000
MONGO_URI="YOUR_MONGO_CONNECTION_URL"
JWT_SECRET="YOUR_JWT_SECRET"
JWT_EXPIRE=2d
NODE_ENV=development 
# Change to "production" when deploying
```

Install package dependencies :

```bash
npm install # Server dependencies
cd client
npm install # Client dependencies
```

Run project :

In the root directory, open two terminal sessions and run both commands separately :

```bash
npm run client
npm run server
```
 Open your browser and go to http://localhost:3000 and boom!! The app will run 



# ✨ Ping Me ✨


Highlights:

- 🌟 Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI
- 🎃 Authentication && Authorization with JWT
- 👾 Real-time messaging with Socket.io
- 🚀 Online user status
- 🐞 Error handling both on the server and on the client


### How to Run?
### Setup .env file in the backend directory

```js
MONGODB_URI="add your database URL here"
PORT=5001
JWT_SECRET="add the JWT secret here" //(can be generate in console using : node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"")

CLOUDINARY_CLOUD_NAME="add you cloudinary cloud name here"
CLOUDINARY_API_KEY="add the API KEY here "
CLOUDINARY_API_SECRET="add the Secret here"

NODE_ENV=development
```

### Build the app (Backend)

```shell
npm run dev
```

### Start the app (Frontend)

```shell
npm run dev
```

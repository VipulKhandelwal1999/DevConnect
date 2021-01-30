# DevConnect

> Social network for developers

This is a MERN stack application. It is a small social network app that includes authentication, profiles and forum posts.

# Quick Start 🚀

### Add a .env file in root folder with the following

You can get GITHUB access token by following [these instructions](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line). For this app we don't need to add any permissions so don't select any in the scopes. DO NOT SHARE ANY TOKENS THAT HAVE PERMISSIONS. This would leave your account or repositories vulnerable, depending on permissions set.

```
MONGO_URI="<your_mongoDB_Atlas_uri_with_credentials>"
JWT_SECRET="secret",
GITHUB_TOKEN="<yoursecrectaccesstoken>"
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```

### Build for production

```bash
cd client
npm run build
```

### Test production before deploy

After running a build in the client 👆, cd into the root of the project.  
And run...

Linux/Unix

```bash
NODE_ENV=production node server.js
```

Windows Cmd Prompt or Powershell

```bash
$env:NODE_ENV="production"
node server.js
```

Check in browser on [http://localhost:5000/](http://localhost:5000/)

---

## App Info

### Author

Vipul Khandelwal
[Portfolio](https://vipul-khandelwal.netlify.app/)

### Version

1.0.0

### License

This project is licensed under the MIT License

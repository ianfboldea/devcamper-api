# DevCamper API

###### Setup:

First, clone the repository and go in config.env to add the fields according to the following template:

```

NODE_ENV=development
PORT=5000

MONGO_URI=

GEOCODER_PROVIDER=
GEOCODER_API_KEY=

FILE_UPLOAD_PATH=
MAX_FILE_UPLOAD=1000000

JWT_SECRET=
JWT_EXPIRE=30d
JWT_COOKIE_EXPIRE=30

SMTP_HOST=
SMTP_PORT=
SMTP_EMAIL=
SMTP_PASSWORD=
FROM_EMAIL=
FROM_NAME=

```

Next, download the node dependencies by running:

```
npm install
```

within the folder.

To run the server in production, run:

```
npm run start
```

To run the server in development, run:

```
npm run dev
```

Lastly, I want to thank my biggest inspiration, Brad Traversy, for walking me through the creation of this API.

> Now we've gaht to add a user. We can put anything here, it doesn't matta. I mean like, I dunno, we'll just go with Jahn Doe.

> - Professor Brad Traversy

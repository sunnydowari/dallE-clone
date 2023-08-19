
# Dall-E Clone

DALL-E clone is an AI system that can create realistic images and art from a description in natural language. This student project tries to achieve the clone of the project using MERN stack and openAi APi.


## Features

- type in any prompt of what your photo should look like, the Dall-E api will generate it and 
- Genrate images with already given prompts using surprise me
- when the image is generated, you can share it with the community, 
- the image is stored in Cloudinary, and MongoDb stores the Cloudinary url
- the home page retrieves all past images that have been generated
- you can search for the images that have already been generated
- you can download the images that have been generated by you and the community


## Screenshots

![App Screenshot](https://imgtr.ee/images/2023/08/19/faf5ac3afafd21c15d9a18252b2892da.png)
![](https://imgtr.ee/images/2023/08/19/1b42e194f71639758231b59c69468f26.png)
## Deployment

To deploy this project for the app run:

```bash
  npm dev run
```

To deploy this project for the api server run:

```bash
  npm start
```
## Installation

Install the project with npm

dependencies that have been used are

    
    MongoDb
    Express.js
    Vite - React.js
    Node.js
    Cloudinary
    file saver
    tailwind CSS

to install dependencies run the following command in both directories (app and server):

```bash
  npm install
```

to start the client locally
```bash
cd app
npm run dev
```

to start the api locally
```bash
cd server
npm start
```
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file, the env will in the root of server


OPENAI_API_KEY ="xxxxxxxxxxxxxxxxxxxxxxxxxxxx"

MONGODB_URL ="xxxxxxxxxxxxxxxxxxxxxxx"

CLOUDINARY_CLOUD_NAME="xxxxxxxx"

CLOUDINARY_API_KEY="xxxxxxxxxxxxxx"

CLOUDINARY_API_SECRET="xxxxxxxxxxxxxxxxxxxx"

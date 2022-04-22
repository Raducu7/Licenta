# Airbnb Clone

Airbnb clone developed on the simcoder youtube chanel. It is made using MERN and firebase for the Auth system.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.


### Prerequisites

What things you need to install the software and how to install them

1. Docker-Compose


> check the following [link](https://docs.docker.com/compose/install/) on how to install docker-compose

## Setting up firebase

1. Go to your firebase dashboard -> authentication -> sign-in method and enable google
   
2. Go to firebase dashboard -> project Settings -> add web app and get the contents of firebaseConfig pasting them onto the variable firebaseConfig in frontend/src/Login/Login.js

3.  Go to your firebase dashboard -> Project Settings -> Service accounts
    1.  Generate new private key copy the content and paste it into backend/src/config/serviceAccountKey.json
    2.  Go to backend/src/functions/user.js and change the admin.initializeApp() content for the one in the service account page.

## Deployment

A step by step series of examples that tell you how to get a development env running.

```
//>  systemctl start docker 
>  docker-compose up --build
```

## Authors

* **Radu** - *Main Dev* 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details



TOKEN:  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
# Documentation Modus

In this repository you'll find the documentation for our Digital Menu Application project. 

To run our application, create a folder and clone all our repositories into that folder. Then, copy the docker-compose.yml file in this repository, to the folder that you created, where all the repositories are. After that, open a terminal and run the following commands at the location of this folder.
```docker
docker compose up -d --build
```

Then run the following command to go to the gateway directory:
```bash
cd gateway
```

After that, run the gateway:
```bash
npm run start-dev
```

The application should then be running. Go to the following link: http://localhost:12345/?tableNumber=5. You can replace the number '5' with any number between 0 and 10.

These are the ports that are mostly used for this application:
- 12345 (for the Customer Frontend, with using the gateway)
- 3001 (for the Staff Frontend, without using the gateway)
- 3002 (for the Manager Frontend, without using the gateway)
- 9000 (for the Menu API)
- 9002 (for the Order API)

You can find our remaining documentation in the following links:
- [Our code of conduct](https://github.com/Modus-1/documentation/blob/main/Documents/Code%20of%20Conduct.md)
- [C4-model](https://github.com/Modus-1/documentation/blob/main/Documents/C4-model.md)
- [Wireframes](https://github.com/Modus-1/documentation/blob/main/Documents/Wireframes.md)
  
Our project repos can be found in the following links:
- [customer-frontend](https://github.com/Modus-1/customer-frontend)
- [menu-api](https://github.com/Modus-1/menu-api)
- [order-api](https://github.com/Modus-1/order-api)

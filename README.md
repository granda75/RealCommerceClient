# RealCommerceClient Repository
Angular client with Search city page and Favorite page.

This repository is the client side of the web application that shows weather of some city.

To run clients side site unzip the real-weather-site.zip from this repository, open real-weather-site folder in the Visual Studio Code and execute npm install and ng serve commands. After the commands the clients side will be available with the URL http://localhost:4200/. In the environments\environment.ts file you can find the configuration for development. I used the configuration to define endpoint to connect to the server's service. If you change servers port it is need to change the clients side endpoint URL too.

export const environment = {
  production: false,
  apiEndpoint: 'https://localhost:44382/api'
};

Have a nice day !

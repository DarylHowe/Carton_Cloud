Starup Instructions


* Install Docker Desktop - https://www.docker.com/products/docker-desktop/
* Ensure Docker is running 
* Clone the project
* Open main project directory ie cd to 'example-app' in terminal
* Create environment file '.env' 
    - copy contents of .env.example file in .env file
    - provide values for carton cloud variables 'CARTON_CLOUD_API_USERNAME' 'CARTON_CLOUD_API_PASSWORD='
* run 'vendor/bin/sail up' to run the proejct
    - this will take some time on the inital build

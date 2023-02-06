It is a very simple nginx project

We are just overriding the default page provided by nginix

we are using docker to run the nginx server

1. Building the image
    
    docker build -t yasarui/nginx-html .
    
2. Running the image

   docker run -p 80:80 yasarui/nginx-html
   
   
    

FROM almalinux:9
RUN  dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]



# NOTE

#FROM run:v1 ---> IMAGE 

# This will work in two type 
# check image available in local OR It pulls from central docker hub 

# local: 
# Example  FROM run:v1 Its check locally it available Or not it avaiable means will run & IF from image is not available not run  IMAGES==> FROM run:v1

# central: 
# Example : FROM run:v1  IF Images not available in local it pulls from central wheather  check {FROM run:v1}--> image



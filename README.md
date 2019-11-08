# Docker Spring example

# Step 1

Have java installed on the machine:

`sudo apt install -y default-jdk`

# Step 2 

Build the image:

`docker build -t java-app .`

# Step 3 

Run the image:

`docker run -d -p 8080:8080 --name=spring java-app`

# Step 4

Check that it's running:

`curl localhost:8080`
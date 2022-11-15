# DockerFile_Demo
building docker image for the application of flask (python) and node 

### Command to build the image (run from the current directory)
`docker build -t <image name> .`

## Note
1. If you are building python based app, then group the flask related files (dockerfile_flask, index.py, requirement.txt) in a directory and run the above command 
2. If you are building node based app, then group the express related files (dockerfile_express, index.js, package.json, package-lock.json) in a directory and run the above command 
3. you cane get the build images from the below repository (docker hub) \
    Flash build: `docker pull hawkwheels/python_flask_demo`
    Express build: `docker pull hawkwheels/node_express_demo`

# Part I

Create a simple secure hello-world node application using the npm package http-server. 

First, git clone this repository, install node dependencies and start it up with the command 'http-server'. Verify that you see the 'Hello World' message at http://127.0.0.1:8080/sandbox/.

Next, secure this app so that you can run it over https. Create ssl .pem files. Keep any file changes you make local and don't push your changes back to this repository.

Then, create a Docker image that you can distribute anywhere. Modify the Dockerfile and create a docker image that will run this app with the latest stable release of node.js at the root directory https://127.0.0.1:8080 (note the ssl layer, the default directory and the default http(s) port). Consider security, the file size of your Docker image. Include the .git directory, but don't include this README file in your image directory.

When you're done, send either the location of your image in a docker repository that can be publically accessed or as a .tar file that can be loaded into a Docker envionment. Send directions on how this Docker image could run on port 4000 in a container. Consider the restart policy. 

Finally, run a security audit on package.json and provide a report.

# Part II

Explain and/or diagram how you might best deploy and monitor this application to AWS at the url: https://sandbox.example.com.

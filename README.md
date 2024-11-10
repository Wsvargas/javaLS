# javaLS

**javaLS** is a simple Java application that prints the message **"Hello World from Java, Lesly Salas SI08!"** to the console. This project is dockerized to facilitate its deployment and execution in any environment.

## Project Structure

The basic structure of the project is as follows:

javaLS/ │ ├── Dockerfile # Dockerfile to create the container image ├── HelloWorld.java # Main Java application code └── README.md # Project documentation

markdown
Copiar código

### Requirements

To run this project locally or inside a Docker container, you need to have the following:

1. **Java 8 or higher**
2. **Docker** (if you want to run in a container)
3. **Git** (to clone the repository)

### Local Installation and Execution

#### 1. Clone the Repository

Clone the repository using Git:

```bash
git clone https://github.com/lessalcu/javaLS.git
cd javaLS
2. Compile and Run the Program
Compile and run the Java program:

bash
Copiar código
javac HelloWorld.java
java HelloWorld
You should see the message "Hello World from Java, Lesly Salas SI08!" in the console.

Docker Launch Manual
1. Download the Image
To download the image from Docker Hub, run:

bash
Copiar código
docker pull lssalas/javals:latest
2. Run the Container
Once the image is downloaded, run the container with the following command:

bash
Copiar código
docker run lssalas/javals:latest
This will start the container with the Java program, and you should see the message in the console.

Notes
Make sure Docker is running.
If you have problems running the container, check that Docker is correctly installed and configured on your system.
Credits
Project developed by Lesly Salas (https://github.com/lessalcu).
# springboot-demo Implementation 

I refered Sen Devops Channel to do this demo project, Thanks to Sudheer.

## Result

![Screenshot 2025-01-25 142955](https://github.com/user-attachments/assets/7b23ae1a-9541-4caa-a658-0374f81bee99)

![Screenshot 2025-01-25 143650](https://github.com/user-attachments/assets/657a7508-5b83-4f1e-b562-8fe1a0420c4a)


## 1. Run in the Local
### Requirement
Installing Java 17:

    sudo apt update
    sudo apt install openjdk-17-jdk

Installing Maven:
    
    sudo apt update
    sudo apt install maven



Clean and Install the Project:

    mvn clean install


Compile the Project:

    mvn compile

Build the Project:

    mvn package

Run the Application:
Or, navigate to the target directory and run the packaged JAR file:
    
    cd target
    java -jar sendevops-0.0.1-SNAPSHOT.jar


Build Issues:
If the build fails, run Maven with detailed logging to diagnose the problem:

    mvn clean install -X


Run the Docker Container:

        docker run -p 8080:8080 sendevops:latest

        

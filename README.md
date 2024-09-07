By using terminal writting "docker build ."

So we have an inmage which we can use to work with java

To check all our images we can use "docker images"

To remove any image we can use command "docker rm [IMAGE ID]"

The next step - we r using command "docker run [IMAGE ID]"

Now we have a wokring container with our just created image

To set the port which u want we can use commad "docker run -p 3001:8001 [IMAGE ID]". Where 3001 - port which u want to set, and 8001 - port after EXPLOSE in Main.java

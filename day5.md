# Task 5

## Install Maven
```bash
sudo apt install maven
```
![image](https://github.com/user-attachments/assets/a1c7b760-d02d-403d-8213-48898f1ce463)

## Fork the repo on github

![image](https://github.com/user-attachments/assets/f18f17ad-42e9-4512-a746-3614c7721fff)

## Configure Jenkins
 - In Jenkins go to `configure jenkins` > `tools`
 - Locate JDK section
 - Uncheck `Install Automatically`
 - Name `Java 17`
 - Go to terminal and enter the command and get the java 17 path:

```bash
update-java-alternatives --list 
```

 - paste the java path in `JAVA_HOME`

![image](https://github.com/user-attachments/assets/e71ecf62-8ba8-4cf5-8cd5-1ef1e1cb694e)

## Fork The Repo and build the pipeline
![WhatsApp Image 2025-03-22 at 14 19 10_c465f028](https://github.com/user-attachments/assets/4891c22e-5f9e-4401-81e0-0d1f79ad13de)


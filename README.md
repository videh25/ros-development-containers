- Repository that holds templates for docker containers.
- Enables to work on multiple ubuntu and ROS versions simultaneously with a consistent setup.

# Usage
To create new container, run the following commands:
```
cp -a ./jazzy_container_template/ ./{container_name: specified by the use}
```
- Update the variables in .env file
- cd to the folder
- `docker compose up -d`

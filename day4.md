# PROJECT SETUP 

# Setting up file browser locally

1. cd directory_name
2. cd filebrowser
3. go run main.go 
4. you can open it in browser using local host - localhost:8080
5. ctrl+c to close the process

- make file - automation
- docker file -  CI
- e2e tests - end to end tests

# Ideal environment setup

1. Open the filebrowser code
2. Check for docker_config.json file
3. Copy paste the file docker_config.json
4. Rename the copied file with .filebrowser.json
4. Change port to 8080 in copied file
5. Add . infront of /database.db making it ./database.db
6. Add . infront of /srv 
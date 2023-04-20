# bak-from-docker
A program that exports your container and saves it in a directory. It pushes the backup image to your desired DockerHub registry.
Check backup.log to check the backup process.
For using script as a cron job need to remove `read -p` lines and set container name and DockerHub account statically.

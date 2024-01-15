# Install

To run your own Joplin Server, you need to have a running Docker enviornment. This readme will not cover the installation of Docker.

The repository includes a docker compose file for the Joplin Server, as well as a config file for NGINX which you have to copy to your sites-available folder. Make sure to create a symlink of the file to the sites-enabled folder.

```bash
docker-compose up -d -f joplin-docker-compose.yml
```

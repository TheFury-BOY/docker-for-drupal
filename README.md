# Docker-compose for drupal dev

> LICENCE MIT

## The compose config for a local Drupal CMS website

- This compose expose Drupal on the port 8080
- This compose use postgres:latest for the database and drupal:latest
- If you want, you can add an adminer container 
- This compose file uses the Bind Mounting for the drupal file and Volumes to persists the data in your db
- Tip: Drupal assumes DB is localhost, but it will actually be on the compose service name you give it
- Use Docker Hub documentation to figure out the right environment and volume settings

Created by [adriendudeck.online](https://adriendudeck.online)

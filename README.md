# Cryptonite Final Version

## Security fixes
   * sonarqube fix removed the database seeders from crypto-back located "src/main/java/io/uranus/ucrypt/data/seeders/DatabaseSeeder.java"
   * zap fix

## To run the application: 
   * You need to have Docker Desktop and MySQL Server
   * You need a fresh ucrypt database on your MySQL Server
   * You can modify the application.properties file to change the admin email and password.
   * For MySQl connection, you will need to modify the file application.properties and docker-compose.yml file (username, password, etc.
   * Then start the Docker Desktop(better to delete old images and containers if any)
   * Then open the repo and cd to crypto-back and run "docker-compose build" wait for it to finish successfully, and then run "docker-compose up".
   * Visit localhost obviously port 80.
   * Try changing role.
   * Try uploading and then deleting files at admin resources section.

  

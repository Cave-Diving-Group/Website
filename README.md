#Cave Diving Group Website
This is the new membership database/website in development for the cave diving group.

The site is build in PHP on the Phalcon framework the DB is MySQL.

This was chosen as its well used and easy to pick up as new volunteers come onto and off the project.

##Development
Development should be done in feature branches with a pull request to merge.

Docker and Docker Compose are required for development.

To bring up the stack run `docker-compose up` the website is available on port 80.

To run Phalcon commands run `docker-compose run app phalcon <command>`.
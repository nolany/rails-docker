# README

You will need to make sure that you have  Docker Compose installed https://docs.docker.com/compose/install/

git clone http://github.com/nolany/rails-docker.git

cd rails-docker/

docker-compose run web rake db:create

docker-compose up

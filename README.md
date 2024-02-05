# Rails Friends App

This is a test project to help me learn rails. It includes basic crud principles.

I'm following along with a tutorial video on youtube found [here](https://youtu.be/fmyvWz5TUWg?si=hiPRVt9BDOA-6Jcv)

Unlike the video, I'm running rails in a docker container and using a postgres database.


## First Time Setup
```bash
docker compose build
docker compose run web rails db:setup
docker compose up
```



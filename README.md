# Spring Boot drone

Example using Spring Boot, gradle and [drone-ci](https://drone.io/).

1. [Setup github integration](http://readme.drone.io/admin/setup-github/)
2. Create a the file drone/[.env](https://docs.docker.com/compose/env-file/) file containing `DRONE_GITHUB_CLIENT`, `DRONE_GITHUB_SECRET` and `DRONE_SECRET`
3. Run `docker-compose up` in the drone folder
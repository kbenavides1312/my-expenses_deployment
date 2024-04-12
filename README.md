# my-expenses.deployment

build dev images
```
docker compose -f docker-compose.dev.yml build
```

run dev containers (detached)
```
docker compose -f docker-compose.dev.yml up -d
```

stop dev containers
```
docker compose -f docker-compose.dev.yml down
```

local app containers don't have port mapping for apis because we want to access them through nginx only


insteresting links

* [communication-between-multiple-docker-compose-projects](https://stackoverflow.com/questions/38088279/communication-between-multiple-docker-compose-projects)
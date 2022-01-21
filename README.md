# docker-compose-ngnix
![docker-nivel](https://user-images.githubusercontent.com/84384521/150500166-aea23cf9-aff5-48d7-a2ad-9ee419be457a.jpg)
this is how my stack look like :
docker-tutorial/
├── .docker/
│   ├── backend/
│   ├── mysql/
│   └── nginx/
│       ├── certs/
│       │   ├── .gitignore
│       │   ├── demo.test.crt
│       │   └── demo.test.key
│       ├── conf.d/
│       └── Dockerfile
├── src/
├── .env
├── .env.example
├── .gitignore ( i have deleted this)
├── demo
└── docker-compose.yml

after any change please do : demo down && demo start
to run and stop the stack we need to use docker-compse up -d ( to run it in the background)

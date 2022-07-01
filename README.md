# php-with-docker-template

## Installation

Copy the `.env` file

```
cp .env.example .env
```

Build docker image

```
docker-compose build
```

Run docker image

```
docker-compose up
```

Run the following command to install the package through Composer:

```bash
docker-compose exec composer install
```

## Usage

Stop docker

```
docker-compose stop
```

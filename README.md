# docker-compose-konga
docker-compose runtime environment for [Konga](https://github.com/pantsel/konga).

## Usage

1. Install `docker` and `docker-compose` if you haven' t.

2. Clone this repository.

3. Copy the `.env.example` to `.env`. Modify configuration items as needed.

4. Run `docker-compose --profile database up -d` to prepare the database and start the konga.

```
shell> git clone https://github.com/jichangfeng/docker-compose-konga.git
shell> cd docker-compose-konga
shell> cp .env.example .env
# Modify configuration items as needed.
shell> docker-compose --profile database up -d
```

# AWS Docker Astroneer

1. Run terraform:

```bash
terraform init
terraform apply
```

2. SSH into the machine:

```bash
./ssh_to_machine.sh
```

3. [Install Docker](https://docs.docker.com/engine/install/ubuntu/)

4. Add user to `docker` group:

```bash
sudo usermod -a -G docker $USER
```

5. Clone this repo on the new machine

6. Setup `.env` file based on [docker-astroneer-server](https://github.com/barumel/docker-astroneer-server/tree/develop)

6. `docker compose up -d`

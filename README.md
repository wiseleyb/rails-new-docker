# Create new Rails project with docker

```
git clone https://github.com/wiseleyb/rails-new-docker.git
chmod 755 entrypoint.sh
dcbuild
docker compose run --no-deps web rails _6.1.7.4_ new rtest --force --skip-git --database=postgresql
```

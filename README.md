# Create new Rails project with docker

```
git clone https://github.com/wiseleyb/rails-new-docker.git
chmod 755 entrypoint.sh
dcup --build
docker compose run --no-deps web rails new rtest --force --skip-git --database=postgresql
```

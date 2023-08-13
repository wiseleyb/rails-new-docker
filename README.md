# Create new Rails project with docker

```
git clone https://github.com/wiseleyb/rails-new-docker.git
chmod 755 entrypoint.sh
dcbuild
docker compose run --no-deps web rails _5.2.8.1_ new rtest --force --skip-git --database=postgresql
cp -R docker-files/docker rtest/
cp docker-files/entrypoint.sh rtest/
cp docker-files/docker-compose.yml rtest/
cd rtest
dcup --build
```

# Check out with submodules

To check out the repository, you need to clone submodules as well. So check out with the following command:

```git clone --recurse-submodules -j8 git@github.com:Aubrary/Aubrary.Compose.git```

## To update submodule commit pointer
```
git submodule update --remote --merge
git add -A && git commit -m "Update submodules" && git push
```

# How to run
```
docker-compose rm
docker-compose build
docker-compose up
```

### Traefik
Located on http://localhost:8080

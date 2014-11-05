# Docker RSS Feed Validator Instance

Installs and runs an instance of http://validator.w3.org/feed/ from the source
tree at https://github.com/rubys/feedvalidator

# Usage

```sh
$ sudo docker run -d -p 8080:80 unboxed/feedvalidator
```

Options:

* "-d" Runs in the background
* "-p 8080:80" Redirects port 8080 on the docker host to port 80 on the container.

Once you have run the above command, connect to your Docker server on port 8080
with a url like http://dockerserver.example:8080/

# Queries

Please raise issues on the project GitHub page.

# Build Process

```shell
$ ./build.sh
```

# Thanks

Thanks go to [Dan Pupius](https://medium.com/dev-tricks/apache-and-php-on-docker-44faef716150)
for his Apache config files from his blog.

Additional thanks go to
[magnetikonline/html5validator](https://registry.hub.docker.com/u/magnetikonline/html5validator/)
for further Apache config options, and his related HTML5 validator Docker
instance.

# License

MIT License - please see the project LICENSE file for details.

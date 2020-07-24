To prepare a docker image for a registry, we tag it and specify our newly
created registry.

`docker tag clarus-site:v1 localhost:5000/hugo-site:v1`{{execute}}
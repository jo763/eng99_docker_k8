`docker pull jo763/nginx_test2:latest`
`docker run -d -p 80:80 jo763/nginx_test2`


`docker commit ccf7 jo763/nginx_test2`
`docker push jo763/nginx_test2`


`/c/Users/Joe/Desktop/DevopsTraining/eng99_docker_k8`

`docker cp index.html <container_ID>:<path>`

`docker cp modules.html 622cd08b122f:/usr/share/nginx/html.modules.html`

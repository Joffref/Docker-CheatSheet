# Run Nginx
As we learned in FirstStep : 
```bash
 docker run -tid --name web -p 8080:80 nginx:latest
```

In this basic usage we can see some options:
- `-tid` t : allocate a pseudo-TTY, i : interactive shell, d : run container in background
- `--name` : name of your container
- `-p` attachs a port from host to the container (`# -p host_port:container_port`) 
- `nginx:latest` pulls from hub the latest version fo nginx

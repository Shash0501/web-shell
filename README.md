Run the below command and then visit http://localhost:8080/ .

```bash
npm install
docker run -d --rm -p 127.0.0.1:8080:8080 -v "$PWD:/usr/share/nginx/html" --name web-shell nginxinc/nginx-unprivileged
node server.mjs
```

Instrucciones para craer
git submodule add git@github.com:rvnext/pagina-web.git content
docker build -t hello-nginx:latest .

Instrucciones para ejecutar
docker run --name hello-nginx-container -it --rm -p 8070:80 hello-nginx:latest

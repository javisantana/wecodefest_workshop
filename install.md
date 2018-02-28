Instala [docker](https://www.docker.com/). Cada plataforma tiene su método. Echa un ojo al comentario de @aitor en este mismo gist si usas OSX.

Ejecuta lo siguiente en la consola:

```
mkdir workshop
cd workshop
docker run -it --rm -p 8888:8888 -v `pwd`:/home/jovyan/work jupyter/scipy-notebook
```

Accede a [http://localhost:8888](http://localhost:8888) deberías cargar algo con un logotipo donde ponga "jupyter"

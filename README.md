# Ejemplo para voluntarios en Ciencia de Datos - GECI

Para verificar que tu computadora se encuentra configurada correctamente, ejecuta el
siguiente código en la terminal:

```bash
git clone https://github.com/IslasGECI/ejemplo_para_voluntarios.git
cd ejemplo_para_voluntarios
docker build --tag islasgeci/ejemplo_para_voluntarios .
docker run --rm --volume ${PWD}:/workdir islasgeci/ejemplo_para_voluntarios
```

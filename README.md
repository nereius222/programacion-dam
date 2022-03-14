# Notebooks de programación

## Configuración

Para ejecutar los notebooks es necesario tener instalado previamente Docker.

Para crear el contendor de notebooks por primera vez, ejecuta el siguiente comando desde DENTRO del proyecto

```bash
docker run -d -p 127.0.0.1:8888:8888 --name programacion-notebooks -v $PWD:/home/jupyter deepjavalibrary/jupyter 
```

### Arrancar el notebook

Para arrancar el contenedor más adelante ejecuta

```bash
docker start programacion-notebooks
```

## Notebooks


Para acceder a los notebooks abre el siguiente enlace en el navegador: http://localhost:8888/tree/home/jupyter/notebooks



# docker-compose-demo
Ejemplo simple de aplicaciones agrupadas sobre entorno Docker Compose, usando submodulos GIT

## Para agregar submodulos

- Agregar Submodulo Node
```
git submodule add https://github.com/codigonet/docker-node-demo src-node
```

- Agregar Submodulo Python/Flask
```
git submodule add https://github.com/codigonet/docker-python-demo src-flask
```

## Para actualizar submodulos existentes

- Actualizar Submodulo Node
```
cd src-node
git pull
```

- Actualizar Submodulo Python/Flask
```
cd src-flask
git pull
```

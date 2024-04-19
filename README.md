# Prueba técnica Talent

## Descripción

Prueba técnica de José Tovar
Codeigniter 4
Mysql


## Instalación

Pasos para instalar el proyecto, incluyendo cualquier dependencia necesaria.

```bash
git clone https://github.com/jltf2308/talent.git
cd talent
composer install
```

## Configuracion
### generamos la clave
```bash
php spark key:generate
```

### creamos la base de datos
```bash
php spark db:create talent
```

### creamos la base de datos
```bash
php spark migrate
```
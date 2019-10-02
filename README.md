# DUOC UC

## Ejercicios Modulo 1

### 1)Crear una app en blanco

```bash
 ionic start modulo1 blank --type=angular --cordova

 cd modulo1
```

Actualizar id y nombre de app en config.xml

```xml
<widget id="cl.laboratoriodiseno.aaravena.modulo1" ...>
    <name>modulo1</name>
    <description>Ejercicio primer modulo</description>
```

Agregar a un repositorio ya creado (pero vacío)

```bash
 git remote add origin https://github.com/alaravena/Modulo1.git #por ejemplo
```

### 2)Crear iconos y splash

Modificar icono.png y splash.png

```bash
 ionic cordova platform add android
 ionic cordova platform ios android

 ionic cordova resources
```

Es un buen momento para hacer un push del repositorio.

### 3)Agregar una página de detalle

```bash
 ionic generate page pages/detalle
```
Trasladar home a carpeta pages y actualizar routing

### 4)Transformar título de barra de navegación en variable

Segun Slide 23 y 24

### 5)Agregar una imagen en la barra de navegación

Segun Slides

### 6)Crear una lista en home

Segun Slide 24
Ajuste scss para correcta visualización

### 7)Utilizar un objeto json para el contenido

### 8)Transformar el header en componente

Segun Slide

```bash
 ionic generate component encabezado
```

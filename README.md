# Auxiliar 4: HTML y CSS

En esta actividad deben ✨embellecer✨ la página de login (o la de register) del proyecto usando las propiedades de CSS que gusten (la idea es que no utilicen Bootstrap, al menos para esta actividad, para sus proyectos recomendamos fuertemente Bootstrap u otro framework).

Esta vez no hay instrucciones establecidas, solo usen su creatividad para obtener un resultado similar a este para la página de registro del proyecto:

![image](https://user-images.githubusercontent.com/62437376/163250617-d60d07e6-7b5d-4503-94cc-599970bc4950.png)

Solo deben trabajar con el archivo `register.html` que está en `todoapp/templates/todoapp/`, y con `style.css` que está en `todoapp/static/todoapp/`

> (Se recomienda fuertemente ver el video de la auxiliar para entender cómo partir)
> https://youtu.be/kku0yczjW-4

Algunos recordatorios:

### Linkear hoja de estilos
```
<!-- Estilos locales: -->
<link rel="stylesheet" type="text/css" href="static/todoapp/style.css">

<!-- Estilos de Bootstrap: No se usará para esta actividad -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-F3w7mX95PdgyTmZZMECAngseQB83DfGTowi0iMjiWaeVhAn4FJkqJByhZMI3AhiU" crossorigin="anonymous">
```
Estas líneas deben ir dentro del `<head>...</head>` de su archivo .html. Luego podrán usar los estilos que definan en el archivo style.css, o los estilos de Bootstrap guiándose por la documentación (por ejemplo, [los botones](https://getbootstrap.com/docs/5.1/components/buttons/))

### Enlaces
- [Selectores de CSS](https://www.w3schools.com/cssref/css_selectors.asp)
- [CSS Diner](https://flukeout.github.io/): Para practicar el uso de selectores.
- [Flexbox Froggy](https://flexboxfroggy.com/): Para practicar el uso de `display: flex;`.
- [Bootstrap](https://getbootstrap.com/)

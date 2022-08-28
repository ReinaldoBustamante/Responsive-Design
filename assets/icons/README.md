# Inicializando 

## Estructura html
Como se dijo anteriormente utilizaremos 1 header , 4 secciones y 1 footer.
Siguiendo el esquema semantico la estructura nos quedaria de la siguiente manera.
~~~
<header></header>
    <main>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
    </main>
<footer></footer>
~~~

## Assets
Podemos descargar los assets(imagenes e iconos) de figma.

## Agregando fuentes

La fuete a utilizar es inter y DM sans. para agregar esta accederemos a google fonts
~~~
<link href=“https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Inter:wght@300;500&display=swap” rel=“stylesheet”>
~~~
esta linea la agregaremos en nuestro html con el fin de tenerla importada.

## Estilos base.
Es recomendable por buenas practica acomodar los estilos en relacion a ciertos 
temas.
- Posicionamiento (static, absolute, relative, fixed)
- Modelo de caja (padding, margin, border, content)
- Tipografia (tipos, tamaños de fuente, etc)
- Estilos visuales (box-shadow, border-radius, gradient, etc)
- Otros (reglas css y mas)

~~~
:root {
    --bitcoin-orange: #f7931a;
    --soft-orange: #ffe9d5;
    --secondary-blue: #1a9af7;
    --soft-blue: #e7f5ff;
    --warm-black: #282623;
    --black: #201e1c;
    --grey: #bababa;
    --off-white: #faf8f7;
    --just-white: #fff;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html{
    font-size: 62.5%;
    font-family: 'DM Sans', sans-serif;
}
~~~
# Website mockup using HTML, CSS, and NORMALIZE.CSS

## 🔎I will use this page to explain some aspects of the code.

##### The class attribute in HTML is used to identify one or more elements and to apply styles to them or manipulate them with JavaScript.

````html
<header>
    <h1 class="titulo">Matías Celis <span>Junior Developer</span></h1>
</header>
````

##### In CSS, we select classes like this: ".titulo span". This line of code allows us to modify the size of the span element that belongs to the "titulo" class.

````css
.titulo span{
    font-size: 2rem;
}
````

##### Div is a generic container used to group elements. In this snippet, we'll group the navigation bar links.

````html
<div class="nav-bg"> <!--El div no puede ir dentro de un nav-->
    <nav class="navegacion-principal contenedor">
        <a href="#">Inicio</a>
        <a href="#">Sobre Mi</a>
        <a href="#">Clientes</a>
        <a href="#">Contacto</a>
    </nav>
</div>
````

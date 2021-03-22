# 12UsodeGridenproyecto
* 12 web Creación de pagina receta de pizza. uso de grid

```javascript
/** Grid aqui**/
nav .navegacion {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}
@media screen and (min-width:768px) {
    .contenido-principal{
        display: grid;
        grid-template-columns: minmax(100px, max-content) auto minmax(100px, max-content);
        grid-template-rows: repeat(4, auto);
        gap: 1rem;
        max-width: 1200px;
        margin: 0 auto;
    }
    .titulo {
        grid-column: 1/4;
    }
    .informacion {
        grid-row: 2/3;
    }
    .imagen1 {
        grid-row: 3/4;
        grid-column: 3/4;
    }
    .entrada {
        grid-column: 2/3;
        grid-row: 2/5;
    }
    .imagen2{
        grid-row: 4/5;
    }
}

.footer .contenedor {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}
```

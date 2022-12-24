# Practica HTML

Practica_LauncherLATAM

Maquetar en HTML el siguiente caso y generar su repositorio con el ejercicio.
Recordemos que solamente se necesita maquetar como un prototipo, no es necesario que tenga funcionalidad completa en la informacón.

---

[Link](https://hydr0bius.github.io/Practica1/) de la práctica finalizada.

En esta práctica se vieron las listas ordenas y listas donde orden no importa "ol" y "ul

```HTML
        <ol>
            <!-- lista ordenada -->
            <li>1 insert text</li>
            <li>2 insert text</li>
            <li>3 insert text</li>
        </ol>
        <ul>
            <!-- lista no ordenada -->
            <li>insert text</li>
            <li>insert text</li>
            <li>insert text</li>
        </ul>
        
```

De igual modo se vieron los diferentes comportamientos del *input* el cual se le puede poner *clases* e *id* para darle estilo y usarlo en Js.

El ***input*** suele ir seguido de un *label*

```HTML
<input type="checkbox" id="Asado" name="Asado" value="Asado">
<label for="Asado">Asado</label>

<input type="text">     
<input type="number">     
<input type="color">
<input type="password">
<input type="date">
<input type="file">
<input type="submit">
<input type="time">
<input type="month">
<input type="range">
```

En el input se pude especificar los rangos minimos y maximos de caracteres a ingresar como se muestra a continuación:

```HTML
<input type="number" id="pastor" name="pastor" placeholder="¿Cuántos?" min="0" max="20">
```

El *placeholder* sirve para poner un texto adentro del *input*, puede servir para enfatizar.

---

Para este caso práctico se realizo un ejercicio del menú de una taqueira el cual se le puso un logotipo realizado en *Canvas*.

La página esta dividida en tres secciones; la primera parte esta contenida por el *menú*, la segunda parte muestra las sucursales y por ultimo la parte de pedidos.

Se hizo uso de *fieldset* y *legend* para para encapsular el contenido y se visualice en la página:

```HTML
<fieldset>
        <legend>Insert title</legend>
            <div>
                <p>insert text</p>
            </div>
</fieldset>
```

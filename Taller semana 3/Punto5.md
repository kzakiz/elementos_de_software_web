1. ¿Por qué los enlaces son verdes y no rojos?
    R= Es porque esta petición (ul.news li.news__item a.news__item-link {color: green;}) en el codigo sobreescribe el
    color rojo dejando los enlaces verde, ya que es más especifica.

2. Hacer que los enlaces sean rojos.
    R= Usando a {color: red !important;}

3. Rehacer el HTML usando <div> en lugar de <ul> y <li>. ¿Qué pasa?
    R= Se rompe el CSS porque usa ul y li, y debido a esto se pierde la semantica.

4. Comentar el CSS que no se puede tocar y reescribir este CSS usando una clase por selector para que se vea igual.
    R= Se mantiene el mismo diseño visual, pero el CSS deja de depender de las etiquetas (ul, li) y pasa a depender de las clases, haciendolo mas reutilizable y flexible.
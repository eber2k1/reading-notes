# PROGRAMACIÓN FUNCIONAL 

| #  | Pregunta |  | Respuesta |
|----|-----------|--------------|
| 1  | ¿Qué diferencias fundamentales encuentras entre resolver un problema con programación imperativa y hacerlo con programación funcional? | | La programación imperativa se basa en dar instrucciones paso a paso, modificando el estado del programa mediante bucles y variables mutables. En cambio, la programación funcional se enfoca en usar funciones y expresiones sin cambiar el estado. |
| 2  | ¿En qué situaciones específicas crees que es más ventajoso aplicar funciones puras, y en cuáles no lo sería? | Cuando el código no necesita cambiar el estado global y solo retornar un valor |
| 3  | ¿Qué rol juegan las funciones de orden superior como `map()`, `filter()` y `find()` en la calidad y legibilidad del código? | | Estas funciones permiten manipular colecciones de datos de manera más declarativa, evitando bucles explícitos. |
| 4  | ¿Por qué la programación funcional facilita las pruebas unitarias y el debugging? | | Porque se pueden probar funciones de manera aislada sin preocuparnos por estados compartidos y sin alterar modficaciones de los estados globales. |
| 5  | ¿Cómo puedes integrar efectivamente el paradigma funcional en proyectos que originalmente fueron construidos con un enfoque imperativo? | | Convertir funciones mutables en funciones puras cuando sea posible y reemplazar bucles for con `map()`, `filter()` , `find()` etc. |
# Explicación

Hice la importación de los hooks.

Cree el contexto CountContext utilizando React.createContext() así es utilizado para pasar el estado del contador a la función setCount y que así no sea necesario pasar proops manualmente.

Se utilizó useState para inicializar el estado del contador en 0.
Utilicé UseEffect para actualizar el título de la página (cada vez que el número del contador cambia, se actualiza el título de la página con el valor actual del contador)
Utilicé useContext para acceder al valor del contador y la función setCount.

Todo el contenido está dentro de "< countContext.Provider > " para que el contexto esté disponible para los componentes descendientes.
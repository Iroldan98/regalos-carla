# Regalos para el cumple de Carla

Una página sola (`index.html`) con la lista de regalos que quiere Carla. Sus
amigas abren el link, ven cada regalo con su tienda y, cuando compran uno,
tocan **"Ya lo compré"**: a las demás les aparece tachado. Solo el celular que
lo marcó lo puede desmarcar ("Me equivoqué").

- **Dónde se ve:** en Vercel, que publica solo cada cambio de este repo.
- **Dónde están los regalos:** en Supabase, en el proyecto `regalos-carla`
  (tabla `regalos`). Es una base aparte, no tiene nada que ver con otras apps.
- **Para cambiar los regalos:** pedíselo a Claude.

La dirección y la clave de Supabase que están en `index.html` son públicas a
propósito (las ve cualquier navegador): la tabla no se puede leer ni cambiar
directo, solo con las tres funciones de la base (ver la lista, marcar y
desmarcar).

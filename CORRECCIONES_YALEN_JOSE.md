# Correcciones del primer commit

Equipo de cambios: Yalen y Jose.

Commit publicado inicialmente:

```text
b3e5d83 Inicio limpio con archivos base corregidos
```

## Cambios de Jose

- Se corrigio la regla de descuentos para cumplir las historias de usuario:
  - 20% de descuento general para todos los productos.
  - 5% adicional para productos de ninos.
  - Total para ninos: 25%.
- Se corrigieron las tarjetas de productos para mostrar:
  - precio original tachado;
  - precio final;
  - badge `-20%`;
  - badge `+5% ninos` cuando aplica.
- Se corrigio el resumen del carrito:
  - subtotal sin descuento;
  - descuento total;
  - total final.

## Cambios de Yalen

- Se agrego persistencia local con `localStorage`, sin base de datos externa.
- Se corrigio que los productos registrados se perdieran al recargar.
- Se corrigio que el carrito se perdiera al recargar.
- Se agrego registro local de pedidos al finalizar compra.
- Se agrego la seccion `Pedidos` para consultar el historial local.
- Se corrigio el checkout para descontar stock despues de una compra.

## Correcciones compartidas

- Se mantuvo el proyecto en HTML, CSS y JavaScript vanilla.
- Se dejaron los datos funcionando localmente en el navegador.
- Se corrigio el flujo principal segun `user_stories_farmacia`:
  - registrar producto;
  - ver inventario;
  - buscar y filtrar;
  - agregar al carrito;
  - modificar cantidades;
  - eliminar productos;
  - ver totales;
  - finalizar compra;
  - registrar pedido local.
- Se redujo el riesgo de inyeccion HTML al pintar nombres y descripciones ingresadas por el usuario.

## Nota tecnica

No se agrego backend ni base de datos. La persistencia queda guardada solamente en el navegador mediante `localStorage`.

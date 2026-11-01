# Liquid Glass para Jellyfin

Tema para la interfaz web de Jellyfin (probado con 12.4) inspirado en el Liquid Glass de Apple: barra superior flotante de cristal, tarjetas con reflejo de luz, botones tipo píldora, menús y reproductor translúcidos.

## Instalación

En Jellyfin: **Panel de control → General → CSS personalizado**, pega esta línea y guarda:

```css
@import url('https://cdn.jsdelivr.net/gh/ex6tense/jellyfin-liquid-glass@main/tema.css');
```

Recarga con **Ctrl+F5**. Si tenías otro tema (Ultrachromic, ElegantFin…), quítalo primero: los dos a la vez se pisan.

## Actualizar

jsDelivr guarda en caché la rama `main` hasta 12 horas. Para ver un cambio al momento, abre:

```
https://purge.jsdelivr.net/gh/ex6tense/jellyfin-liquid-glass@main/tema.css
```

y recarga Jellyfin.

## Qué incluye

- Fondo oscuro con resplandores violeta y azul (el cristal necesita algo detrás que difuminar).
- Barra superior flotante en la que cada enlace (bibliotecas, Favoritos) es una píldora de cristal y cada icono una burbuja redonda.
- En el reproductor, volver, el título y los botones son burbujas sueltas; los controles de abajo van en una cápsula.
- Al pasar el ratón por una tarjeta, reproducir y visto/favorito/más son burbujas de cristal con icono blanco.
- Menú lateral, menús, ventanas y avisos de cristal.
- Tarjetas redondeadas con sombra y reflejo, que crecen al enfocarlas; anillo blanco al navegar con mando o teclado.
- Barra de progreso blanca, botones y campos de cristal, fuente Inter.
- Móvil: cápsulas más pegadas al borde.
- Respeta *reducir movimiento* y *reducir transparencia* del sistema.

El Liquid Glass de Apple también deforma lo que hay detrás como una lente; eso no se puede hacer con CSS de forma fiable, así que el tema imita el desenfoque, el brillo y la translucidez.

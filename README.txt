CIUDAD DÚO — PROTOTIPO COOPERATIVO PARA ANDROID

Juego original, inspirado en los clásicos de mundo abierto en vista desde arriba.
NO contiene archivos, mapas, personajes ni música de Rockstar.

QUÉ INCLUYE
- Mundo 2D, dos jugadores, vehículos y 8 maletines como misión.
- Joystick virtual, botones de disparar y subir/bajar de autos.
- Controles en PC: WASD o flechas, E (auto), ESPACIO (disparar).
- Sala con código de 6 caracteres; conexión WebRTC usando PeerJS.

CÓMO PUBLICAR GRATIS PARA QUE AMBOS JUEGUEN
1. Crea un repositorio público nuevo en GitHub, por ejemplo ciudad-duo.
2. Sube este archivo index.html en la raíz.
3. En Settings > Pages elige Deploy from a branch > main > / (root).
4. Abre la dirección HTTPS publicada (https://USUARIO.github.io/ciudad-duo/)
   desde ambos teléfonos en Chrome.
5. Uno pulsa CREAR SALA y comparte el código con el otro.
6. El otro pulsa UNIRME A LA SALA e introduce ese código.

ADVERTENCIAS
- La conexión usa el PeerServer Cloud público y WebRTC, sin servidor propio.
- En algunas redes móviles/NAT los dos celulares no lograrán conectarse;
  hará falta un servidor TURN o un backend propio para mayor fiabilidad.
- La sala termina cuando se cierra la pestaña del anfitrión.
- Esto es un prototipo: todavía no hay misiones complejas, policías,
  guardado persistente ni anti-trampas.
- Se necesita Internet para cargar PeerJS y establecer la partida.

# Notas de implementación — NEXUS Volumen 2

- Se tomó como base el HTML de NEXUS proporcionado en esta conversación.
- El objetivo es conservar el comportamiento existente y cambiar la capa de presentación; no se reescribió intencionalmente la lógica de misiones.
- Se aplicó una estética clara inspirada en Apple: tipografía del sistema, superficies translúcidas, fondos neutros, azul de acción, radios amplios y sombras contenidas.
- Se añadieron estilos para foco visible, interacción táctil, movimiento reducido, transparencia reducida y contraste aumentado.
- Se conservaron los overlays oscuros en banners con imágenes para mantener la legibilidad del texto.
- Verificación estática: la fuente y la variante tienen los mismos conteos de bloques `<script>` (2), `function ` (74), botones (74) y atributos `id=` (253).
- Límite: no se completó una prueba de extremo a extremo en navegador; no debe interpretarse como certificación de todos los flujos.
- La carpeta es independiente y no modifica ni publica en el repositorio original.

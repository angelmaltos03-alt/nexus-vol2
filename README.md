# NEXUS Volumen 2 — copia funcional con Apple Design Skill

## Objetivo
Esta carpeta contiene una copia independiente de NEXUS Control Tower basada en el HTML fuente proporcionado, con una nueva capa visual inspirada en `apple-design`. La intención es mantener la misma aplicación —mismos módulos, misiones, controles, cálculos, validaciones y reportes que existían en ese archivo— cambiando la presentación visual, no reescribiendo el simulador.

## Archivos
- `index.html`: aplicación autónoma con el HTML y JavaScript de origen y una capa de estilos Apple-inspired.
- `DESIGN-NOTES.md`: alcance, criterios visuales y límites de las pruebas.

## Principios visuales aplicados
- Claridad: tipografía del sistema, jerarquía más limpia y superficies claras.
- Feedback y agencia: se conservan los controles y estados funcionales existentes, con estados visuales más claros.
- Consistencia: radios, bordes, espacios y elevaciones compartidos.
- Materiales translúcidos: superficies tipo glass con alternativas para reducir transparencia.
- Accesibilidad: foco visible, contraste aumentado opcional y respeto a movimiento reducido.
- Movimiento con propósito: transiciones breves y respuesta visual al presionar controles.

## Verificación y límites
La adaptación está planteada como una capa visual sobre el archivo fuente, no como una reconstrucción funcional. Los contadores estáticos del HTML coinciden entre la fuente y la variante: 2 bloques `<script>`, 74 apariciones de `function `, 74 botones y 253 atributos `id=`. Estos conteos ayudan a verificar que la estructura no se haya eliminado, pero **no sustituyen una prueba completa de todos los recorridos interactivos**. La apertura automatizada del navegador no terminó dentro del tiempo disponible, por lo que no afirmo que todos los flujos estén certificados.

La copia no modifica ni publica nada en el repositorio original `Protocolo-Nexus`. Para usarla, abre `index.html` en un navegador moderno. Antes de desplegarla, valida login, navegación, las 3 sesiones, los 24 retos, proveedores, guardado local y exportaciones PDF/CSV.

# Notas de diseño — NEXUS Apple Design Concept

## Qué se exploró
Una dirección visual más calmada y cuidada, inspirada en los principios del skill `apple-design`, sin copiar literalmente el diseño de Apple.

- **Respuesta inmediata:** botones con estados activos, feedback de proveedor y mensajes breves.
- **Jerarquía:** métricas principales arriba, misiones como siguiente paso y proveedores en un panel propio.
- **Materiales y profundidad:** superficies translúcidas moderadas para navegación, tarjetas y modal.
- **Tipografía:** fuentes del sistema, títulos con tracking óptico y tamaños fluidos.
- **Continuidad espacial:** transiciones cortas, mismo espacio de navegación y modal centrado.
- **Flexibilidad:** layout responsive y navegación móvil.
- **Accesibilidad:** foco nativo, `aria-live`, Escape para cerrar modal, y soporte para `prefers-reduced-motion`, `prefers-reduced-transparency` y `prefers-contrast`.
- **Responsabilidad:** advertencia de maqueta, datos de ejemplo y sin conexión al sitio real.

## Interacciones
Modal de bienvenida, navegación por cuatro vistas, selector de proveedor con feedback, mensajes toast, CSV de demostración e impresión.

## Límites
No incluye el motor real de misiones, el registro real de intentos, la validación académica ni la generación real del PDF de NEXUS. Las acciones de exportación están marcadas como demostrativas para evitar confusión.

## Recomendación
Revisar en escritorio y móvil antes de decidir si se integra algo. Cualquier integración futura debe realizarse en una copia o rama separada, nunca sobrescribiendo directamente la versión publicada.

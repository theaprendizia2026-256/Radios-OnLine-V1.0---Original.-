# Radio Online Minimalista

Aplicación de streaming de audio diseñada para la concentración y la desconexión mediante música clásica y ambiental.

---

## Concepto

Diseñada bajo los principios de la **Ingeniería de Invisibilidad**: interfaz minimalista, consumo de recursos nulo y máxima eficiencia. Ideal como música de fondo para acompañar flujos de trabajo de alta concentración.

---

## Stack Tecnológico

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla).
* **Infraestructura:** CDN (Content Delivery Network) mediante Vercel.
* **Arquitectura:** PWA instalable (Progressive Web App: comportamiento de aplicación nativa en móvil o escritorio).

---

## Método de Desarrollo (Cloud-Native)

Este proyecto se gestiona íntegramente en la nube bajo el siguiente flujo:

1. **Edición:** Realizada directamente en el entorno web de [GitHub.dev](https://github.dev/github/dev).
2. **Sincronización:** El repositorio se conecta automáticamente a [Vercel](https://vercel.com/).
3. **Despliegue:** Cada commit a la rama principal dispara un despliegue optimizado en el Edge Network.

---

## Uso

Acceda a la URL de producción: [radios-online.vercel.app](https://radios-online.vercel.app/)

* **Botón Power:** Inicializa o detiene el stream (con manejo de excepciones de red).
* **Botones Prev/Next:** Navegación cíclica por la lista de emisoras (`STATIONS` en `js/script.js`).

---

## Estatus

Estable (v1.0).

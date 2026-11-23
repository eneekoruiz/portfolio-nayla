# Portfolio Visual · Nayla Aguado

Sitio web personal y portfolio interactivo para la diseñadora gráfica y directora de arte Nayla Aguado, desarrollado con React 18, TypeScript, Vite, Tailwind CSS y scroll inercial.

- **Demo en vivo:** [portfolio-nayla-one.vercel.app](https://portfolio-nayla-one.vercel.app)
- **Documentación de arquitectura:** [DeepWiki - portfolio-nayla](https://deepwiki.com/eneekoruiz/portfolio-nayla)

## Propósito y Valor Técnico

Diseñado a medida para presentar proyectos de identidad visual, branding editorial y cartelería con máxima pureza estética, fluidez de movimiento y respeto riguroso por las proporciones y la fidelidad cromática de las obras.

- **Desplazamiento Inercial Cinemático:** Integración de la librería Lenis para unificar la velocidad y amortiguación del scroll entre navegadores de escritorio (ratón, trackpad) y pantallas táctiles móviles, logrando una sensación táctil continua.
- **Micro-interacciones y Animaciones de Entrada:** Transiciones y desvelado progresivo de elementos gráficos al entrar en viewport implementados con Framer Motion.
- **Rendimiento Visual y Cero CLS:** Estructura modular de layouts con dimensiones fijas de ratio en imágenes para evitar cualquier desplazamiento inesperado de maquetación (Cumulative Layout Shift) y carga optimizada de recursos WebP.

## Stack Técnico

- **Frontend:** React 18, TypeScript, Vite, Tailwind CSS
- **Animaciones & Scroll:** Framer Motion, Lenis, Lucide Icons
- **Tooling:** ESLint, Prettier, TypeScript

## Puesta en Marcha Local

### Prerrequisitos

- Node.js 18+

### Instalación y Ejecución

```bash
git clone https://github.com/eneekoruiz/portfolio-nayla.git
cd portfolio-nayla
npm install

# Servidor de desarrollo con Hot Module Replacement (HMR)
npm run dev

# Análisis estático de código
npm run lint

# Compilar para producción
npm run build
```

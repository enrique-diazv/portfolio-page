# Portafolio de Enrique Díaz Vera

Portafolio estático de desarrollo de software construido con Astro. Reúne el perfil profesional, conocimientos, herramientas, experiencia y páginas individuales para los proyectos incluidos.

## Tecnologías

- Astro 7
- TypeScript en componentes `.astro`
- CSS nativo
- Vercel Analytics

## Rutas

| Ruta | Contenido |
| --- | --- |
| `/` | Perfil, conocimientos, herramientas y experiencia |
| `/projects` | Índice de proyectos |
| `/projects/watch-later-universal` | Watch Later Universal |
| `/projects/pulsewatch` | PulseWatch |
| `/projects/traffic-sim` | TrafficSim |
| `/projects/cared` | Cared |
| `/projects/rocket-rl-lab` | Rocket RL Lab |

## Desarrollo local

Requisitos: Node.js 22.12 o posterior y npm.

Desde la raíz del proyecto:

```powershell
npm.cmd install
npm.cmd run dev
```

El servidor de desarrollo usa `http://localhost:4321` de forma predeterminada.

## Verificación y compilación

```powershell
npm.cmd run build
```

Astro genera el sitio estático en `dist/`.

## Estructura principal

```text
public/
  images/                  Recursos visuales de los proyectos
src/
  components/              Navegación y componentes compartidos
  layouts/                 Estructura base del documento
  pages/                   Páginas y rutas del sitio
    projects/              Índice y páginas individuales de proyectos
```

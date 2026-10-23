# SCP Inmobiliaria · código

Un repositorio por app. Cada repositorio lleva el topic de su grupo, y así se separan la plataforma, cada proyecto inmobiliario y lo corporativo.

| Grupo | Topic | Qué entra | Repositorios hoy |
| --- | --- | --- | --- |
| Plataforma | `plataforma` | Apps que sirven a todos los proyectos: CRM, app de copropietarios, cotizador | `crm-mml`, `SCP-Tool` |
| Proyecto Mercado Media Luna | `proyecto-mml` | Lo propio del proyecto, como su web | `mercadomedialuna` |
| Corporativo | `corporativo` | Lo de la marca SCP, como su web | `corp-web` (scp.pe) |
| Centro de mando | `centro-de-mando` | La memoria de la empresa en texto: decisiones, registro, marca | `SCP` |

## Reglas

1. Una app, un repositorio. La carpeta local se llama igual que el repositorio (espejo en `D:\SCPInmobiliaria-dev`: `plataforma/`, `proyectos/<proyecto>/`, `corporativo/`).
2. Un proyecto nuevo no copia la plataforma: se agrega a ella. Solo crea lo que es suyo, como su web, en un repositorio `<proyecto>-<app>` con el topic `proyecto-<proyecto>`.
3. Nombres de repositorios nuevos: `plataforma-<app>`, `<proyecto>-<app>`, `corp-<app>`.
4. Nunca se sube `.env` ni video. Cada repositorio tiene `.env.example` sin valores; los videos pesados van por Git LFS o fuera del repositorio.
5. La ficha de cada app vive en `SCP/07-sistemas`. Este índice solo apunta.

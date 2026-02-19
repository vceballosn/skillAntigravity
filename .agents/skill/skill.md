---
name: committer
description: commit changes to the repository 
---

# Formato de Commits

Sigue el estándar de **Conventional Commits** para todos los cambios en este repositorio.

## Estructura del Mensaje

```text
<tipo>[alcance opcional]: <descripción corta>

[cuerpo extenso opcional]

[pie de página opcional]
```

## Reglas Obligatorias

1.  **Título (Descripción corta)**:
    - Debe ser conciso y directo.
    - **Máximo 50 caracteres**.
    - No terminar con punto.
    - Usar imperativo (ej: "add" en lugar de "added" o "adds").

2.  **Cuerpo (Descripción extensa)**:
    - Obligatorio para cambios significativos.
    - Debe explicar el **porqué** de los cambios, no solo el qué.
    - Proporcionar contexto sobre el impacto o decisiones tomadas.

3.  **Tipos permitidos**:
    - `feat`: Nueva funcionalidad.
    - `fix`: Corrección de un error.
    - `docs`: Cambios en la documentación.
    - `style`: Cambios que no afectan el significado del código (espacios, formato, etc.).
    - `refactor`: Cambio de código que no corrige un error ni añade funcionalidad.
    - `perf`: Cambio de código que mejora el rendimiento.
    - `test`: Añadir o corregir pruebas.
    - `chore`: Cambios en el proceso de construcción o herramientas auxiliares.

## Ejemplo

```text
feat(auth): add JWT login support

Implement logical flow for user authentication using JWT tokens.
This change includes the new middleware for token validation 
and the endpoint to generate tokens upon successful login.
```

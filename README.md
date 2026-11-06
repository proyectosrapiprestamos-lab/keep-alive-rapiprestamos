# keep-alive-rapiprestamos

Mantiene activo el proyecto de Supabase **proyectosrapiprestamos**.

- `keep-alive.yml`: consulta la tabla `keep_alive` cada 2 días (Supabase pausa a los 7 días sin uso).
- `keep-github-alive.yml`: hace un commit al mes (GitHub apaga las tareas de repos públicos a los 60 días sin cambios).

Secrets necesarios: `SUPABASE_URL` y `SUPABASE_KEY` (publishable key).

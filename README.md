# Captura de prospectos — Marketino

Forma móvil para que una imprenta registre prospectos con su origen en menos de 1 minuto.
Se conecta a Supabase (proyecto `marketino-imprentas`); cada usuario solo ve los datos de su imprenta (RLS).

- Alta de imprenta nueva: fila en `imprentas` + fila en `miembros` con el correo del usuario + `logos/<slug>.png`.
- La clave incluida es la publicable; los datos los protege RLS.

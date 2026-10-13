# Motor de mercados · panel de revisión

Panel web donde el equipo revisa, edita, aprueba, exporta y publica en Predice los mercados de predicción que crea el motor.

- Publicado con GitHub Pages desde `index.html`.
- Los datos viven en Supabase y solo los ven usuarios dados de alta como revisores. La página lleva la clave **publicable** del proyecto, que es pública por diseño: el acceso lo controlan el login y las reglas de la base de datos.
- Este repositorio solo contiene el panel. El motor (moldes, fuentes, skill) vive en un repositorio privado.
- `index.html` se genera con `python3 scripts/build_web.py` en el repositorio del motor; no se edita a mano.

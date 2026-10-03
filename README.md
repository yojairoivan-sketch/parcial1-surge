# 1er Parcial — Integración continua con Surge.sh y GitHub Actions

Página HTML sencilla que se despliega automáticamente a
**https://yojairo-itla-parcial1.surge.sh** en cada push a la rama `main`,
mediante el workflow `.github/workflows/main.yaml`.

El token de surge se guarda como secret del repositorio (`SURGE_TOKEN`),
así que no queda expuesto en el código.

Estudiante: Yojairo Rodriguez — ITLA, Electiva 2 (2026-C-3)

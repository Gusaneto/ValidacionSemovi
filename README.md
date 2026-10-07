# Interfaz y Validador Dinámico SEMOVI

Este proyecto estático está diseñado para desplegarse fácilmente en **Vercel** vinculado con **GitHub**. Consta de dos vistas principales:

1. **Panel de Control / Interfaz de Administración (`/` o `admin.html`):**
   - Te permite rellenar fácilmente los campos: **Fecha de expedición**, **Tipo de licencia**, **Folio** y **Validez**.
   - Genera automáticamente un **Token Secret** criptográfico aleatorio.
   - Cuenta con un botón para **Generar Enlace Automático** que te entrega la URL lista para copiar y compartir.

2. **Página de Validación (`/validador` o `index.html`):**
   - Recibe los parámetros generados y muestra el diseño oficial de la SEMOVI con los datos actualizados en tiempo real.

## Instrucciones para Vercel y GitHub:
1. Sube todos los archivos de este ZIP a un repositorio en GitHub.
2. Importa el repositorio en Vercel (es un proyecto estático, Vercel detectará la configuración automáticamente).
3. ¡Listo! Tu panel de control aparecerá en la raíz de tu dominio y generará los enlaces dinámicos con tokens aleatorios al instante.

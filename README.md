# COTIZO CONTIGO

**Tus precios, tu propuesta, a tu manera.**

Cotizador de servicios para consultores, mentores y emprendedores. Tú escribes tus servicios y tus precios; la app arma la cotización con el total en vivo y genera un PDF profesional.

**Pruébala aquí:** https://TU-USUARIO.github.io/cotizo-contigo/

> Reemplaza `TU-USUARIO` por tu usuario de GitHub.

## Vista previa

![Inicio](imagenes/inicio.png)
![Catálogo](imagenes/catalogo.png)
![Cotizar](imagenes/cotizar.png)
![Resumen](imagenes/resumen.png)
![Historial](imagenes/historial.png)

<img src="imagenes/movil-cotizar.png" alt="Versión móvil" width="300">

Las capturas usan servicios y precios de ejemplo.

## Qué incluye

- **Catálogo propio:** nombre, descripción, precio, forma de cobro, color e ícono. Sin precios predefinidos: los escribe cada persona.
- **Marca:** nombre, correo, WhatsApp, enlace para agendar y logo opcional.
- **Reglas opcionales:** moneda, descuento por volumen, recargo presencial, impuesto, validez y condiciones.
- **Cotización en 4 pasos** con total en vivo, ajuste manual y validaciones.
- **PDF** descargable y botón para preparar el **email** (el correo no puede adjuntar el PDF automáticamente: hay que adjuntarlo).
- **Historial** con estados (borrador, enviada, aceptada, rechazada), duplicar, editar y eliminar.

## Privacidad

Sin cuentas ni servidores. Los datos se guardan solo en el navegador (`localStorage`) y el PDF se genera en el dispositivo. Incluye un botón para borrar todos los datos.

## Aviso

Los cálculos son una ayuda para armar propuestas; revisa siempre los montos antes de enviarlas. No sustituye asesoría contable ni tributaria.

## Tecnología

Un único `index.html` (HTML, CSS y JavaScript). Usa jsPDF desde cdnjs, por lo que necesita internet para generar el PDF.

## Cómo publicarla

1. Sube `index.html` (y la carpeta `imagenes`) a un repositorio público.
2. **Settings → Pages → Deploy from a branch → main → / (root)**.
3. Espera uno o dos minutos.

Creada por Tiby Hernández.

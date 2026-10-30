# Tokens · Familia Cooler

Monitor de consumo de Codex, Claude y Gemini / Google AI para la barra de macOS.

**[Descargar Tokens y ver las versiones](https://github.com/leomobel/cooler-tokens-updates/releases)**

## Instalación

La versión 1.0.0 es para Mac con Apple Silicon (M1 o posterior) y macOS 13+.
Descarga el ZIP, descomprímelo y copia Tokens.app a tu carpeta Aplicaciones.
La aplicación aparece en la barra superior. Abre Configuración para seleccionar
las IAs que quieres monitorear y conectar tus cuentas.

Esta primera versión tiene firma local ad hoc y aún no está notarizada por
Apple. macOS puede impedir su primera apertura. La firma de actualización
Ed25519 valida las nuevas versiones dentro de Tokens; no sustituye la
notarización de Apple.

## Actualizaciones

Tokens comprueba nuevas versiones diariamente y también permite buscarlas desde
Configuración. Pide confirmación antes de instalar. Los instaladores y el
catálogo están firmados con Ed25519; SHA256SUMS permite comprobar las descargas.
No necesitas credenciales de GitHub para actualizar.

## Privacidad y código

Este repositorio contiene solo documentación y archivos de distribución.
El código fuente es privado. Las sesiones, claves y datos de las cuentas
conectadas no forman parte de los instaladores ni de este repositorio.
Tokens no envía mensajes a los modelos para consultar sus estadísticas.

Gemini requiere conectar la cuenta de Google dentro de Tokens y tener disponible
su página de límites. La conexión con cada proveedor se realiza en la app;
ninguna cuenta está preconfigurada en el instalador.

**Leo Mobel — leonardmobel@gmail.com**

© 2026 Cooler. Todos los derechos reservados.

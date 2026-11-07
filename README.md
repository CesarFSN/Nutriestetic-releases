# Nutriestetic para macOS

Descargas y actualizaciones de Nutriestetic. Este repositorio contiene únicamente información de distribución y archivos de los releases; el código fuente se mantiene privado.

[Descargar la versión más reciente](https://github.com/CesarFSN/Nutriestetic-releases/releases/latest)

## Requisitos

- macOS 27 o posterior.
- Mac con Apple Silicon (arm64).

## Instalación

Descarga el zip o el dmg del último release y copia Nutriestetic.app a Aplicaciones. La distribución tiene firma ad hoc y no está notarizada por Apple; consulta las indicaciones de primera apertura del release.

## Actualizaciones

Desde la versión 6.1.1, usa **Nutriestetic > Buscar actualizaciones…**. En **Ajustes > General** puedes activar la búsqueda automática. La descarga y la instalación requieren tu confirmación.

El catálogo `appcast.xml` y el zip del actualizador se firman con Ed25519. Los archivos `SHA256SUMS.txt` permiten comprobar la integridad de las descargas. La firma del updater es independiente de la firma ad hoc del bundle.

Las versiones anteriores a 6.1.1 necesitan una primera instalación manual para incorporar el actualizador.

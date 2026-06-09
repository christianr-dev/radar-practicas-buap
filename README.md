# Radar de Practicas BUAP

App web no oficial para organizar, comparar y compartir opciones de practicas profesionales y servicio social.

## Que hace

- Registra empresas y actividades disponibles.
- Guarda folio, dificultad, apoyo economico, numero de prestadores, duracion y ubicacion.
- Permite buscar, filtrar y ordenar opciones.
- Permite comparar ofertas seleccionadas.
- Exporta e importa datos en JSON.
- Genera un link compartible con los datos codificados en la URL.

## Como se guardan los datos

Los datos se guardan localmente en el navegador usando `localStorage`.

Esto significa que no se suben a ningun servidor y no se comparten automaticamente. Para respaldarlos o moverlos a otro navegador, usa el boton `Exportar`.

## Como compartir datos

1. Abre la app.
2. Importa o captura tus datos.
3. Presiona `Compartir link`.
4. Envia el enlace generado.

El enlace debe incluir `#data=` para que otra persona vea los datos.

## Aviso

Este proyecto no es oficial de la BUAP. Es una herramienta independiente creada para facilitar la organizacion personal de opciones de practicas y servicio social.

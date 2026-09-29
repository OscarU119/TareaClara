# Tarea Clara

Aplicación web progresiva (PWA) para organizar tareas desde computadora y teléfono. Permite agregar pendientes, asignar categoría y fecha opcional, completar, filtrar y eliminar. Guarda los datos en `localStorage` de cada navegador y almacena recursos básicos con un service worker para visitas posteriores sin conexión.

## Aplicación publicada

https://tarea-clara-oscar.rakzour119.chatgpt.site

La publicación actual solicita acceso con ChatGPT. El código de este repositorio es público.

## Ejecutar localmente

Los archivos de la aplicación están en la raíz de este repositorio. Sirve la carpeta con un servidor HTTP local, por ejemplo:

```sh
python -m http.server 8000
```

Abre `http://localhost:8000`. No requiere dependencias ni proceso de compilación. Para instalar la PWA en un equipo compatible, abre el sitio mediante HTTPS o localhost y usa la opción de instalación del navegador.

## Alcance

Las tareas se guardan sólo en el navegador actual; no hay cuentas ni sincronización entre dispositivos. La primera visita necesita conexión para almacenar los archivos usados sin conexión.

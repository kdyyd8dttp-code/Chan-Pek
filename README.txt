# CHAN PEK — Prototipo QR

Este prototipo tiene dos flujos:

1. QR DEL EMPAQUE → abre index.html → formulario de registro.
2. QR DE LA PLAQUITA → abre pet.html → perfil de la mascota.

IMPORTANTE:
- Para que un celular externo pueda escanear y abrir los QR, estos archivos deben estar publicados en internet.
- El prototipo actual guarda el registro en localStorage, por lo que sirve para demostrar el flujo en el mismo dispositivo.
- Para una versión real multiusuario se debe sustituir localStorage por una base de datos (por ejemplo Supabase/Firebase) y crear identificadores únicos para cada mascota.
- No se recomienda publicar la dirección exacta del dueño.

QR DEL EMPAQUE:
Registrar una mascota.

QR DE LA PLAQUITA:
Perfil de Kira / CHANPEK-0001.

Después de publicar la carpeta, hay que regenerar los QR usando las URLs públicas:
https://TU-DOMINIO/index.html
https://TU-DOMINIO/pet.html?id=CHANPEK-0001

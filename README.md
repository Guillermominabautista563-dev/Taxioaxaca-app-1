# Taxioaxaca-app-1# Taxi Oaxaca

App cliente + panel de control para Taxi Oaxaca.

## Funciones incluidas
- Botón de llamada directa al 424-541-2177
- Botón de WhatsApp con chat directo
- Formulario de reservación y cotización
- Envío de ubicación exacta con Google Maps
- Panel de control con PIN
- Estados de servicio
- PWA instalable en celular

## Cómo usar localmente
1. Instala Node.js 18 o superior.
2. Abre una terminal en esta carpeta.
3. Ejecuta:

```bash
npm install
npm start
```

4. Abre `http://localhost:3000`
5. Panel de control: `http://localhost:3000/admin`

## Variables opcionales
Puedes personalizar esto antes de publicar:

- `PORT=3000`
- `ADMIN_PIN=542177`
- `PHONE_E164=14245412177`
- `BRAND_NAME=Taxi Oaxaca`

### Ejemplo Linux/Mac
```bash
ADMIN_PIN=123456 PHONE_E164=14245412177 npm start
```

### Ejemplo Windows PowerShell
```powershell
$env:ADMIN_PIN='123456'; $env:PHONE_E164='14245412177'; npm start
```

## Recomendado para publicar
- Render
- Railway
- VPS con Node.js

## Notas importantes
- La app sí pide permiso de ubicación y genera un enlace exacto de Google Maps.
- El enlace queda guardado en tu panel de control.
- Además, el cliente puede abrir WhatsApp para mandarte ese link inmediatamente.
- Para que funcione como sitio real para clientes, publícala en HTTPS.

# RAV | Referee Analytics & Video

Descargá la última versión de RAV para tu computadora. Para usarla
necesitás una cuenta habilitada: si no tenés, pedísela al administrador.

## 1. Descargá el instalador

| Tu computadora | Descarga |
|---|---|
| **Mac con chip Apple** (M1, M2, M3, M4, M5…) | [RAV-mac-apple-silicon.dmg](https://github.com/valeferrero4/RAV-descargas/releases/latest/download/RAV-mac-apple-silicon.dmg) |
| **Mac con procesador Intel** | [RAV-mac-intel.dmg](https://github.com/valeferrero4/RAV-descargas/releases/latest/download/RAV-mac-intel.dmg) |
| **Windows** (10 u 11, 64 bits) | [RAV-windows-setup.exe](https://github.com/valeferrero4/RAV-descargas/releases/latest/download/RAV-windows-setup.exe) |

**¿Qué Mac tengo?** Menú  → **Acerca de esta Mac**. Si dice **Chip Apple M…**,
es la primera opción; si dice **Procesador Intel…**, la segunda.

## 2. Instalá VLC (una sola vez)

RAV usa VLC, un reproductor gratuito, para mostrar los videos.
Descargalo de [videolan.org](https://www.videolan.org/vlc/):

- **Mac:** elegí la versión de tu tipo de Mac y arrastrá VLC a **Aplicaciones**.
- **Windows:** la versión de **64 bits**.

## 3. Instalá RAV

### Mac

1. Abrí el `.dmg` y arrastrá **RAV** a **Aplicaciones**.
2. Abrí RAV desde **Aplicaciones**.
3. **La primera vez, macOS la bloquea** porque no viene de la App Store.
   Es normal y se hace **una sola vez**:

   **Si dice "No se abrió RAV"** (o *"Apple no pudo verificar…"*):
   1. Tocá **Listo**. ⚠️ **No** toques "Mover al basurero".
   2. Abrí **Ajustes del Sistema** ( → Ajustes del Sistema).
   3. Entrá a **Privacidad y seguridad**.
   4. Bajá hasta el final: aparece *"Se bloqueó el uso de RAV…"*.
      Tocá **Abrir igualmente**.
   5. Poné la contraseña de tu Mac (o tu huella) y tocá **Abrir igualmente**
      otra vez.

   Listo: desde ahora RAV abre normal.

   **Si en cambio dice que RAV "está dañada"**: abrí la aplicación
   **Terminal** (buscala con Cmd + Espacio), pegá esto y apretá Enter:

   ```
   xattr -dr com.apple.quarantine /Applications/RAV.app
   ```

   Después abrí RAV normalmente.
4. Si macOS te pide permiso para leer **Descargas** o **Documentos**
   (donde tengas los videos), decile que sí.

Cada vez que instales una versión nueva puede volver a pedírtelo:
se resuelve igual.

### Windows

1. Hacé doble click en `RAV-windows-setup.exe`.
2. Si aparece **"Windows protegió su PC"**: **Más información** →
   **Ejecutar de todas formas**.
3. Seguí los pasos del instalador. RAV queda en el menú Inicio y, si lo
   elegís, en el Escritorio.

## 4. Ingresá con tu cuenta

La primera vez que abrís RAV te pide el email y la contraseña que te dio
el administrador. Después entra solo.

- Sin internet podés seguir usándolo hasta **7 días**.
- Cada cuenta se puede usar en hasta **2 computadoras**. Si cambiás de
  computadora, pedile al administrador que libere la anterior.

## Actualizar

Descargá de nuevo el instalador de esta página e instalalo encima. Tus
proyectos y paneles no se borran.

## Versiones anteriores

Todas las versiones están en [Releases](https://github.com/valeferrero4/RAV-descargas/releases).

# TryGo — apps de Android y accesos web

**TryGo** es la plataforma de logística de **Bemians** (Perú). Tiene dos apps:

| App | Para quién | Qué hace |
| --- | --- | --- |
| **TryGo Business** | Empresas y su personal | Paquetería, envíos entre sedes, reparto con ruta y PIN de entrega, equipo y permisos, cobros y facturación. |
| **TryGo** | Personas | Envíos enviados y recibidos, seguimiento y comprobantes. |

> Este repositorio publica **solo los instaladores y la información pública** de TryGo. El código fuente no es público.

## Usar TryGo en la web (sin instalar nada)

| App | Entrar | Crear cuenta |
| --- | --- | --- |
| TryGo Business (empresas) | <https://trygo.bemians.com/#/login> | <https://trygo.bemians.com/#/register> |
| TryGo (personas) | <https://customer.bemians.com/#/login> | <https://customer.bemians.com/#/register> |

Portadas: <https://trygo.bemians.com> y <https://customer.bemians.com>.

## Descargar las apps de Android

| App | Versión | Descarga oficial | GitHub |
| --- | --- | --- | --- |
| **TryGo Business** | 1.0.14 | [trygo-business.apk](https://api.bemians.com/descargas/trygo-business.apk) | [Release 1.0.14](https://github.com/xDarcyLove/Try-Go/releases/tag/business-v1.0.14) |
| **TryGo** | 1.0.6 | [trygo.apk](https://api.bemians.com/descargas/trygo.apk) | [Release 1.0.6](https://github.com/xDarcyLove/Try-Go/releases/tag/clientes-v1.0.6) |

- La **descarga oficial** siempre entrega la versión más reciente (el enlace no cambia).
- En **[Releases](https://github.com/xDarcyLove/Try-Go/releases)** están las versiones publicadas, con sus notas y su huella SHA-256.
- Requisito: **Android 7.0 o superior**.
- TryGo Business **1.0.12 es la versión mínima**: las anteriores ya no se conectan y la app pide actualizar.

## Instalar o actualizar

1. Descarga el archivo `.apk` desde la descarga oficial o desde Releases.
2. Ábrelo. Si Android lo pide, permite **«Instalar apps desconocidas»** para tu navegador o tu gestor de archivos.
3. Para **actualizar**, instala la versión nueva encima de la anterior: no hace falta desinstalar y no se pierden datos.
4. Si la app muestra **«Actualiza TryGo Business»** (o «Actualiza TryGo»), toca «Actualizar ahora» o descarga la versión
   más reciente desde aquí.

Las dos apps se pueden tener instaladas a la vez en el mismo teléfono.

## Verificar la descarga

Compara la huella **SHA-256** del archivo con la publicada en su Release:

| Archivo | SHA-256 |
| --- | --- |
| `TryGo-Business-1.0.14.apk` | `398aedddb6cff8ce1788fb7130a512409333ca57775a0b3417a177a769a9a66f` |
| `TryGo-1.0.6.apk` | `a89b38c99b7c8c90d0b0b47f583b2a9853cf7c112df6aca59fb98a0b23baf620` |

- Windows (PowerShell): `Get-FileHash .\TryGo-Business-1.0.14.apk -Algorithm SHA256`
- macOS: `shasum -a 256 TryGo-Business-1.0.14.apk` · Linux: `sha256sum TryGo-Business-1.0.14.apk`

Las dos apps están firmadas con el mismo certificado. Huella SHA-256 del certificado:
`23:93:03:99:48:A2:54:D5:03:5B:1D:31:23:A0:60:32:85:7F:2F:5C:A7:BC:E0:17:82:87:8D:4D:C9:E1:B0:0E`

## Legal

| | TryGo Business | TryGo |
| --- | --- | --- |
| Términos y condiciones | <https://trygo.bemians.com/#/terms> | <https://customer.bemians.com/#/terms> |
| Política de privacidad | <https://trygo.bemians.com/#/privacidad> | <https://customer.bemians.com/#/privacidad> |
| Política de cookies | <https://trygo.bemians.com/#/cookies> | <https://customer.bemians.com/#/cookies> |

## Contacto

<contact@bemians.com> · <https://trygo.bemians.com>

---

© 2026 Bemians. Todos los derechos reservados. Los instaladores se publican para su uso con los servicios de TryGo.

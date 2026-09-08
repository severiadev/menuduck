# Instalar MenuDuck

[MenuDuck](../README.es.md) · [English](ALPHA_GUIDE.md) · [Русский](ALPHA_GUIDE.ru.md) · Español · [简体中文](ALPHA_GUIDE.zh-Hans.md)

Requiere **macOS 26+**. Es una alfa sin firma Developer ID ni notarización de Apple. Haz una copia de seguridad e instálala solo si confías en su origen.

## Instalación

1. Descarga el `.dmg` de **Assets** en [Releases](https://github.com/severiadev/menuduck/releases), no el archivo **Source code**. Lee las limitaciones de esa versión.
2. Verifica SHA-256: escribe `shasum -a 256 ` en Terminal, arrastra el DMG a la ventana y pulsa Intro. Compara el resultado completo con la suma recibida por tu contacto privado de pruebas.
3. Abre el DMG, arrastra MenuDuck a **Aplicaciones** y expulsa la imagen de disco.
4. Abre MenuDuck. Si macOS no puede verificar al desarrollador, ve a **Ajustes del Sistema → Privacidad y seguridad → Abrir igualmente** y confirma la apertura.

**Detente si la suma no coincide, macOS detecta software malicioso o daños, o no aparece Abrir igualmente.** Contacta con el organizador; no desactives Gatekeeper ni eludas las restricciones del Mac. [Instrucciones de Apple](https://support.apple.com/es-es/102445).

## Primer uso

- En los ajustes, pulsa **Enter License Key** e introduce tu clave de pruebas. No la publiques.
- Pulsa **Update Catalog**, autoriza la solicitud de red e instala **Stay Awake** o **Network Speed**.
- Para plugins **Planned**, **I Need It** registra tu voto; **Voted** lo confirma y **Remove Vote** lo retira.

<details>
<summary>Pruebas, actualizaciones y solución de problemas</summary>

Prueba los iconos, atajos, ajustes de pantalla y ambos plugins. Cambia un ajuste cada vez; reinicia la app para comprobar que se guarda. En el modo de fondo **All (Experimental)**, ocultar la muesca requiere la apariencia **Dark**.

Las actualizaciones son manuales: cierra MenuDuck y sigue las instrucciones de la nueva versión. No instales versiones anteriores sin consultar.

Si algo falla, deshaz el último cambio o cierra la app. Cerrarla puede no restaurar todos los cambios de pantalla. **No borres preferencias, archivos de fondos ni datos de recuperación.** Indica las versiones de la app/macOS y cómo reproducir el fallo; elimina los datos personales del informe.

</details>

[Informar de un error](https://github.com/severiadev/menuduck/issues/new/choose) · [Ayuda privada](../SUPPORT.md) · [Privacidad](../PRIVACY.md)

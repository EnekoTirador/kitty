# 🐈 My Kitty Configuration

Mi configuración personal para **Kitty Terminal**, optimizada para el desarrollo diario utilizando **Zsh** y el esquema de colores **Catppuccin Mocha** con un fondo negro puro para mejorar el contraste.

## ✨ Características

*   **Paleta de colores:** Catppuccin Mocha modificado (`#000000` de fondo para un look OLED/Pure Black).
*   **Tipografía:** JetBrainsMono Nerd Font (Tamaño 12.0) ideal para iconos y desarrollo.
*   **Diseño Limpio:** Sin decoraciones de ventana (borderless), pestañas estilo *Powerline* en la parte inferior y opacidad ligera (0.92).
*   **Shell por defecto:** Zsh.

## 🚀 Instalación

1. Asegúrate de tener instalada la tipografía [JetBrainsMono Nerd Font](https://github.com).
2. Clona este repositorio o copia el archivo de configuración.
3. Coloca el archivo `kitty.conf` en tu directorio de configuración:

```bash
# Crea el directorio si no existe
mkdir -p ~/.config/kitty

# Copia la configuración (ejemplo si clonaste el repo)
cp kitty.conf ~/.config/kitty/kitty.conf
```

4. Reinicia Kitty o recarga la configuración presionando `ctrl+shift+f5`.

## 🛠️ Vista previa de la Configuración

El archivo `kitty.conf` incluye principalmente:

*   **Opacidad:** `0.92` (Transparencia sutil).
*   **Relleno:** `window_padding_width 10` para que el texto no pegue a los bordes de la pantalla.
*   **Cierre seguro:** Desactivada la confirmación de cierre (`confirm_os_window_close 0`).


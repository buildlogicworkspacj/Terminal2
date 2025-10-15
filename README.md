# Terminal2

> Un "CMD" personalizado con extras — editor de texto — hecho por diversión.



Descripción
-----------
Terminal2 es un proyecto pequeño y experimental que emula una consola (cmd) con funcionalidades añadidas:
- Mini IDE integrado para editar código.
- Capacidad de crear y escribir archivos directamente desde la interfaz.
- Diseñado como proyecto personal y educativo — "only for fun".

Información técnica
-------------------
- Lenguaje: C++ (proyecto pensado para compilar con MinGW en Windows).
- Archivos principales mencionados por el autor: `wms.h`, `ui.cpp`.

Descripción de los archivos
---------------------------
- ui.cpp: <b> Pensado para lo principal y otras cosas </b>
- wms.h: <b> <font color="#FF0000">PROXIMAMENTE</font> </b>

Requisitos
---------
- MinGW (g++) instalado y en la variable de entorno `PATH`.
- Windows (probado con MinGW/MinGW-w64).
- Opcional: un editor de texto para modificar fuentes.

Compilación (MinGW)
-------------------
Abre PowerShell en la carpeta src y ejecuta:

```powershell
g++ ui.cpp wms.h -o Terminal2
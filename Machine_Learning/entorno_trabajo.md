# Preparando el entorno de trabajo
Alfredo Aburto
2024-01-22

## Objetivo

Crear un entorno de trabajo funcional que permita documentar y ejecutar los
códigos que se desarrollen a lo largo del aprendizaje.

## Entorno Offline: Anaconda

### Instalación en Linux

La instalación de Anaconda en Linux es un proceso sencillo que te permite gestionar entornos virtuales y paquetes de manera eficiente. Aquí hay una guía paso a paso para instalar Anaconda en un sistema Linux:

1. **Descargar Anaconda:**
   Visita el sitio web de Anaconda (https://www.anaconda.com/products/distribution) y descarga la versión adecuada para Linux.

2. **Abrir una terminal:**
   Abre una terminal en tu sistema. Puedes hacerlo desde el menú de aplicaciones o utilizando el atajo de teclado `Ctrl + Alt + T`.

3. **Navegar al directorio de descargas:**
   Usa el comando `cd` para cambiar al directorio donde descargaste el instalador de Anaconda. Por ejemplo:

   ```bash
   cd ruta/del/directorio/descargas
   ```

4. **Dar permisos de ejecución:**
   Asegúrate de que el instalador tenga permisos de ejecución con el siguiente comando:

   ```bash
   chmod +x nombre_del_instalador.sh
   ```

   Reemplaza `nombre_del_instalador.sh` con el nombre real del archivo de instalación.

5. **Ejecutar el instalador:**
   Ejecuta el instalador de Anaconda con el siguiente comando:

   ```bash
   ./nombre_del_instalador.sh
   ```

   Sigue las instrucciones en pantalla para completar la instalación. Puedes presionar `Enter` para aceptar las configuraciones predeterminadas.

6. **Cargar cambios en la terminal:**
   Después de la instalación, puedes necesitar cargar los cambios en la terminal. Esto se hace cerrando y volviendo a abrir la terminal o ejecutando el siguiente comando:

   ```bash
   source ~/.bashrc
   ```

7. **Activar el entorno base:**
   Puedes activar el entorno base de Anaconda con el siguiente comando:

   ```bash
   conda activate base
   ```

   Si estás usando una versión anterior a la 4.4, puedes usar `source activate base` en su lugar.

8. **Listo para usar:**
   Ahora, el entorno de Anaconda está instalado y listo para su uso. Puedes verificar la instalación con el comando:

   ```bash
   conda info
   ```

   Esto mostrará información sobre tu instalación de Anaconda.

Con estos pasos, has instalado con éxito Anaconda en tu sistema Linux, y ahora estás listo para trabajar en entornos virtuales y gestionar paquetes de manera eficiente.
```

Recuerda que este es un ejemplo y puedes ajustarlo según tus necesidades. Además, ten en cuenta que puede haber cambios en los comandos según la versión específica de Anaconda o la distribución de Linux que estés utilizando.

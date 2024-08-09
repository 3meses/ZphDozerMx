# ZphDozerMx

ZphDozerMx es una herramienta de phishing actualizada en 2024, de momento solo cuenta con soporte para Facebook, pero en el futuro traerá más variedad. Se trata de una herramienta de clonación de páginas web, en este caso, de Facebook. Esta es su primera versión, y pronto seguirán mejoras y actualizaciones más avanzadas.

## Instalación

Sigue los pasos a continuación para instalar y configurar ZphDozerMx en Termux.

### Requisitos

Asegúrate de tener Termux instalado en tu dispositivo Android.

### Pasos de instalación

1. Aquí tienes los comandos de instalación:

1. **Actualizar paquetes y herramientas de Termux**:

   ```bash
   pkg update -y && pkg upgrade -y
   ```
2. **Instalar Git*
   ```bash
   pkg install git -y
   ```

4. **Instalar Python**:

   ```bash
   pkg install python -y
   ```

5. **Instalar OpenSSH** (para utilizar Serveo):

   ```bash
   pkg install openssh -y
   ```

6. **Clonar el repositorio desde GitHub**:

   ```bash
   git clone https://github.com/3meses/ZphDozerMx.git
   ```

7. **Cambiar al directorio del proyecto**:

   ```bash
   cd ZphDozerMx
   ```

8. **Instalar las dependencias de Python**:

   ```bash
   pip install -r requirements.txt
   ```

9. **Ejecutar el script**:

   ```bash
   python zphdozer.py
   ```

10. **Seleccionar la opción 1 en la terminal** para elegir el login de Facebook.

# Clase 11
## Pasos a realizar

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio:
    ```
    mkdir python-final
    ```

3. Entramos en ella: 
    ```
    cd python-final
    ```

4. Iniciamos el repositorio:
    ```
    git init
    ```

5. Creamos un archivo:
    ```
    touch finales.py
    ```

6. Abrimos VSC:
    ```
    code .
    ```

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
    ```
    python -V
    python3 -V
    ```

8. Creamos el entorno virtual en Python:
    ```
    python3 -m venv venv #Creamos el entorno virtual
    ```

9. Activamos el entorno virtual:
    ```
    source venv/bin/activate #Activamos el entorno virtual en Linux

    venv/scripts/activate #En windows
    ```

10. Hacemos actualización del pip de Python
    ```
    python3 -m pip install --upgrade pip #Actualizamos el pip
    ```

11. Investigar ¿Qué es el pip y porque lo actualizamos?
  
    ### ¿Qué es pip?

      "Pip" es un gestor de paquetes para Python, que permite instalar, actualizar y desinstalar paquetes y bibliotecas de software de Python desde el Python Package Index (PyPI) y otros índices de paquetes. Su nombre es un acrónimo recursivo que significa "Pip Installs Packages".

    ### ¿Por qué se actualiza pip?

      - Mejoras de Seguridad: Las actualizaciones pueden incluir parches para vulnerabilidades de seguridad descubiertas.
      - Nuevas Funcionalidades: Con cada nueva versión, pip puede incorporar nuevas funcionalidades y mejoras en el manejo de paquetes.
      - Corrección de Errores: Las versiones más recientes a menudo corrigen errores presentes en versiones anteriores.
      - Compatibilidad: A medida que Python y los paquetes evolucionan, pip se actualiza para asegurar compatibilidad con las nuevas versiones de Python y otros paquetes.
      - Rendimiento: Las actualizaciones pueden incluir optimizaciones que mejoren la velocidad y eficiencia de pip.

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
# Entrega Taller 2
## Guía para desploegar 
1. **Clonar el repositorio en local**
   ```console
   git clone git@github.com:danielj4mv/taller_2.git
   ```
2. **Desde la carpeta en la que se encuentra el `docker-compose.yaml` Compilar la aplicación de docker**
   ```docker
   docker compose build
   ```
3. **Crear el contenedor de docker**
   ```docker
   docker compose up
   ```
4. **Una vez se ha terminado de ejecutar el comando anterior, en las últimas líneas se muestra como acceder a la interfaz de jupyterlab expuesta en el puerto 8888. Acceder a cualquiera de los elaces proporcionados desde el navegador**
5. **Una vez dentro, desde la interfaz de jupyterlab se pide un token de acceso el cual fue proporcionado junto al enlace. Copiar y pegar este token en el espacio requerido para acceder**
6. **Con todo esto listo, se puede trabajar con los notebooks dentro de este repositorio. En caso de querer descargar nuevamente dichos notebooks, desde una terminal pueden ser descargados con el comando wget y el enlace a dicho notebook**
   ```console
   wget https://raw.githubusercontent.com/CristianDiazAlvarez/MLOPS_PUJ/main/Niveles/1/Validacion_de_datos/TF/TFDV.ipynb
   ```
   ```console
   wget https://raw.githubusercontent.com/CristianDiazAlvarez/MLOPS_PUJ/main/Niveles/1/Transformacion_de_datos/ML_Metadata.ipynb
   ```

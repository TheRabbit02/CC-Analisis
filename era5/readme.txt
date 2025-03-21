Solicitud de datos a ERA5 atravez de python


Intalacion y key:

Crear un archivo ".cdsapirc" como el ejemplo que se encuentra en esta carpeta, la key la encuentras en https://cds.climate.copernicus.eu/profile
Una copia va en la carpeta donde vas a ejecutar las solicitudes y otra copia va en C:/Users/%USERPROFILE%/

Teniendo ambos archivos listos toca instalar la libreria, en un terminal ejecutar
pip3 install cdsapi

Si todo sale bien ya esta listo para hacer solicitudes

Solicitud.ipynb es un codigo que genera 21 solicitudes para los años entre 1961 y 2024, para todos los dias de todos los meses a las 18:00 utc para la region contenida en [-32, -71.75, -34, -70] para las presiones entre 1000 y 850 hpa en formato "netcdf" en grupos de 3 años (lo que permitia el limite

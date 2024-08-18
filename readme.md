# wps-office en español
Este repositorio contiene los archivos necesarios para tener el wps-office en espanol con su diccionarios (distros basados en debian).

0. clone el repositorio 
```bash
git clone https://github.com/EDISC255/wps-espanol.git
```

1. instalar el paquete wps-office_11.1.0.8865_amd64.deb

```bash
sudo dpkg -i wps-office_11.1.0.8865_amd64.deb
```

2. instalar el paquete wps-full-fix-es_1.0-2019_all.deb

```bash
sudo dpkg -i wps-full-fix-es_1.0-2019_all.deb
```

3. cambiar la configuracion de idioma

    1. ejecute el programa wps y dirijase a la opcion de cambiar idioma.

        ![pantalla_prinsipal.png](./screenshots/pantalla_prinsipal.png) 

    2. cambie el idioma del programa

        ![pantalla_cambio_idioma.png](./screenshots/pantalla_cambio_idioma.png)


4. descargar e instalar la ultima version de wps-office

[wps office actualizado](https://es.wps.com/download/ )

5. abra y verifique que se halla camiado correctamete el idioma.

### nota

al abrir el programa le va aparecer un error de fuentes. para solucionar el error tiene que instalar el paquete ttf


```bash
sudo dpkg -i ttf-wps-fonts_1.0_all.deb
```

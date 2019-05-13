refindbooting
=============

Establece rEFInd como primera opción de arranque y ubuntu como segunda   
      
   
Instalación
-----------

La forma más sencilla de instalarlo es ejecutar los siguientes comandos:

   wget --no-check-certificate -O /usr/local/sbin/refindbooting https://raw.githubusercontent.com/algodelinux/refindbooting/master/refindbooting  
   chmod 755 /usr/local/sbin/refindbooting  
   
   
Uso
---

* El script se ejecuta automáticamente en cada apagado o reinicio desde /lib/systemd/system/refind.service   
* En cualquier caso, es posible ejecutarlo manualmente  
   
Sintaxis
--------

```bash
refindbooting
```
   
   
Ejemplos
--------

```bash
# refindbooting
```
   
   
Authors
-------

Esteban M. Navas <algodelinux@gmail.com>   
Fecha creación:      21/05/2018   
Última modificación: 13/05/2019   

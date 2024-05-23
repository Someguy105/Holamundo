Nombre: Jimmy Ayala                                                Fecha: 20 de mayo de 2024

Paralelo B

 #                             Caso de Ciberataque Shamoon

Alrededor del año 2012 ocurrió un incidente, donde se utilizó un malware de borrado de datos  
(un tipo de software malicioso con fines de borrar información sensible), en contra de una  
compañía de Arabia Saudita, llamada Saudi Aramco, que se dedica a la explotación y  
exportación de petróleos. Este malware atacó en un par de horas a 35.000 computadoras, donde  
se robaron las contraseñas y borraron los datos de dichas computadoras que, en consecuencia,  
dejaron de operar. Sin embargo, antes de borrar todos los documentos incluyeron imágenes de la  
bandera americana quemándose. Los responsables de este ciberataque fueron realizados por un  
grupo con el alias de: “Cutting Sword of Justice”. Hasta el día de hoy no se conocen los  
responsables detrás de este ataque. Aun así, se especula que fue algún grupo hacker de Irán. Este  
malware se compone de un “Dropper module” dentro de un documento y este módulo crea un  
servicio, llamado, “NtsSrv”, que sirve para descargar, instalar, borrar y reportar componentes.  
También tiene otra propiedad de esparcirse dentro de una red y robar credenciales. Cuando está  
instalado, el malware descarga un diver con el nombre: “Eldos” para su funcionamiento. Luego,  
el módulo de reportar se conecta al “command and control” (servidor), donde el programa  
coordina qué tipo de archivos se elimina y una fecha con hora para ejecutar el malware. Por  
último, se sobrescribe y elimina los contenidos del “Master Boot Record” (disco duro). 

**Referencias**

Pagliery, J. (2015, Agostot 5). _The inside story of the biggest hack in history_. CNNMoney.  
        https://money.cnn.com/2015/08/05/technology/aramco-hack/

Perlroth, N. (2012, Octubrer 24). Cyberattack on Saudi oil firm disquiets U.S. _The New York  
        Times_.  
        https://www.nytimes.com/2012/10/24/business/global/cyberattack-on-saudi-oil-firm-dis
        quiets-us.html

_Shamoon Wiper Trojan - NHS England Digital_. (2019, Enero 3). NHS England Digital.  
        https://digital.nhs.uk/cyber-alerts/2018/cc-2844

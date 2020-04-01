# LinuxCnCam
Generador de Trayectorias cnc mediante Codigos G
----------------------------------------------------------------------------------------------------------------------------

Proyecto                     >  LinuxCnCam
Descripción                >  Generador de trayectoria cnc para Linuxcnc mediante código iso.
Fecha de inicio           >  1-6-2019
Idioma                         >  Español
Fundador                    >  Nestor Eduardo Gonzalez cncrobotmatic@gmail.com
Pais Origen                >  Argentina

----------------------------------------------------------------------------------------------------------------------------



-------------------------------------------------------README--------------------------------------------------------

LinuxCnCam es un proyecto que en su fase inicial pretende ser una biblioteca de rutinas iso de códigos G con la utilidad de poder generar trabajos típicos de mecanizado para máquinas de ejes cartesianos como tornos , fresadoras y routers de 2, 3 y 4 ejes, que sean accionados mediante el software LinuxCNC.

El motivo de que exista un proyecto como LinuxCnCam es rescatar y mantener una tecnologia de trabajo para máquinas CNC muy utilizadas en las épocas previas a los sistemas Cad/Cam gráficos.

Resulta que como profesional del área y educador, sigo encontrando la problemática de resistencia a adquirir tecnología CNC en las pequeñas empresas ya que consideran a dicha tecnología muy difícil de utilizar.

En el tiempo presente, si usted nunca trabajo con un sistema cnc, necesita integrar un grupo de 
aplicaciones para poder realizar cierto tipos de trabajos que son típicos en el área de mecanizado por arranque de viruta.

LinuxCnCam pretende darle una solución simple, mediante el uso de programación [iso-paramétrica], con la idea de cargar variables al inicio de un programa para poder realizar tareas de mecanizado definidos en cada una de las rutinas presentadas en el proyecto.
Cajeras, agujeros de posición circular, aplanados, etc, son solo algunas de las tareas básicas que vamos a facilitar.  .

LinuxCnCam espera recibir colaboración de toda la comunidad que conoce este tipo de codificación para poder rápidamente tener una gran cantidad de empaquetados que puedan hacer que iniciar y trabajar en máquinas de control numérico sea sencillo.


Proyectamos al final tener una interface gráfica que integre en un único shell de usuario todas las rutinas de manera que podamos incorporarlo como solapa en la aplicación LinuxCNC con el fin de que se encuentre disponibles al ingresar a LINUXCNC.

Algunos sistemas como FANUC o SIEMENS incorporan el concepto de conversacional, donde ocultan toda la complejidad del código para que el usuario no tenga que lidiar con el. LinuxCnCam pretende ser en un futuro el sistema conversacional de LinuxCnC.

LinuxCnCam desarrollara sus rutinas como programas a código visible [.ngc] nativos para LinuxCNC, lo que permitirá a los usuarios principiantes poder descargar los archivos de programas y ejecutarlos directamente.
A los usuarios expertos, les permitirá  mejorar y optimizar los códigos o adicionar código para potenciar los algoritmos.

LinuxCnCam mantendrá una bitácora por rutina, donde se podrán ver las modificaciones en el tiempo y los avances obtenidos en las rutinas.

Esperamos que con este proyecto, estimulemos el uso de tecnología cnc en las pequeñas empresas que en todo el mundo siguen temerosos de adquirirla.

Este proyecto surge en Argentina como parte de un desarrollo electrónico que utiliza LinuxCNC como aplicación principal que se denomina ROBOTMATIC CNC. (http://www.robotmatic.net) (facebook/robotmatic cnc)

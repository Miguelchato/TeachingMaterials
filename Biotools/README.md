# Biotools in biostatistics and bioinformatics

Repository with the material corresponding to the course __Biotools in biostatistics and bioinformatics__ given at 
[ISGlobal](http://www.isglobal.org) (former CREAL). Each folder contains slides, R code, data and exercises of each topic.


## License
 
Unless otherwise stated, all material is licensed under a
[Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/).
This means you are free to copy, distribute and transmit the work,
adapt it to your needs as long as you cite its origin and, if you do
redistribute it, do so under the same license.

# Introducci�n y Objetivos
El curso es una respuesta a la necesidad de investigadores en bioestad�stica y bioinform�tica de aprender a manejar herramientas b�sicas para ser profesionales y eficientes a la hora de programar, crear y distribuir sus trabajos creados, b�sicamente, en R. El cuso est� dise�ado para investigadores que utilizan R en su trabajo diario y quieren: 

> * Aprender a programar de forma eficiente nuevos m�todos estad�sticos y bioinform�ticos y crear librer�as optimizadas. 
> * Aprender a documentar librer�as mediante m�todos que garanticen la investigaci�n reproducible (Knitr, Markdown).
> * Saber c�mo implementar dichas librer�as de forma colaborativa usando herramientas que permiten el control de versiones (GitHub).
> * Aprender a crear interfaces gr�ficas (GUIs) mediante Shiny para extender el uso de los m�todos implementados a usuarios no familiarizados con R, o en general programas que requieren escribir comandos. Por ejemplo, grupos que no disponen de programadores, bioinform�ticos y/o bioestad�sticos.
> * Saber c�mo publicar sus librer�as en repositorios p�blicos como CRAN y/o Biooconductor (tambi�n GitHub) que garanticen la m�xima disponibilidad de sus m�todos por otros grupos

# Dirigido a
Estudiantes, profesores e investigadores con conocimientos b�sicos de programaci�n, que deseen utilizar este entorno para crear librer�as que implementen m�todos nuevos que hayan desarrollado o flujos de trabajos (pipelines) que permitan analizar sus datos mediante otras librer�as o funciones ya existentes. 

Para obtener un mejor provecho del curso, es necesario tener cierta experiencia escribiendo funciones, aunque sean sencillas. Los participantes aprender�n en profundidad las t�cnicas de programaci�n que est�n disponibles para R, as� como crear sus propias librer�as para ser enviadas a repositorios como CRAN o Bioconductor. El curso pretende mejorar tanto la estrategia como la programaci�n de funciones de forma que el desarrollo de nuevos m�todos estad�sticos puedan ser utilizados por el mayor n�mero de usuarios de forma sencilla y eficaz. 

# Metodolog�a del curso
Las sesiones ser�n de 2 horas. La primera media hora servir� para introducir a los participantes en un tema concreto. La siguiente media hora consistir� en un ejemplo basado en un problema real que servir� para ilustrar el tema tratado. La siguiente hora consistir� en un ejercicio que los participantes deber�n resolver y que ser� comentado y resuelto tras su finalizaci�n. Los participantes dispondr�n de las diapositivas del curso y el c�digo utilizado tanto en la presentaci�n como para resolver los ejercicios resueltos. 

# Fechas y horario
Las fechas del curso ser�n el 16, 17 y 18 de Mayo y se realizar� en el Instituto de Salud Global Barcelona, ISGlobal - Campus Mar ( www.isglobal.org ) [antiguo CREAL - www.creal.cat] situado en el Parque de Investigaci�n Biom�dica de Barcelona  (www.prbb.org ). El n�mero de plazas para el curso est� limitado a 20 y las plazas se han adjudicado ESTRICTAMENTE por orden de llegada de pre-inscripci�n, enviando un e-mail a  gemma.punyet@isglobal.org y posteriormente rellenando el [formulario de pre-inscripci�n]( https://docs.google.com/forms/d/e/1FAIpQLSeY0v5l7gbze0CEBlR5gx33A69dyk7uNk4KJZxcE8DtXje-Gw/viewform?usp=sf_link) 

El horario del curso es el siguiente:
Ma�anas: de 9:00 a 13:30h / Tardes: de 15:00 a 18:00h

# Temario
**D�a 1: Programaci�n en R, creaci�n de librer�as y creaci�n de documentos con Rmarkdown.**

Parte I - Programaci�n en R  (2 horas)
- Creaci�n de nuevas funciones
- C�mo organizar una funci�n 
- Nombres de argumentos y valores por defecto
- Control de los argumentos
- Uso de 'formula'   

Parte II - M�todos y clases en R (2 horas)
- Programaci�n orientada a objetos
- Creaci�n de M�todos
- Creaci�n de Clases

Parte III - Creaci�n de una librer�a (1 horas)
- Estructura b�sica

Parte IV - Investigaci�n reproducible (2 horas)
- Creaci�n de documentaci�n
- Knitr
- Markdown
- Env�o a CRAN o Bioconductor.

**D�a 2: Creaci�n de interfaces gr�ficas con Shiny**

Parte I  
-  Introducci�n: instalaci�n de Shiny y primeros ejemplos (1 horas)

Parte II 
- Dise�o del formulario de la aplicaci�n: disposici�n de los elementos (Secci�n UI) (1'5 horas)

Parte III 
- L�gica de Shiny: c�mo funciona (Secci�n Server). (1'5 horas)

Parte IV  
- C�mo mejorar el aspecto y la funcionalidad de la aplicaci�n mediante paquetes complementarios a Shiny: shinyBS, shinythemes, shinyjs. (1 hora)

Parte V 
-  Pr�ctica: creaci�n de una aplicaci�n. (2 horas)

**Dia 3: Manejo de repositorios**

Parte I - Github B�sico
- �Qu� es un sistema de control de versiones?
- GitHub - Presentaci�n
- Creaci�n de una cuenta en GitHub y del primer repositorio
- Interfaz GitHub desktop y/o GitKraken

Parte II - GitHub Avanzado
- Comandos b�sicos (status, add, rm, commit y push)
- Comandos avanzados (stash, rollback)
- Creaci�n de ramas (branches)


# Material y Requisitos
Los alumnos deber�n traer sus propios port�tiles. Dicha aula tendr� acceso WiFi a Internet y los alumnos dispondr�n de acceso previo a todo el material del curso que incluye las librer�as, el c�digo R y los datos necesarios para seguir las clases y realizar los ejercicios. 

El curso utilizar� dos herramientas principales: Rstudio y Github. Todos los participantes deber�n tener instalado una semana antes del curso la version de Rstudio 1.0.136 ( https://www.rstudio.com/ ) y la interfaz de Github desktop (Windows: https://desktop.github.com/, Linux: https://www.gitkraken.com/ ) . No hace falta tener una cuenta en Github porque aprenderemos a crearla en el curso (si ya la tiene no hay problema). Durante esa semana anterior al curso, se enviar� unas instrucciones para que todos los alumnos tengan una misma configuraci�n y puedan seguir las clases de forma eficiente. 


# Profesorado
Juan R Gonz�lez, Responsable del Grupo de Investigaci�n en Bioinform�tica en Epidemiolog�a Gen�tica (BRGE) del Instituto de Salud Global Barcelona (ISGlobal) y Profesor Asociado al Departamento de Matem�ticas de la Universidad Aut�noma de Barcelona (UAB).

Isaac Subirana, T�cnico Investigador en el Grupo REGICOR (IMIM-Parc de Salut Mar) y Profesor Asociado en el Departamento de Estad�stica de la Facultad de Biolog�a de la Universidad de Barcelona (UB).

Carles Hern�ndez-Ferrer, Investigador pre-doctoral del BRGE del Instituto de Salud Global Barcelona (ISGlobal).

# Coste del curso y forma de pago
El coste del curso es de 340 euros que incluye el desayuno que se realizar� a mitad de la ma�ana as� como todo el material del curso en soporte electr�nico (funciones, librer�as y ejercicios resueltos) las diapositivas y material bibliogr�fico presentado en las clases.  El n�mero de alumnos ser� de un m�ximo de 20. Los socios del [Barcelona Bioinformatics (BIB)](http://www.bioinformaticsbarcelona.eu/) tendr�n un descuento del 10% pero s�lo a los dos primeros miembros que lo soliciten. El resto si quieren asistir al curso deber�n abonar el coste total.

Una vez confirmada la inscripci�n al curso, se deber� realizar el pago a  trav�s de transferencia bancaria, al n�mero de cuenta CAIXABANK, S.A numero ES79 2100 0801 1102 0052 1586. Una vez realizado el ingreso el alumno tendr� que enviar el comprobante de la transferencia a gemma.punyet@isglobal.org 


# Acceso al Campus Mar - ISGlobal (PRBB) 
El Instituto de Salud Global Barcelona (ISGlobal) se encuentra en el Parque de Investigaci�n Biom�dica de Barcelona (PRBB) situado en la calle Doctor Aiguader, 88 de Barcelona, en la primera planta del PRBB, delante del Paseo Mar�timo de Barcelona, entre el Hospital del Mar y el Hotel Arts de la Villa Ol�mpica. 

 ![PRBB localization](figures/prbb_loc.png)


Se puede llegar a trav�s de varias v�as. Si necesit�is m�s informaci�n pod�is consultar la web de Transportes Metropolitanos de Barcelona ( www.tmb.net ).

Paradas de Metro cercanas al centro: L�nea 4 (amarilla) Barceloneta y Ciutadella.





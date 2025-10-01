## Datos

<br>

●&nbsp;&nbsp;&nbsp;&nbsp;Nombre: Elisa Luque Jiménez

●&nbsp;&nbsp;&nbsp;&nbsp;Curso Académico: 2024/2025

●&nbsp;&nbsp;&nbsp;&nbsp;Título provisional de la Tesis Doctoral: Búsqueda de artrópodos reservorios de bacterias y virus patógenos 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mediante el análisis de datos de secuenciación NGS públicos.

●&nbsp;&nbsp;&nbsp;&nbsp;Línea de Investigación: Ingeniería, Ciencia de Datos y Bioinformática.

●&nbsp;&nbsp;&nbsp;&nbsp;Director de la tesis doctoral: Antonio Jesús Pérez Pulido.

●&nbsp;&nbsp;&nbsp;&nbsp;Financiación: Contrato con duración del proyecto (cuatro años) de Titulada Superior de Apoyo a la Investigación.

●&nbsp;&nbsp;&nbsp;&nbsp;Lugar donde se llevará a cabo la investigación: Centro Andaluz de Biología del Desarrollo (CABD).

●&nbsp;&nbsp;&nbsp;&nbsp;Situación de la tesis: Finalización de tesis (a la puta calle).

<br>


<br>

## Plan de Investigación

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Introducción:

En las bases de datos públicas de datos genómicos existen actualmente miles de genomas borradores de especies de artrópodos. Cuando se secuencian estos genomas, pueden estar contaminados por genomas de microorganismos, principalmente virus y bacterias, que se encuentran colonizando al animal de partida (Cornet L et al, 2022). Las secuencias de estos otros genomas son normalmente filtrados de los proyectos de secuenciación del artrópodo, pero se encontrarían disponibles en las lecturas de los datos crudos (reads en inglés). Así, estudiando estas secuencias, utilizando herramientas de bioinformática y biología computacional, se podrían encontrar reservorios animales de microorganismos patógenos oportunistas de humanos. El conocimiento de estos reservorios sería de utilidad a la hora de manejar infecciones de patógenos conocidos o de nuevo surgimiento en nuestro entorno. 
En concreto, el género Acinetobacter es de especial interés actualmente en clínica, debido principalmente a su resistencia a antibióticos (Bharadwaj A et al, 2022) (A Hernández et al, 2010). Y, precisamente, miembros de este grupo de bacterias han sido recientemente encontrados en el medio ambiente, aislados en aves, que a su vez conviven con invertebrados (M Dahiru et al, 2015).
Dentro de un proyecto de secuenciación, cuyos datos son públicos, hemos encontrado secuencias de una bacteria del género Acinetobacter en un ácaro del género *Oppiella*, por lo que usaremos los datos crudos de este proyecto como control positivo.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Estado de la cuestión:

En la actualidad, se han publicado trabajos en los que se ha reportado la presencia de bacterias en artrópodos, centrados en algunas especies en concreto o en artrópodos que se encuentran en hospitales. 
El estudio del microbioma de artrópodos está revelando una compleja red de interacciones entre estos animales y sus microorganismos asociados. Se ha documentado la presencia de bacterias simbióticas pertenecientes a los géneros Wolbachia, Rickettsia o Sodalis, que pueden influir en la reproducción, inmunidad y capacidad como vector del hospedador (Zug R et al, 2015). Sin embargo, más allá de estos simbiontes ya conocidos, existe una diversidad microbiana aún poco caracterizada, especialmente en especies no hematófagas o no asociadas a enfermedades humanas.
Diversos estudios han demostrado que los artrópodos pueden albergar bacterias con genes de resistencia a antibióticos, incluso en entornos no clínicos (Founou L et al, 2016). Por ejemplo, se han detectado genes de resistencia a antibióticos, betalactamasas, y bombas de flujo en insectos urbanos y rurales, lo que sugiere una circulación ambiental de estos determinantes genéticos. Esta resistencia puede ser adquirida por transferencia horizontal y facilitada por la convivencia de múltiples especies bacterianas en el mismo hospedador (McGann P et al, 2016).
El uso de datos de secuenciación públicos para detectar microorganismos en hospedadores no humanos ha sido validado en varios estudios. Por ejemplo, en el artículo de Li et al. (2015) utilizaron datos de transcriptomas de insectos para identificar virus previamente no descritos. Asimismo, herramientas como Kraken2 permiten realizar análisis taxonómicos y funcionales de genomas y metagenomas a partir de datos no diseñados originalmente para ese fin (Wood et al., 2019).
En cuanto al género Acinetobacter, su presencia en artrópodos ha sido documentada en cucarachas, moscas y garrapatas, tanto en entornos urbanos como rurales. Pueden formar parte del microbioma intestinal o cuticular, y su papel como vectores o reservorios aún no está completamente descrito. La detección de genes de resistencia en estas cepas refuerza la necesidad de estudiar su ecología y evolución en hospedadores no humanos.
A pesar de estos avances, persisten importantes lagunas de conocimiento. La mayoría de estudios se centran en especies de interés médico o agrícola ya conocidas, dejando de lado la enorme diversidad de artrópodos presentes en ecosistemas naturales de los que aún se desconoce su posible papel como vector de patógenos.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Hipótesis y/o preguntas de investigación:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Hay una presencia desconocida y relevante de bacterias y virus en artrópodos, con potencial de transmisión y 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;patogenicidad en humanos, por lo que el estudio de sus datos genómicos sería de gran interés.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Existen diferencias entre las bacterias presentes en artrópodos domésticos y de ambientes urbanos (que 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;habitan en nuestras residencias y espacios habitables) y las bacterias presentes en artrópodos de ambiente 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rural.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Existen diferencias entre las bacterias presentes en artrópodos que habitan hospitales y las bacterias 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;presentes en artrópodos de ambiente urbano y rural.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Los artrópodos pueden actuar como vectores de bacterias resistentes a antibióticos tanto para humanos 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;como para otros animales.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Hay animales afectados por la transmisión de bacterias patógenas resistentes a antibióticos afectan 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;indirectamente a humanos, como en la industria cárnica.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Objetivos que se pretenden alcanzar:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Describir el género de bacteria Acinetobacter encontrada en una especie de ácaro del género *Oppiella*.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Buscar secuencias de bacterias en otros ácaros de la misma familia Oppiidae.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Descargar datos crudos de secuenciación de genomas de artrópodos aislados en diferentes ámbitos.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Buscar secuencias de bacterias y virus en los genomas de artrópodos descargados, restringiendo a grupos 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;taxonómicos concretos, en caso de existir un gran número.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Realizar pangenomas de las especies de bacterias y virus encontradas para caracterizarlas filogenéticamente 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dentro de la especie y estudiar su potencial patogenicidad y virulencia.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Buscar y analizar genes de resistencia a antibióticos y de virulencia en las secuencias de bacterias y virus 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;encontrados.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Investigar posibles diferencias entre la presencia de bacterias en artrópodos de hábitat rural y de hábitat 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;urbano.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Distinguir entre contaminación y transferencia horizontal bacteriana entre los datos de artrópodos. Dilucidar 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;si, en caso de contaminación, se debe a una relación mutualista de simbiosis, tanto de endosimbiosis como 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;de ectosimbiosis.

Estas búsquedas de datos genómicos serán realizadas en bases de datos con datos públicos de acceso disponible, como las bases de datos del National Center for Biotechnological Information (NCBI).

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Metodología:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Realización de listado de especies de artrópodos urbanos y rurales a analizar.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Descarga de datos crudos y metadatos.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Análisis de calidad y limpieza de datos crudos.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Identificación taxonómica.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Mapeado entre lecturas y genomas de referencia.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Ensamblado de genomas.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Anotación estructural y funcional de genomas.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Identificación de proteínas y dominios proteicos de interés.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Identificación de virus y profagos.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Construcción de filogenias.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Medios materiales:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Material informático: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;PCs&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Servidor C3UPO

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Servidor NAS de grupo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Servidor CICA Hércules, Junta de Andalucía 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Herramientas bioinformáticas: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;NCBI datasets&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;FastQC

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;BLAST&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;MAGICBLAST

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Kraken2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Nxtrim

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Trimmomatic&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;FastP

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Hisat2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Bowtie2

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Salmon&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;Samtools

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Bakta&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;PHASTEST

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Unicycler&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;EggNOG-mapper

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Rag-tag&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Mummer

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Panaroo&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;MAFFT

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;IQ-Tree&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Phylopic

○&nbsp;&nbsp;&nbsp;&nbsp;Programas informáticos: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;RStudio&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Visual Studio Code

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;InkScape&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Notepad ++

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;IGV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;FileZilla

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Bitvise SSH Client 

○&nbsp;&nbsp;&nbsp;&nbsp;Lenguajes informáticos: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Linux&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Python

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;Perl&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;■&nbsp;&nbsp;&nbsp;&nbsp;R 

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Planificación temporal:

| Objetivos | 2024 - 2025 | 2025 - 2026 | 2027 - 2028 | 2028 - 2029 |
| --- | :---: | :---: | :---: | :---: |
| Revisión bibliográfica y formación en diversas herramientas bioinformáticas	| X	| X	| X | X |
| Validación metodológica con caso control (*Oppiella* y *Acinetobacter*)	| X	|	| | |
| Selección y creación del listado de especies | X | X | | |
| Realización completa del pipeline de análisis de datos | X | X | | |
| Comparación entre resultados de distintos hábitats | | X | X | |
| Estudio de contaminación, transferencia horizontal y relaciones simbióticas	| X	| X | X |	|
| Construcción de pangenomas y análisis filogenético | | X | X | X |
| Redacción de la tesis | | | | X |

<br>

<br>


○&nbsp;&nbsp;&nbsp;&nbsp;Referencias Bibliográficas:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;Cornet L, Baurain D. Contamination detection in genomic data: more is not enough. Genome Biol. 2022 Feb 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;21;23(1):60. doi: 10.1186/s13059-022-02619-9. PMID: 35189924; PMCID: PMC8862208.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bharadwaj A, Rastogi A, Pandey S, Gupta S, Sohal JS. Multidrug-Resistant Bacteria: Their Mechanism of Action 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and Prophylaxis. Biomed Res Int. 2022 Sep 5;2022:5419874. doi: 10.1155/2022/5419874. PMID: 36105930; 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PMCID: PMC9467707.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A. Hernández Torres, E. García Vázquez, G. Yagüe, J. Gómez Gómez. Multidrug resistant Acinetobacter 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;baumannii: clinical update and new highlights. Revista Española de Quimioterapia, ISSN-e 0214-3429, Vol. 23, 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Nº. 1, 2010, págs. 12-19. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;M. Dahiru & O. I. Enabulele. Acinetobacter baumannii in Birds’ Feces: A Public Health Threat to Vegetables 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and Irrigation Farmers. Advances in Microbiology, Vol.5 No.10, 2015. doi: 10.4236/aim.2015.510072.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Zug R, Hammerstein P. Bad guys turned nice? A critical assessment of Wolbachia mutualisms in arthropod 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;hosts. Biol Rev Camb Philos Soc. 2015 Feb;90(1):89-111. doi: 10.1111/brv.12098. Epub 2014 Mar 11. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PMID: 24618033.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Founou LL, Founou RC, Essack SY. Antibiotic Resistance in the Food Chain: A Developing Country-Perspective. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Front Microbiol. 2016 Nov 23;7:1881. doi: 10.3389/fmicb.2016.01881. PMID: 27933044; PMCID: PMC5120092.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;McGann P, Snesrud E, Maybank R, Corey B, Ong AC, Clifford R, Hinkle M, Whitman T, Lesho E, Schaecher KE. 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Escherichia coli Harboring mcr-1 and blaCTX-M on a Novel IncF Plasmid: First Report of mcr-1 in the United 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;States. Antimicrob Agents Chemother. 2016 Jun 20;60(7):4420-1. doi: 10.1128/AAC.01103-16. Erratum in: 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Antimicrob Agents Chemother. 2016 Jul 22;60(8):5107. doi: 10.1128/AAC.01353-16. PMID: 27230792; PMCID: 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PMC4914657.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ci-Xiu Li, Mang Shi, Jun-Hua Tian, Xian-Dan Lin, Yan-Jun Kang, Liang-Jun Chen, Xin-Cheng Qin, Jianguo Xu, 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Edward C Holmes, Yong-Zhen Zhang (2015). Unprecedented genomic diversity of RNA viruses in arthropods 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;reveals the ancestry of negative-sense RNA viruses. eLife 4:e05378. doi: 10.7554/eLife.05378

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Wood, D.E., Lu, J. & Langmead, B. Improved metagenomic analysis with Kraken 2. Genome Biol 20, 257 (2019). 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;doi: 10.1186/s13059-019-1891-0

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Bae JM. Methodological issues for determining intervals of subsequent cancer screening. Epidemiol Health.  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2014;36.e2014010. doi: 10.4178/epih/e2014010

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Modalidad: Tesis monográfica.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Menciones: Tesis con mención internacional. Se prevé que la estancia dure alrededor de tres meses y que el 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;trabajo científico que se realice esté directamente relacionado con los objetivos de la tesis mencionados 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;anteriormente o con los de alguna publicación. Actualmente se está llevando a cabo una búsqueda de grupos de 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;investigación y proyectos con los que colaborar para la estancia.

<br>


<br>
 
## Plan de Formación

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Plan de formación de la Escuela de Doctorado:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Curso “La documentación científica para la elaboración de la Tesis”, impartido del 13 al 31 enero de 2025, con 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;un total de 8 horas.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Curso “La revisión bibliográfica como método de investigación”, impartido del 19 de mayo al 6 junio de 2025, 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;con un total de 6 horas.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Curso “Técnicas avanzadas de gestión de la información”, impartido del 3 al 27 de febrero de 2025, con un 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;total de 10 horas.

Se espera la participación de más cursos de la Escuela de Doctorado para el siguiente curso 2025/2026.

<br>
 
○&nbsp;&nbsp;&nbsp;&nbsp;Plan de formación de los Programas de Doctorado:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Se planea participar en los siguientes cursos en el próximo curso 2025-2026:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data processing using R: basic statistics and graph generation (duración de 10 horas).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Introduction to Data Analysis with Orange3 (duración de 10 horas).

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Seminarios de Investigación:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Asistencia a seminarios internos (Centro Andaluz de Biología del Desarrollo, CABD):

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Antonio Giráldez. Yale University. Understanding the mechanisms of gene regulations through genomics and 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;imaging. (09-04-2025).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Modesto Orozco. Instituto de Investigación Biomédica (IRB) Barcelona. Expanding the frontiers of nucleic 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;acid simulations. (21-03-2025).
  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dirk Shübeler. Friedrich Miescher Institute for Biomedical Research (FMI), Basel, Switzerland. Finding your 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;place: transcription factors and modifiers of chromatin. (11-04-2025).

<br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Asistencia a seminarios externos:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Juan Pascual-Gil & Pedro Costales Maestre. Estación Biológica de Doñana. Fire effects on mediterranean 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;communities from an ecosystem perspective / An integrative approach to the diversity of the 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mediterranean Sonchus asper taxonomic complex. (13-02-2025).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Ladislav Hamerlik.  Estación Biológica de Doñana. Paleolimnology: Reading the lake sediments to reveal 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;environmental history. (20-02-2025).

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Reuniones de seguimiento de los Proyectos:

Todos los jueves se han realizado reuniones de grupo de los integrantes del grupo de investigación a cargo de Antonio Jesús Pérez Pulido, en las que se ha seguido el progreso de la tesis semanalmente.
Se planea participar en los CABD Meetings y presentar una charla en el año 2025, que tratará sobre los inicios de la tesis doctoral y los avances hasta el momento.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Cursos de especialización científica:

Todos los títulos obtenidos a lo largo de la carrera académica previa a la tesis han aportado conocimiento para ésta:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Máster en Análisis de Datos Ómicos y Biología de Sistemas, Universidad Internacional de Andalucía, 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sevilla (2023 - presente).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Diploma de experta en Bioinformática, Universidad Pablo de Olavide, Sevilla (2023 - 2024).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Curso de Experto Universitario en Entomología Aplicada, Universidad Nacional de Educación a Distancia 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2021).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Máster en Biodiversidad, Universidad Autónoma de Madrid, Madrid (2019 - 2020).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Grado en Biotecnología, Universidad Pablo de Olavide, Sevilla (2014 - 2019).

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Asistencia y participación a congresos:

Se ha asistido y participado en las Jornadas Andaluzas de Bioinformática (JABI), en Málaga, del 12 al 14 de mayo de 2025, realizando una comunicación oral titulada “Bacteriophages in arthropods or contamination in genome databases?”.
Se planea participar además en las próximas JABI, presentando póster, y en los años siguientes que se realice la tesis.
Se planea participar en las Jornadas Doctorales en el curso 2024/2025 que se emplazarán en Carmona, en el Palacio de los Briones (sede de la Universidad Pablo de Olavide), en el mes de octubre. Se realizará una presentación de póster.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Publicaciones:

En estos momentos se encuentra en proceso de publicar un artículo como primera autora titulado “A bacteriophage in a mite genome reveals bacterial contamination and opens new possibilities for exploring arthropod symbionts“ en la revista Microbial Genomics, a la que enviamos el manuscrito en el mes de abril y recibimos primera revisión en junio (Major revision). Enviaremos la segunda versión corregida y ampliada antes de agosto con perspectiva de ser publicada en los próximos meses. Este trabajo incluye los resultados de la primera parte de la tesis.
Se prevé publicar más artículos y/o comunicaciones en los siguientes años de tesis, tanto como primera autora, como otras colaboraciones en el grupo.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Estancias:

No se ha realizado ninguna estancia por el momento. Se planea hacerla en un centro de investigación internacional para el tercer año de tesis, en el curso 2026-2027, de una duración de alrededor de tres meses. El objetivo de la estancia será de un trabajo que deberá formar una aportación sustancial a la tesis, ya sea trabajo de campo y laboratorio o trabajo computacional.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Formación para la docencia:

Se planea ejercer de ayudante de prácticas para prácticas tuteladas de la asignatura “Bioinformática” del grado de Biotecnología de la Universidad Pablo de Olavide en los próximos años de la tesis. Durante el curso 2025-2026 ya se han planificado alrededor de 21 horas.
Se planea ejercer como docente en el diploma de especialización de Bioinformática de la Universidad Pablo de Olavide a partir del curso 2026-2027.

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Iniciación a la Dirección de Proyectos Científicos y a la Transferencia de Conocimientos:

Como primera autora del artículo mencionado anteriormente, y para su completa realización entre varios miembros del grupo de investigación de mi director de tesis, se ha debido ejercer una labor de coordinadora de proyecto, de tal forma que las tareas ejercidas por los miembros participantes fueran coherentes las unas con las otras, se realizaran correctamente y finalmente se pusieran en común los resultados para construir el artículo. 

<br>

○&nbsp;&nbsp;&nbsp;&nbsp;Complementos Formativos:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Participación en el taller del Centro Andaluz de Biología del Desarrollo en la Feria de las Ciencias de
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sevilla, el 22 de abril de 2025, duración de cuatro horas. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Participación en el taller “¿Cómo se forman los seres vivos?” en el Colegio de Educación Infantil y 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Primaria Ana María Matute en Dos Hermanas, Sevilla, el día 21 de enero de 2025, duración de dos
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;horas.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Participación en el taller “Aprendiendo con los ratones” en el Colegio de Educación Infantil y Primaria 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tartessos, en Sevilla Este, el día 28 de mayo de 2025, duración de tres horas.


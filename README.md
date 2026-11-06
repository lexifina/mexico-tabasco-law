# Tabasco: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Tabasco, Mexico, which global-law reads at `mexico/tabasco/acts/`.

The law of the State of Tabasco (Estado Libre y Soberano de Tabasco, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-tab/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

121 ordenamientos with 792 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE TABASCO | 118 | as first published, then each reform: 5 April 1919 to 27 August 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE TABASCO | 33 | as first published, then each reform: 12 April 1997 to 3 September 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO DE TABASCO | 14 | as first published, then each reform: 15 April 1997 to 17 October 2019 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE TABASCO | 18 | as first published, then each reform: 10 October 1993 to 27 December 2025 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE TABASCO | 74 | as first published, then each reform: 8 February 1997 to 13 September 2026 |
| `ley-agricola/` | LEY AGRICOLA PARA EL ESTADO DE TABASCO | 3 | as first published, then each reform: 23 May 2010 to 28 December 2025 |
| `ley-de-acceso-a-la-justicia-alternativa/` | LEY DE ACCESO A LA JUSTICIA ALTERNATIVA PARA EL ESTADO DE TABASCO | 2 | as first published, then each reform: 30 August 2012 to 17 November 2013 |
| `ley-de-acuicultura-y-pesca/` | LEY DE ACUICULTURA Y PESCA DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 27 January 2012 to 19 July 2020 |
| `ley-de-adquisiciones-arrendamientos-y-prestacion-de-servicio/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y PRESTACION DE SERVICIOS DEL ESTADO DE TABASCO | 11 | as first published, then each reform: 27 May 2005 to 20 September 2026 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE TABASCO | 2 | as first published, then each reform: 1 January 2021 to 21 October 2025 |
| `ley-de-arrendamiento-de-fincas-urbanas/` | LEY DE ARRENDAMIENTO DE FINCAS URBANAS | 1 | as first published: 27 July 1947 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE TABASCO | 1 | as first published: 22 July 2021 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS DEL ESTADO DE TABASCO Y SUS MUNICIPIOS | 3 | as first published, then each reform: 18 May 2014 to 6 July 2017 |
| `ley-de-atencion-a-victimas/` | LEY DE ATENCION A VICTIMAS DEL ESTADO DE TABASCO -ANTES LEY DE ATENCION, APOYO Y PROTECCION A VICTIMAS U OFENDIDOS EN EL ESTADO DE TABASCO- | 2 | as first published, then each reform: 31 January 2016 to 17 October 2019 |
| `ley-de-austeridad/` | LEY DE AUSTERIDAD DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 10 November 2024 to 19 December 2024 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE TABASCO Y SUS MUNICIPIOS | 1 | as first published: 17 September 2017 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE TABASCO | 4 | as first published, then each reform: 24 January 1993 to 7 May 2026 |
| `ley-de-condominios/` | LEY DE CONDOMINIOS DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 2 March 2006 to 6 July 2017 |
| `ley-de-consulta-popular-e-iniciativa-ciudadana/` | LEY DE CONSULTA POPULAR E INICIATIVA CIUDADANA PARA EL ESTADO DE TABASCO | 1 | as first published: 12 October 2023 |
| `ley-de-control-constitucional-reglamentaria-del-articulo-61/` | LEY DE CONTROL CONSTITUCIONAL REGLAMENTARIA DEL ARTICULO 61 DE LA CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE TABASCO | 1 | as first published: 23 March 2018 |
| `ley-de-cooperacion-para-obras-publicas-municipales/` | LEY DE COOPERACION PARA OBRAS PUBLICAS MUNICIPALES | 1 | as first published: 13 May 1961 |
| `ley-de-coordinacion-fiscal-y-financiera/` | LEY DE COORDINACION FISCAL Y FINANCIERA DEL ESTADO DE TABASCO | 17 | as first published, then each reform: 2 January 1993 to 21 December 2024 |
| `ley-de-coordinacion-para-el-establecimiento-y-desarrollo-de/` | LEY DE COORDINACION PARA EL ESTABLECIMIENTO Y DESARROLLO DE ZONAS ECONOMICAS ESPECIALES DEL ESTADO DE TABASCO | 1 | as first published: 31 December 2016 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE TABASCO | 4 | as first published, then each reform: 30 March 2006 to 24 March 2013 |
| `ley-de-derechos-humanos/` | LEY DE DERECHOS HUMANOS DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 10 May 2014 to 31 May 2018 |
| `ley-de-derechos-y-cultura-indigena/` | LEY DE DERECHOS Y CULTURA INDIGENA DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 25 May 2009 to 22 May 2025 |
| `ley-de-desarrollo-pecuario/` | LEY DE DESARROLLO PECUARIO DEL ESTADO DE TABASCO | 5 | as first published, then each reform: 2 June 2011 to 27 May 2024 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE TABASCO | 5 | as first published, then each reform: 30 April 2009 to 27 December 2025 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL DEL ESTADO DE TABASCO | 4 | as first published, then each reform: 2 January 2007 to 18 May 2025 |
| `ley-de-desarrollo-turistico/` | LEY DE DESARROLLO TURISTICO DEL ESTADO DE TABASCO | 1 | as first published: 1 January 2007 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO DE TABASCO Y SUS MUNICIPIOS | 7 | as first published, then each reform: 1 January 2006 to 27 December 2025 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE TABASCO | 26 | as first published, then each reform: 13 March 1997 to 24 September 2026 |
| `ley-de-ejecucion-de-sanciones-penales/` | LEY DE EJECUCION DE SANCIONES PENALES PARA EL ESTADO DE TABASCO | 1 | as first published: 28 September 2012 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 1 June 1948 to 7 January 1959 |
| `ley-de-fiscalizacion-superior/` | LEY DE FISCALIZACION SUPERIOR DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 16 July 2017 to 31 August 2025 |
| `ley-de-fomento-a-la-lectura-y-el-libro/` | LEY DE FOMENTO A LA LECTURA Y EL LIBRO DEL ESTADO DE TABASCO | 1 | as first published: 21 May 2015 |
| `ley-de-fomento-apicola-y-proteccion-de-agentes-polinizadores/` | LEY DE FOMENTO APICOLA Y PROTECCION DE AGENTES POLINIZADORES PARA EL ESTADO DE TABASCO | 1 | as first published: 27 May 2024 |
| `ley-de-fomento-para-la-investigacion-cientifica-y-desarrollo/` | LEY DE FOMENTO PARA LA INVESTIGACION CIENTIFICA Y DESARROLLO TECNOLOGICO PARA EL ESTADO DE TABASCO | 2 | as first published, then each reform: 28 September 2000 to 13 September 2006 |
| `ley-de-fomento-y-proteccion-artesanal/` | LEY DE FOMENTO Y PROTECCION ARTESANAL DEL ESTADO DE TABASCO | 1 | as first published: 22 April 2024 |
| `ley-de-gobierno-digital-y-firma-electronica/` | LEY DE GOBIERNO DIGITAL Y FIRMA ELECTRONICA PARA EL ESTADO DE TABASCO Y SUS MUNICIPIOS | 3 | as first published, then each reform: 8 March 2018 to 1 January 2026 |
| `ley-de-hacienda/` | LEY DE HACIENDA DEL ESTADO DE TABASCO | 19 | as first published, then each reform: 2 January 2016 to 12 April 2026 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO DE TABASCO | 11 | as first published, then each reform: 2 January 1993 to 22 August 2020 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE TABASCO PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 27 December 2025 |
| `ley-de-justicia-administrativa/` | LEY DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 16 July 2017 to 12 April 2026 |
| `ley-de-la-campana-contra-las-enfermedades-y-plagas-del-plata/` | LEY DE LA CAMPAÑA CONTRA LAS ENFERMEDADES Y PLAGAS DEL PLATANO | 2 | as first published, then each reform: 2 January 1963 to 9 August 2026 |
| `ley-de-la-comision-estatal-de-conciliacion-y-arbitraje-medic/` | LEY DE LA COMISION ESTATAL DE CONCILIACION Y ARBITRAJE MEDICO | 3 | as first published, then each reform: 24 March 2002 to 5 May 2019 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD PARA EL ESTADO DE TABASCO | 3 | as first published, then each reform: 17 April 2012 to 13 October 2013 |
| `ley-de-la-responsabilidad-civil-por-dano-y-deterioro-ambient/` | LEY DE LA RESPONSABILIDAD CIVIL POR DAÑO Y DETERIORO AMBIENTAL DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 27 February 2005 to 26 May 2013 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE TABASCO | 7 | as first published, then each reform: 24 December 2015 to 28 December 2025 |
| `ley-de-los-servicios-publicos/` | LEY DE LOS SERVICIOS PUBLICOS | 1 | as first published: 2 January 1971 |
| `ley-de-los-trabajadores-al-servicio/` | LEY DE LOS TRABAJADORES AL SERVICIO DEL ESTADO DE TABASCO | 20 | as first published, then each reform: 5 April 1990 to 2 July 2026 |
| `ley-de-medios-de-impugnacion-en-materia-electoral/` | LEY DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL DEL ESTADO DE TABASCO | 6 | as first published, then each reform: 13 December 2008 to 19 January 2025 |
| `ley-de-movilidad/` | LEY DE MOVILIDAD PARA EL ESTADO DE TABASCO | 5 | as first published, then each reform: 1 December 2019 to 20 September 2026 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS DEL ESTADO DE TABASCO | 10 | as first published, then each reform: 6 June 2004 to 18 December 2025 |
| `ley-de-operaciones-inmobiliarias/` | LEY DE OPERACIONES INMOBILIARIAS DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 8 October 2009 to 6 July 2017 |
| `ley-de-planeacion/` | LEY DE PLANEACION | 10 | as first published, then each reform: 14 July 1983 to 2 July 2026 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-y-de/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL EN EL ESTADO DE TABASCO | 1 | as first published: 25 June 2017 |
| `ley-de-presupuesto-y-responsabilidad-hacendaria/` | LEY DE PRESUPUESTO Y RESPONSABILIDAD HACENDARIA DEL ESTADO DE TABASCO Y SUS MUNICIPIOS | 8 | as first published, then each reform: 17 December 2015 to 20 September 2026 |
| `ley-de-proteccion-ambiental/` | LEY DE PROTECCION AMBIENTAL DEL ESTADO DE TABASCO | 4 | as first published, then each reform: 21 January 2013 to 9 May 2019 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 1 January 2015 to 5 May 2019 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE TABASCO | 1 | as first published: 15 June 2025 |
| `ley-de-proteccion-y-fomento-del-patrimonio-cultural/` | LEY DE PROTECCION Y FOMENTO DEL PATRIMONIO CULTURAL PARA EL ESTADO DE TABASCO | 3 | as first published, then each reform: 29 March 2013 to 12 October 2025 |
| `ley-de-remuneraciones-de-los-servidores-publicos/` | LEY DE REMUNERACIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE TABASCO Y SUS MUNICIPIOS | 2 | as first published, then each reform: 29 December 2011 to 6 July 2017 |
| `ley-de-responsabilidad-administrativa-de-los-servidores-publ/` | LEY DE RESPONSABILIDAD ADMINISTRATIVA DE LOS SERVIDORES PUBLICOS, REGLAMENTARIA DEL ARTICULO 68, DEL TITULO VII, DE LA CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE TABASCO -ANTES LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS, REGLAMENTARIA DE LOS ARTICULOS 68 Y 69, DEL TITULO VII, DE LA CONSTITUCION POLITICA DEL ESTADO DE TABASCO -ANTES LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS QUE REGLAMENTA EL TITULO SEPTIMO DE LA LEY FUNDAMENTAL DEL ESTADO DE TABASCO- | 6 | as first published, then each reform: 14 July 1983 to 24 April 2022 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE TABASCO Y SUS MUNICIPIOS | 1 | as first published: 11 April 2023 |
| `ley-de-revocacion-de-mandato/` | LEY DE REVOCACION DE MANDATO DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 17 April 2025 to 3 September 2026 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE TABASCO | 18 | as first published, then each reform: 12 March 2010 to 10 November 2025 |
| `ley-de-seguridad-social/` | LEY DE SEGURIDAD SOCIAL DEL ESTADO DE TABASCO | 7 | as first published, then each reform: 1 January 2016 to 12 April 2026 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 15 June 2025 to 20 November 2025 |
| `ley-de-usos-de-agua/` | LEY DE USOS DE AGUA DEL ESTADO DE TABASCO | 5 | oldest version available, then each reform: 20 June 2005 to 5 May 2019 |
| `ley-de-valuacion/` | LEY DE VALUACION PARA EL ESTADO DE TABASCO | 4 | as first published, then each reform: 1 January 2012 to 27 December 2025 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE TABASCO | 6 | as first published, then each reform: 28 October 2011 to 14 June 2026 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 20 February 2020 to 20 August 2025 |
| `ley-del-instituto-estatal-de-las-mujeres/` | LEY DEL INSTITUTO ESTATAL DE LAS MUJERES | 5 | as first published, then each reform: 23 December 2001 to 5 May 2019 |
| `ley-del-libro-y-bibliotecas-publicas/` | LEY DEL LIBRO Y BIBLIOTECAS PUBLICAS DEL ESTADO LIBRE Y SOBERANO DE TABASCO | 2 | as first published, then each reform: 7 June 2012 to 6 July 2017 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE TABASCO | 5 | as first published, then each reform: 19 January 2004 to 7 May 2026 |
| `ley-del-servicio-civil/` | LEY DEL SERVICIO CIVIL DEL ESTADO DE TABASCO | 1 | as first published: 10 November 1956 |
| `ley-del-servicio-de-defensoria-publica/` | LEY DEL SERVICIO DE DEFENSORIA PUBLICA DEL ESTADO DE TABASCO | 1 | as first published: 24 April 2015 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 12 June 2025 to 18 December 2025 |
| `ley-del-sistema-de-seguridad-publica/` | LEY DEL SISTEMA DE SEGURIDAD PUBLICA DEL ESTADO DE TABASCO | 7 | as first published, then each reform: 11 August 2015 to 24 September 2026 |
| `ley-del-sistema-estatal-de-asistencia-social/` | LEY DEL SISTEMA ESTATAL DE ASISTENCIA SOCIAL DEL ESTADO DE TABASCO | 10 | as first published, then each reform: 30 December 1986 to 31 March 2023 |
| `ley-electoral-y-de-partidos-politicos/` | LEY ELECTORAL Y DE PARTIDOS POLITICOS DEL ESTADO DE TABASCO | 10 | as first published, then each reform: 2 July 2014 to 3 September 2026 |
| `ley-en-materia-de-desaparicion-forzada-de-personas-desaparic/` | LEY EN MATERIA DE DESAPARICION FORZADA DE PERSONAS, DESAPARICION COMETIDA POR PARTICULARES Y DEL SISTEMA DE BUSQUEDA DE PERSONAS PARA EL ESTADO DE TABASCO | 3 | as first published, then each reform: 13 June 2019 to 25 September 2025 |
| `ley-estatal-de-acceso-de-las-mujeres-a-una-vida-libre-de-vio/` | LEY ESTATAL DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA DEL ESTADO DE TABASCO | 12 | as first published, then each reform: 19 January 2009 to 2 October 2025 |
| `ley-forestal/` | LEY FORESTAL DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 1 April 2006 to 15 May 2025 |
| `ley-general-de-seguridad-publica-y-transito/` | LEY GENERAL DE SEGURIDAD PUBLICA Y TRANSITO DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 4 August 1984 to 14 September 2006 |
| `ley-general-de-transito-y-vialidad/` | LEY GENERAL DE TRANSITO Y VIALIDAD DEL ESTADO DE TABASCO | 16 | as first published, then each reform: 28 May 2006 to 17 May 2026 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE TABASCO | 6 | as first published, then each reform: 14 December 2014 to 12 April 2026 |
| `ley-organica-de-la-universidad-juarez-autonoma-de-tabasco/` | LEY ORGANICA DE LA UNIVERSIDAD JUAREZ AUTONOMA DE TABASCO | 1 | as first published: 22 December 1987 |
| `ley-organica-de-los-municipios/` | LEY ORGANICA DE LOS MUNICIPIOS DEL ESTADO DE TABASCO | 28 | as first published, then each reform: 2 January 2004 to 3 May 2026 |
| `ley-organica-del-colegio-de-bachilleres-de-tabasco/` | LEY ORGANICA DEL COLEGIO DE BACHILLERES DE TABASCO | 1 | as first published: 19 November 1998 |
| `ley-organica-del-poder-ejecutivo/` | LEY ORGANICA DEL PODER EJECUTIVO DEL ESTADO DE TABASCO | 9 | as first published, then each reform: 12 November 2024 to 25 October 2026 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE TABASCO | 12 | as first published, then each reform: 29 May 2016 to 3 September 2026 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 21 May 2024 to 27 October 2025 |
| `ley-organica-del-tribunal-electoral/` | LEY ORGANICA DEL TRIBUNAL ELECTORAL DEL ESTADO DE TABASCO | 6 | as first published, then each reform: 29 November 2002 to 6 July 2017 |
| `ley-organica-y-de-procedimientos-del-consejo-tutelar-para-me/` | LEY ORGANICA Y DE PROCEDIMIENTOS DEL CONSEJO TUTELAR PARA MENORES INFRACTORES DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 16 July 1983 to 28 October 1999 |
| `ley-para-el-desarrollo-economico-sostenible/` | LEY PARA EL DESARROLLO ECONOMICO SOSTENIBLE DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 17 November 2019 to 31 December 2022 |
| `ley-para-la-administracion-y-destino-de-bienes-asegurados-ab/` | LEY PARA LA ADMINISTRACION Y DESTINO DE BIENES ASEGURADOS, ABANDONADOS O DECOMISADOS, DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 27 November 2015 to 29 June 2025 |
| `ley-para-la-atencion-y-proteccion-a-personas-con-la-condicio/` | LEY PARA LA ATENCION Y PROTECCION A PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA EN EL ESTADO DE TABASCO | 2 | as first published, then each reform: 24 December 2015 to 20 April 2026 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 20 November 2014 to 11 December 2025 |
| `ley-para-la-prevencion-y-gestion-integral-de-los-residuos/` | LEY PARA LA PREVENCION Y GESTION INTEGRAL DE LOS RESIDUOS, DEL ESTADO DE TABASCO | 4 | as first published, then each reform: 28 January 2013 to 26 January 2026 |
| `ley-para-la-prevencion-y-tratamiento-de-la-violencia-intrafa/` | LEY PARA LA PREVENCION Y TRATAMIENTO DE LA VIOLENCIA INTRAFAMILIAR PARA EL ESTADO DE TABASCO | 3 | as first published, then each reform: 30 May 1999 to 12 October 2023 |
| `ley-para-la-promocion-fomento-y-desarrollo-de-la-industria-c/` | LEY PARA LA PROMOCION, FOMENTO Y DESARROLLO DE LA INDUSTRIA CINEMATOGRAFICA Y AUDIOVISUAL DEL ESTADO DE TABASCO | 1 | as first published: 31 January 2024 |
| `ley-para-la-proteccion-de-las-personas-adultas-mayores-en-el/` | LEY PARA LA PROTECCION DE LAS PERSONAS ADULTAS MAYORES EN EL ESTADO DE TABASCO | 5 | as first published, then each reform: 17 May 2003 to 2 October 2022 |
| `ley-para-la-proteccion-de-personas-que-intervienen-en-el-pro/` | LEY PARA LA PROTECCION DE PERSONAS QUE INTERVIENEN EN EL PROCEDIMIENTO PENAL, DEL ESTADO DE TABASCO | 1 | as first published: 29 June 2015 |
| `ley-para-la-proteccion-y-cuidado-de-los-animales-en-el-estad/` | LEY PARA LA PROTECCION Y CUIDADO DE LOS ANIMALES EN EL ESTADO DE TABASCO | 3 | as first published, then each reform: 17 January 2014 to 10 March 2024 |
| `ley-para-prevenir-y-eliminar-la-discriminacion-en-el-estado/` | LEY PARA PREVENIR Y ELIMINAR LA DISCRIMINACION EN EL ESTADO DE TABASCO | 3 | as first published, then each reform: 15 May 2016 to 15 February 2026 |
| `ley-para-prevenir-combatir-y-sancionar-la-trata-de-personas/` | LEY PARA PREVENIR, COMBATIR Y SANCIONAR LA TRATA DE PERSONAS EN EL ESTADO DE TABASCO | 1 | as first published: 27 December 2009 |
| `ley-para-prevenir-investigar-y-sancionar-el-delito-de-extors/` | LEY PARA PREVENIR, INVESTIGAR Y SANCIONAR EL DELITO DE EXTORSION EN EL ESTADO DE TABASCO | 2 | as first published, then each reform: 26 February 2026 to 3 September 2026 |
| `ley-que-crea-el-instituto-de-cultura-de-tabasco/` | LEY QUE CREA EL INSTITUTO DE CULTURA DE TABASCO | 2 | as first published, then each reform: 10 November 1984 to 17 June 1999 |
| `ley-que-crea-el-instituto-tecnologico-superior-de-comalcalco/` | LEY QUE CREA EL INSTITUTO TECNOLOGICO SUPERIOR DE COMALCALCO | 4 | as first published, then each reform: 15 February 1996 to 12 April 2018 |
| `ley-que-crea-el-instituto-tecnologico-superior-de-los-rios/` | LEY QUE CREA EL INSTITUTO TECNOLOGICO SUPERIOR DE LOS RIOS | 5 | as first published, then each reform: 24 November 1996 to 27 October 2021 |
| `ley-que-establece-los-procedimientos-de-entrega-y-recepcion/` | LEY QUE ESTABLECE LOS PROCEDIMIENTOS DE ENTREGA Y RECEPCION EN LOS PODERES PUBLICOS, LOS AYUNTAMIENTOS Y LOS ORGANOS CONSTITUCIONALES AUTONOMOS DEL ESTADO DE TABASCO | 2 | as first published, then each reform: 19 December 2014 to 3 April 2016 |
| `ley-que-garantiza-la-entrega-de-utiles-escolares-en-el-estad/` | LEY QUE GARANTIZA LA ENTREGA DE UTILES ESCOLARES EN EL ESTADO DE TABASCO | 1 | as first published: 3 April 2005 |
| `ley-que-regula-la-venta-distribucion-y-consumo-de-bebidas-al/` | LEY QUE REGULA LA VENTA, DISTRIBUCION Y CONSUMO DE BEBIDAS ALCOHOLICAS EN EL ESTADO DE TABASCO | 9 | as first published, then each reform: 22 December 2001 to 20 September 2025 |
| `ley-que-regula-las-casas-de-empeno-en-el-estado-de-tabasco/` | LEY QUE REGULA LAS CASAS DE EMPEÑO EN EL ESTADO DE TABASCO | 3 | as first published, then each reform: 25 December 2007 to 6 July 2017 |
| `ley-registral/` | LEY REGISTRAL DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 1 February 2011 to 7 May 2026 |
| `ley-reglamentaria-de-la-fraccion-iv-del-articulo-7-de-la-con/` | LEY REGLAMENTARIA DE LA FRACCION IV, DEL ARTICULO 7, DE LA CONSTITUCION POLITICA DEL ESTADO | 1 | as first published: 30 March 2003 |
| `ley-reglamentaria-de-los-articulos-4-y-5-de-la-constitucion/` | LEY REGLAMENTARIA DE LOS ARTICULOS 4°. Y 5°. DE LA CONSTITUCION FEDERAL, RELATIVA AL EJERCICIO DE LAS PROFESIONES EN EL ESTADO DE TABASCO | 3 | as first published, then each reform: 28 February 1967 to 7 July 1974 |
| `ley-sobre-las-caracteristicas-y-uso-del-escudo/` | LEY SOBRE LAS CARACTERISTICAS Y USO, DEL ESCUDO DEL ESTADO DE TABASCO | 3 | as first published, then each reform: 14 January 2013 to 20 February 2020 |
| `ley-sobre-los-derechos-de-las-personas-con-discapacidad/` | LEY SOBRE LOS DERECHOS DE LAS PERSONAS CON DISCAPACIDAD PARA EL ESTADO DE TABASCO | 8 | as first published, then each reform: 1 July 2011 to 13 December 2022 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.

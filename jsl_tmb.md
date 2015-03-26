<!-- .slide: id="r2014 data-background="#FFFFFF"" -->
# Evolución del GIS en TMB
----------
<br/>
## _9as Jornadas SIG Libre_
#### On-line: <a href="http://sergioedo.github.io/workshops/" target="_blank">http://sergioedo.github.io/jsl/jsl_tmb.html</a>
<br/>
<br/>
<img style="border: 0; box-shadow: none; margin: 0;" src="img/jsl/tmb.png"/>
#### 2015 - Sergio Edo / Eduard Porquet
<br/>


---

# La Empresa
----------

## _Transports Metropolitants de Barcelona_ (TMB)
<br/>

 * ### Unión de dos empresas:
  * ### Transports de Barcelona y Ferrocarril Metropolità de Barcelona
 * ### Gestiona la red de bus y metro del _Área metropolitana de Barcelona_
  * ### Área de influencia (18 municipios)
  * ### +550 Millones de desplazamientos al año
 * ### <a href="www.tmb.cat" target="_blank">www.tmb.cat</a>


<!-- side node http://www.tmb.cat/ca/c/document_library/get_file?uuid=eea42c92-624d-44e4-b3ec-334298b6db0b&groupId=10168 -->

---

# TMB - Bus
----------
## **+100** líneas de autobús
## **+2700** paradas y **+35** áreas intercambio
<img style="border: 0; margin: 0;" src="img/jsl/nxb.png"/> 

-v-

## **+900 autobuses** en circulación diaria
<img style="border: 0; box-shadow: none; margin: 0;" src="img/jsl/buses.png"/>

-v-

## **+1000 alteraciones** y desvíos del servicio **al año**
<img style="border: 0; margin: 0;" src="img/jsl/bus_disruption.png"/>

---

# TMB - Metro
----------
## **8** líneas y **142** estaciones de Metro
<img style="border: 0; margin: 0;" src="img/jsl/metro_red.png"/>

-v-

## **+700** plantas de infraestructura (2.5D)
<img style="border: 0; margin: 0;" src="img/jsl/metro_infra.png"/>

-v-

## **+100** Km de vías/túnel
## **+500K** Elementos en dependencias
  ### _Energia, seguridad, limpieza, vía, ..._
<img style="border: 0; margin: 0;" src="img/jsl/metro_vies.png"/>

---

# Evolución del GIS
----------
<img style="border: 0; margin: 0;" src="img/jsl/history.png"/>

-v-

# Punto de partida
----------
* ## Dos plataformas **independientes/heterogéneas**
    * ### Basadas en E$RI y Int€rgraph 
* ## Grandes problemas para **integrar** datos
<!-- .element: class="fragment" data-fragment-index="1" -->
* ## Sólo disponible para usuarios **técnicos**
<!-- .element: class="fragment" data-fragment-index="2" -->
<br/>
* ## Punto inflexión:
<!-- .element: class="fragment" data-fragment-index="3" -->
<img style="border: 0;" src="img/jsl/foss4g2010.png"/>
<!-- .element: class="fragment" data-fragment-index="3" -->

-v-

# Modelo de publicación
----------
<img style="border: 0; margin: 0;" src="img/jsl/publish_model.png"/>

-v-

<!-- .slide: data-transition="none" -->
# Ciclo de vida
----------
### Estrategia evolución de los datos
<img style="border: 0; margin: 0;" src="img/jsl/users_data1.png"/>

-v-

<!-- .slide: data-transition="none" -->
# Ciclo de vida
----------
### Datos GIS - sólo geometría
<img style="border: 0; margin: 0;" src="img/jsl/users_data2.png"/>

-v-

<!-- .slide: data-transition="none" -->
# Ciclo de vida
----------
### Aplicar conocimiento de negocio
<img style="border: 0; margin: 0;" src="img/jsl/users_data3.png"/>

-v-

<!-- .slide: data-transition="none" -->
# Ciclo de vida
----------
### Enriquecer datos para publicación
<img style="border: 0; margin: 0;" src="img/jsl/users_data4.png"/>

-v-

<!-- .slide: data-transition="none" -->
# Ciclo de vida
----------
### Balance entre técnico y gran público
<img style="border: 0; margin: 0;" src="img/jsl/users_data5.png"/>

-v-


# Características
----------

* ## **Desacople** tecnológico >> nuevas herramientas
<!-- .element: class="fragment" data-fragment-index="1" -->

* ## Integra datos de **ambos sistemas**
<!-- .element: class="fragment" data-fragment-index="2" -->

* ## Enriquece/adapta para **consulta**
<!-- .element: class="fragment" data-fragment-index="3" -->

* ## Agregaciones, relaciones, simplificaciones...
<!-- .element: class="fragment" data-fragment-index="4" -->

* ## Modelo navegable >> **+Usabilidad**
<!-- .element: class="fragment" data-fragment-index="5" -->

-v-

# GeoPortal
----------

* ## NO orientado a capas
<!-- .element: class="fragment" data-fragment-index="1" -->
* ## Basado en la **navegación** (modelo de datos)
<!-- .element: class="fragment" data-fragment-index="2" -->
* ## Relaciones entre modelos (p.e. correspondencias)
<!-- .element: class="fragment" data-fragment-index="3" -->
* ## **Acercamiento** al "gran público"
<!-- .element: class="fragment" data-fragment-index="4" -->
* ## Servicios+librerías **"estándar"** >> +integración
<!-- .element: class="fragment" data-fragment-index="5" -->
<br/>
<br/>
_<a href="https://www.youtube.com/watch?v=FoJQLFznjCo" target="_blank">Watch video on Youtube</a>_
<!-- .element: class="fragment" data-fragment-index="5" -->

---

# Arquitectura
----------

![](img/jsl/architecture.png)

-v-


# Productos consolidados
----------

* ## Bases de datos: **Oracle** $patial
* ## Servidor: **GeoServer** + GeoWebCache
* ## Cliente web: **GXP** (GeoExt, Ext + Openlayers)
* ## Buscador: Apache **SOLR**
* ## Rutas: **OpenTripPlanner**

-v-

# Nuevos productos...
----------

* ## MongoDB
* ## NodeJS/IOjs
* ## Openlayers 3
* ## ElasticSearch
* ## ...

-v-

# Objetivo final - Plataforma
----------

* ## Plataforma de servicios (API)
<!-- .element: class="fragment" data-fragment-index="1" -->
* ## GIS everywhere >> **more people** doing GIS
<!-- .element: class="fragment" data-fragment-index="2" -->
* ## **Acercamiento** a "desarrolladores"
<!-- .element: class="fragment" data-fragment-index="3" -->

---

<!-- .slide: id="r2014 data-background="#FEEFAD"" -->
# Gracias por vuestra atención!
<br/>
<img style="border: 0; margin: 0;" src="img/jsl/cat.jpg"/>



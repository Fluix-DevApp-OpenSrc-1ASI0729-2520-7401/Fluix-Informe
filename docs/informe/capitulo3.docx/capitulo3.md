# Capítulo III: Requirements Specification

## 3.1. User Stories.


| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :---- | :---- | :---- | :---- | :---- |
| EP01 | Registro de usuarios | Implementar el registro de los usuarios |  |  |
| US01 | Registro de vivienda | Como cliente que vive en un zona residencial Quiero registrarme en la aplicación web Para monitorear en tiempo real el nivel de agua en mi vivienda . | Escenario 01: Registro exitoso. Dado que entro a la aplicación web de Droplet, Cuando completo todos los campos del formulario del registro, Entonces el sistema guarda la información y aparece un mensaje de aprobación . Escenario 02: Fallo en el registro. Dado que entro a la aplicación web de Droplet, Cuando dejo campos obligatorios vacíos o ingreso datos inválidos, Entonces el sistema muestra mensajes de error y no permite enviar el formulario hasta corregir los datos. | EP01 |
| US02 | Registro de empresa | Como gerente Quiero registrar mi empresa Para tener un monitoreo del nivel y caudal de agua en mi negocio. | Escenario 01: Registro exitoso. Dado que entro a la aplicación web de Droplet, Cuando completo todos los campos del formulario del registro, Entonces el sistema guarda la información y aparece un mensaje de aprobación . Escenario 02: Fallo en el registro. Dado que entro a la aplicación web de Droplet, Cuando dejo campos obligatorios vacíos o ingreso datos inválidos, Entonces el sistema muestra mensajes de error y no permite enviar el formulario hasta corregir los datos. | EP01 |
| US03 | Registro de  | Como xx Quiero xx Para xx. | Escenario 01: xx. Dado que xx, Cuando xx, Entonces xx. Escenario 02: xx. Dado que xx, Cuando xx, Entonces xx. | EP01 |
| EP02 | Monitoreo en tiempo real | Permitir a los usuarios ver en tiempo real el nivel, consumo y calidad de los líquidos en sus tanques o cisternas tanto en hogares como plantas industriales |  |  |
| US03 | Visualización de nivel en tiempo real | Como propietario de vivienda, Quiero ver el nivel actual de agua en mi tanque Para saber cuándo debo planificar una recarga. | Escenario 01: Visualización de nivel. Dado que el sensor está instalado en mi tanque, Cuando abro la aplicación, Entonces veo el nivel actualizado en litros o porcentaje. | EP02 |
| US04 | Medición de caudal | Como jefe de planta, Quiero medir el caudal en tiempo real Para detectar fugas o consumos anómalos. | Escenario 01: Desvío en caudal. Dado un flujo activo, Cuando el caudal se desvía del rango esperado, Entonces veo en la aplicación web la información de la variación | EP02 |
| US05 | Parámetros de calidad | Como operador de empresa de preparación de bebidas, Quiero visualizar la temperatura y densidad Para asegurar que el proceso se mantenga en óptimas condiciones. | Escenario 01: Visualización de temperatura y densidad. Dado que el sensor de calidad está activo, Cuando reviso el dashboard en la aplicación web, Entonces veo los valores de temperatura y densidad en tiempo real | EP02 |
| US06 | Multitanque | Como jefe de planta, Quiero monitorear múltiples tanques en paralelo Para tener control integral de toda la operación. | Escenario 01: Visualización de tanques conectados. Dado que tengo varios tanques con sensores conectados, Cuando accedo al panel principal en la aplicación web, Entonces visualizo el estado de todos con un identificador único | EP02 |


## 3.2. Impact Mapping

## 3.3. Product Backlog

| #Orden | User Story ID | Título | Descripción                               | Story Points |
|-------|----------------|-------------------------------------------|---------------------------------------------------------------------------------------------------|--------------|
| 1     | US01           | XX                 | Como XX Quiero XX Para XX. | N |
| 2     | US02           | XX                 | Como XX Quiero XX Para XX. | N |


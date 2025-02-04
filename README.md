# Entrega semana 2

**Nota** La entrega se realiza sobre el repositorio `https://github.com/dparejaUniandes/ciclo8-nomonoliticas-fork-contextmapper`, por favor, tener en cuenta las instrucciones que se muestran a continuación. Para la ejecución del ContextMapper, se debe haber registrado en GitPod Classic.

En la entrega de la semana 2 se ha realizado del dominio y subdominios tanto para AS-IS como para TO-BE con ContextMapper, para estos también se identifican los vision statement con el DSL.

## Convenciones y definiciones
<img width="1553" alt="image" src="https://github.com/user-attachments/assets/cc62b500-87e4-41f8-8dd2-2200914b7dd6" />


## Event Storming AS-IS
<img width="1532" alt="image" src="https://github.com/user-attachments/assets/66d831b0-506c-4be6-9357-20207fddf78f" />

## Event Storming TO-BE
<img width="1649" alt="image" src="https://github.com/user-attachments/assets/2d4ac83d-f041-4220-818e-7374750faebd" />

Para la consulta de los event storming, se puede ingresar desde miro:
* [Enlace Miro con Events Storming](https://miro.com/app/board/uXjVLnwfFlU=/?share_link_id=150905541425)

## Ejecución del workspace con GitPod
Se ha utilizado el DSL ContextMapper, en donde se debe ingresar al presente repositorio y en la url anteponer `gitpod.io/#`, quedando de esta manera `gitpod.io/#/https://github.com/dparejaUniandes/ciclo8-nomonoliticas-fork-contextmapper`, para mayor facilidad, se pueda dar clic sobre el siguiente enlace:
> [Crear ambiente para ejecición del ContextMapper](https://gitpod.io/#/https://github.com/dparejaUniandes/ciclo8-nomonoliticas-fork-contextmapper)

## Archivos
### Código
Nos hemos basado en el workspace Demo que suministra ContextMapper, por este motivo, existen bastantes archivos en la raíz del proyecto y en otras carpetas. Para nuestro propósito, lo que debemos tener en cuenta es la ruta `src/main/cml`, acá se pueden encontrar dos archivos, uno que contiene toda la parte AS-IS y el otro archivo contiene la parte TO-BE

<img width="1112" alt="image" src="https://github.com/user-attachments/assets/7506be28-f53b-4662-8df2-c320cf703647" />

### Diagramas

**AS-IS ContextMapper Imagen -> archivo STA-AS-IS_ContextMap.png**
![image](https://github.com/user-attachments/assets/bf711fbe-95b2-457a-89f1-a52ae90a5cb8)

**TO-BE ContextMapper Imagen -> archivo STA-TO-BE_ContextMap.png**
![image](https://github.com/user-attachments/assets/108ce70e-7c15-437a-9a54-2fa3e3c2b510)

Para acceder a las imágenes y PlantUML, se debe tener en cuenta la carpeta `src-gen` ubicada en la raíz del proyecto.

Los diagramas de PlantUML se pueden identificar por los archivos que terminan en puml, estos archivos contienen el código en PlantUML el cual puede ser copiado y pegado en [editor PlantUML](https://www.planttext.com/), como se muestra a continuación

<img width="1663" alt="image" src="https://github.com/user-attachments/assets/e99be92d-d36c-4cac-803c-b793a78e0996" />

En el ejemplo se ha tomado el código del archivo `src-gen/STA-AS-IS_BC_IngestionContext.puml`, se ha pegado en el editor ubicado en la parte izquierda y luego se ha oprimido **Refresh** para ver el diagrama

## Bono
En la ruta `src/main/cml` se encuentra el archivo **bono.cml** en donde se identifican 4 historias de usuario como se puede ver a continuación, también se han identificado las entidades, pero estas se encuentra en los archivo **STA-AS-IS.cml** y **STA-TO-BE.cml** en donde se han generado los contextos, dominios y subdominios del AS-IS y el TO-BE.
<img width="799" alt="image" src="https://github.com/user-attachments/assets/5f2ef9cb-85e6-4aaa-a377-af2f28d0d853" />

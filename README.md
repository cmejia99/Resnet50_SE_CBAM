# **Resnet50 - SE -  CBAM** #
## **Diseñado por:**
* *Alba Maria Ramirez Marquinez*
    * **Código:** 2216260
* *Milton Guarin Arias* 
    * **Código:** 2210702
* *Carlos Arbey Mejia Martinez*
    * **Código:** 2210549
* *Andres Felipe Guerra Vargas* 
    * **Código:** 2211058

## **Contenido** ##
En este repositorio se podrá encontrar la documentación, fuentes y resultados llevados a cabo en la comparación de los modelos de la arquitectura RestNet 50 utilizando diferentes modelos de atención aplicados al dataset CIFAR10:

* ResNet50 original (sin módulo de atención)
* ResNet50 con módulo de atención Squeeze-Excitation
* Resnet50 con módulo de atencion CBAM

<p align="center">
<img src="ARQResNet50.png" alt="" style="height: 400px; width:600px;"/>
</P>

Validación del Heatmap de las 3 arquitecturas:

<p align="center">
<img src="img/heatmap.png"/> 
<img src="img/heatmap2.png"/> 
<img src="img/heatmap3.png"/> 
</P>

Validación del Accuracy de los modelos:
<p align="center">
<img src="img/Accuracy.png"/>
</P>

Validación de Loss de los modelos:
<p align="center">
<img src="img/Loss.png"/>
</P>

Tabla comparativa de los modelos:
<p align="center">
<img src="img/Tabla_comparativa.png"/> 
</P>

A continuación se muestra la validación de las arquitecturas en 3 diferentes imagenes de pruebas visualizando la atención con GrandCam:

* Arquitectura original.
    <p align="center">
    <img src="img/caballo1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/caballo1_RN50.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/pajaro2.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/pajaro2_RN50.png" alt="" style="height: 200px; width:300px;"/> 
    <img src="img/rana1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/rana1_RN50.png" alt="" style="height: 200px; width:300px;"/>
    </P> 
*  Squeeze Excitation
    <p align="center">
    <img src="img/caballo1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/caballo1_RN50SE.png" alt="" style="height: 200px; width:300px;">
    <img src="img/pajaro2.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/pajaro2_RN50SE.png" alt="" style="height: 200px; width:300px;"/> 
    <img src="img/rana1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/rana1_RN50SE.png" alt="" style="height: 200px; width:300px;"/> 
    </P>
*  Squeeze Excitation Adam ajustado.
    <p align="center">
    <img src="img/caballo1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/caballo1_RN50SEAdam.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/pajaro2.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/pajaro2_RN50SEAdam.png" alt="" style="height: 200px; width:300px;"/>  
    <img src="img/rana1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/rana1_RN50SEAdam.png" alt="" style="height: 200px; width:300px;"/> 
    </P>
*  CBAM
    <p align="center">
    <img src="img/caballo1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/caballo1_RN50CBAM.png" alt="" style="height: 200px; width:300px;"/> 
    <img src="img/pajaro2.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/pajaro2_RN50CBAM.png" alt="" style="height: 200px; width:300px;"/> 
    <img src="img/rana1.jpg" alt="" style="height: 200px; width:300px;"/>
    <img src="img/rana1_RN50CBAM.png" alt="" style="height: 200px; width:300px;"/>  
    </P> 

## **Links alternos al repositorio:** ##
* [Repositorio Google Drive Tarea](https://drive.google.com/file/d/1aar-eZAy8nYX8TlmvjE2uV6RvF6J5Eyz/view?usp=drive_web&authuser=0)

## **Referencias:** ##
* [ResNet](https://drive.google.com/file/d/1aar-eZAy8nYX8TlmvjE2uV6RvF6J5Eyz/view?usp=drive_web&authuser=0)
* [Squeeze - Excitation 1](https://drive.google.com/file/d/1_zvn6gjB-S0EaOxAxp7f8TYLvBq0dHP2/view?usp=drive_web&authuser=0)
* [Squeeze - Excitation 2](https://drive.google.com/file/d/1ebtN-ui9z0QIX1faMAuGBxdvkRYBHyeT/view?usp=drive_web&authuser=0)
* [CBAM / PAY ATTENTION 1](https://drive.google.com/file/d/1LRkUOcBcXL3lqRMbBzlirvWOu56eiUq6/view?usp=drive_web&authuser=0)
* [CBAM / PAY ATTENTION 2](https://drive.google.com/file/d/14aMNJp6Y-3KAsuoQzx3KUDI8cdzp0Djv/view?usp=drive_web&authuser=0)

---
{"dg-publish":true,"permalink":"/modulos-y-lecciones/motivanki-configuracion-de-luis-letona/","noteIcon":""}
---

Las siguientes configuraciones expande las posibilidades de uso para este addon. Luego de instalar Motivanki, ir a herramientas → Complementos → Motivanki → Configuración y reemplazar todo el código por las que se muestran

**Ejemplo de configuración 1: gif animado, texto y emojis**

Los gifs o imágenes de preferencia se copian de una ubicación en internet. No he probado con imágenes de la PC, podrían intentar con la ruta de acceso, si alguien lo ha conseguido probar, me avisa

```
{

"font color": "lightblue",

"font family": "Tahoma, CornerStoreJF, Snell Roundhand, Palace Script MT",

"font size": "24px",

"quote": [

"<center><img src=https://www.icegif.com/wp-content/uploads/2022/04/icegif-444.gif /><br><marquee><font size=4 face=verdana color=#1d4ed8>🏆🏆🏆🏆🏆👏👏👏👏👏 Eres un campeón ¡Tú puedes! Sigue adelante por favor... 👏👏👏👏👏🥳🥳🥳🥳🥳</font></marquee></center>"

]

}

```

![Pasted image 20240418134044.png](/img/user/ANEXOS/Pasted%20image%2020240418134044.png)

**Ejemplo de configuración 2: Google Sheets dentro de Anki**

Para que quede bien el tamaño, se debe jugar con los números de width y height e ir probando hasta que alcance el tamaño deseado. Yo uso un Google Sheets que puedo editar, tu puedes hacer lo mismo o usar Google docs o lo que desees probar

```
{

"font color": "lightblue",

"font family": "Tahoma, CornerStoreJF, Snell Roundhand, Palace Script MT",

"font size": "24px",

"quote": [

"<center><iframe width=1200 height=500 src=https://docs.google.com/spreadsheets/d/13NTuKQPHM63MTOGTcVkcA-zqD3JQQ4egPsUWuRtvYJE/edit?usp=sharing></iframe></center>"

]

}
```

![Pasted image 20240418134049.png](/img/user/ANEXOS/Pasted%20image%2020240418134049.png)
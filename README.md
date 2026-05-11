# Breath-of-Fire-2-GBA-Text-Editor
Editor de Texto para Breath of Fire 2 de GBA. (Proy. en desarrollo)



## Uso
Actualmente la herramienta se ejecuta por terminal

```
rem extraer  
BoF2Manager extract Breathesp.gba text.json bof2.gba.tbl  

rem parchar  
BoF2Manager insert Breathesp.gba text.json breathpatced.gba bof2.gba.tbl
```

- El método extraer te produce un json con: el texto, su puntero, el tamaño de linea en bytes y en caracteres.

- El método parchar te reinsertar el json con la font, pantalla de título, y las modificaciones de texto realizadas en el json.

## Créditos

- Dev de la aplicación: Angel
- Ing Inversa, font y pantalla titulo: [Bunkai](https://github.com/Bunkai9448/)
- Traducción española base: [Damniel](https://www.youtube.com/%40damnielvicioyperversion) 

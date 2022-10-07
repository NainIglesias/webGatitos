# La web de los gatitos bebe

Esta página web ha sido escrita en javascript vanilla y css

Si quieres ver la página en funcionamiento entra en
https://nainiglesias.github.io/webGatitos/


>- Algo en negrita cursiva y tachado, enlace a la wikipedia (gatos)
>- Una foto de un gato 
>- Una mencion a vuestro profe angel (kant003)
>- titulo principal y dos secundarios
>- Una lista no numerada
>- Un checklist con unas cuantas tareas marcadas y otras desmarcadas
>- Un trozo de codigo fuente escrito en algún lenguaje
>- Una tabla comparativa de diferentes tipos de razas de gatos
>- Algún emoji

# Página web de gatitos

## Explicación proyecto

Esta página creada desde **JS** y *css* ha sido diseñada luego de un ~~facil~~ exahustivo proceso de recogida de información tanto de [wikipedia](https://es.wikipedia.org/wiki/Felis_silvestris_catus) como de muchas otras páginas webs en las cuales se recogen información dada como:

- Razas de gatos
- Colores de gatos
- Tiempo de vida de un gato
- Nombres de gatos
- etc...

## Futuras implpenentaciones al proyecto

Dejo escrita una cheklist donde se marcarán como hechas las futuras versiones del proyecto para llegar a ser la mejor webs de gatos de todo el internet.

- [ ] Implementar mas fotos de gatos
- [ ] Añadir lista de gatos famosos
- [ ] Crear una base de datos para saber el arbol genealógico de tu gato
- [x] Añadir un readme.md donde aparezca la explicación del proyecto y sus futuras versiones

Los estilos de texto usados para la creación de la página web son los siguientes:

```css
.container{
display:flex;
flex-direction: row;
gap: 10px;
}
.container img{
width: 500px;
border-radius: 450px;
box-shadow: box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px, rgba(0, 0, 0, 0.3) 0px 30px 60px -30px, rgba(10, 37, 64, 0.35) 0px -2px 6px 0px inset;;
}
h2{
background: #CF3ACF;
background: linear-gradient(to right, #CF3ACF 0%, #CF1313 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
font-size: 115px;
}
```

Una de las imagenes a implementar sería :cat: :
![Foto pallascat][logo_gato]


`Tabla con algunos gatos a implementar:`

|Raza |Pelaje|Color 
|-----|-------|-----------|
|British shorthair| Si| Gris|
|Kohana|    No|    Carne|
|Maine Coon| Si| Blanco y Gris|
|Thai| Si   |   Marrón Clarito|  


Hago una mención a mi profesor Angel para que ver si me sigue en [GitHub](https://github.com/NainIglesias/webGatitos) @kant003




[logo_gato]:
https://www.cmzoo.org/wp-content/uploads/WH10-2020Pallas-Cat-480x320.jpg
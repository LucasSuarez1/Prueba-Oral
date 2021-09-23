# Prueba-Oral

<!--encabezado -->
# titulo

titulo
===

## titulo 2

titulo 2
---

### titulo 3

#### titulo 4

<!--negritas -->
**oscuro**

<!--cursiva -->
*cursiva*

<!--tachado -->
~~tachado~~

<!--Listas con html -->
<dl>
    <dt>Peliculas</dt>
    <dd>esto es una pelicula<dd>
    <dt>Series</dt>
    <dd>Serie1</dd>
</dl>

<!--Listas desordenadas -->
* Peliculas
  * esto es una pelicula
* Series
  * Serie1

<!--Listas ordenadas -->
1. Peliculas
   1. aca van las peliculas
2. Series
   1. aca van las series


<!--Tablas en html -->
<table>
<tr>
    <td>Producto</td>
    <td>Precio</td>
</tr>
<tr>
    <td>Pc</td>
    <td>1000</td>
</tr>
</tabla>

<!-- Tabla en Markdown -->

| Product   | Price         |quantity   |
| ------------- |:-------------:| :--------:|
| Laptop        | 3.33          | 2         |
| Mouse         | 10.33         | 1         |
|Pc|100|aasd|


<!-- lista to do -->
* [ ] task1
* [X] task2

<!-- salto de linea-->
<br>

<!-- Enlaces-->

[Google.com](https://github.com/LucasSuarez1/Prueba-Oral)

[Google.com](https://github.com/LucasSuarez1/Prueba-Oral "Felipe")

<!-- Imagen-->

![Google.com](https://hipertextual.com/wp-content/uploads/2021/04/whatsapp-audios-134-scaled.jpeg "wpp")

![Google.com](450_1000.jpg "wpp")

<!-- Citas-->

`Esto es una cita`

```JAVA
int minDistance(int dist[], bool sptSet[])
{

    // Initialize min value

    int min = INT_MAX, min_index;

 

    for (int v = 0; v < V; v++)

        if (sptSet[v] == false && dist[v] <= min)

            min = dist[v], min_index = v;

 

    return min_index;

}
```

 
---

> esto es una cita

> esto es otra cita

---
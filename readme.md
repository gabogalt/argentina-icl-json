# Argentina Icl JSON

El siguiente json contiene los icl publicados hasta el momento por el Banco Central de la Republica Argentina .JSON.

## Contenido

El JSON esta dividido por año de publicacion del icl. Luego esta divido por mes y cada dia con el valor correspondiente del icl. 

## Ejemplos de uso

El archivo se puede usar para consultar icl por fecha y asi poder calcular el aumento anual de alquiler en Argentina.
El JSON esta divido por año y luego por mes. Se especifica cada dia de cada mes y el valor del icl esta asociado a el dia que se consulta. Por ejemplo 
     {
        "2020" : [
            {
                "mes" : "december",
                "mesNum" : "12",
                "dates" : {
                    "2020-12-01" :	1.09,
                    "2020-12-02" :	1.10,
                    "2020-12-03" :	1.10,
                    "2020-12-04" :	1.10,
                    "2020-12-05" :	1.10,
                    "2020-12-06" :	1.10,
                }
            }
        ]
     }
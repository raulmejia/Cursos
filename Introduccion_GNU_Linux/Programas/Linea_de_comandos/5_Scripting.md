## Sed (Stream editor)

``` sed "s/algo/otra cosa/g" elnombredemiarchivo > comoquieroquesellameelresultado ```
* s = substitute  
* g = global  

``` cat frutas.txt ```  
``` lima luego sandia ahora lima luego sandia```  
``` luego lima ahora sandia luego lima ahora sandia```  

``` sed "s/lima/guanabana/g" frutas.txt > frutasconguanabanas ```  
¿Ahora que pasa si omitimos la "g" ?  
``` sed "s/lima/guanabana/" frutas.txt > frutasconguanabana ```

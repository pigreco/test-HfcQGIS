## Gruppo `Arrays` - solo DB (es:SpatiaLite, PostGIS)

Questo gruppo contiene funzioni espressione per la creazione e la manipolazione di array (noti anche come strutture dati ad elenco). L'ordine dei valori all'interno dell'array è importante, al contrario della struttura dati 'a mappa' ([gruppo Maps](../maps)), in cui l'ordine delle coppie chiave-valore è irrilevante e i valori vengono identificati dalle loro chiavi.

| Funzione  | Descrizione|Plugin
|----------:|:-----------|--------
|[array](funzioni/array.md)|Restituisce un array contenente tutti i valori passati come parametro|
|[array_append](funzioni/array_append.md)|Restituisce un array con il valore passato aggiunto alla fine|
|[array_avg](funzioni/array_avg.md)|Calcola il valore medio di un array|ArrayPlus
|[array_cat](funzioni/array_cat.md)|Restituisce un array contenente tutti gli arrays passati concatenati|
|[array_contains](funzioni/array_contains.md)|Restituisce true se un array contiene il valore specificato|
|[array_count](funzioni/array_count.md)|Conta un dato valore in un array|ArrayPlus
|[array_distinct](funzioni/array_distinct.md)|Restituisce un array contenente valori distinti dell'array dato|
|[array_find](funzioni/array_find.md)|Restituisce l'indice di un valore all'interno di un array|
|[array_first](funzioni/array_first.md)|Restituisce il primo valore di un array|
|[array_get](funzioni/array_get.md)|Restituisce il valore ennesimo di un array|
|[array_insert](funzioni/array_insert.md)|Restituisce un array con il valore passato aggiunto nella posizione indicata|
|[array_lambda](funzioni/array_lambda.md)|Applica una funzione personalizzata a ciascun elemento (x)|ArrayPlus
|[array_intersect](funzioni/array_intersect.md)|Restituisce vero se almeno un elemento dell'array1 esiste in array2|
|[array_last](funzioni/array_last.md)|Restituisce l'ultimo valore di un array|
|[array_length](funzioni/array_length.md)|Restituisce il numero di elementi di un array|
|[array_majority](funzioni/array_majority.md)|Restituisce il valore più comune. Restituisce un valore arbitrario se ex-equo|ArrayPlus
|[array_minority](funzioni/array_minority.md)|Restituisce il valore più comune. Restituisce un valore arbitrario se ex-equo|ArrayPlus
|[array_max](funzioni/array_max.md)|Restituisce il valore massimo di un array|ArrayPlus
|[array_min](funzioni/array_min.md)|Restituisce il valore minimo di un array|ArrayPlus
|[array_prepend](funzioni/array_prepend.md)|Restituisce un array con il valore dato aggiunto all'inizio|
|[array_prioritize](funzioni/array_prioritize.md)|Ordina un array rispetto ad un altro QGIS >= 3.2|ArrayPlus
|[array_remove_all](funzioni/array_remove_all.md)|Restituisce un array con tutti gli elementi del valore passato rimossi|
|[array_remove_at](funzioni/array_remove_at.md)|Restituisce un array con l'indice passato rimosso|
|[array_replace](funzioni/array_replace.md)|Ordina i valori in ordine crescente (usa _array_reverse_ per desc)|ArrayPlus
|[array_reverse](funzioni/array_reverse.md)|Restituisce l'array dato con valori dell'array in ordine inverso|
|[array_slice](funzioni/array_slice.md)|Restituisce una porzione dell'array|
|[array_sort](funzioni/array_sort.md)|Ordina i valori in ordine crescente (usa _array_reverse_ per desc)|ArrayPlus
|[array_sum](funzioni/array_sum.md)|Calcola la somma dei valori|ArrayPlus
|[array_to_string](funzioni/array_to_string.md)|Concatena gli elementi di un array in una stringa separata da un delimitatore usando una stringa opzionale per valori mancanti|
|[regexp_matches](funzioni/regexp_matches.md)|Restituisce un array di tutte le stringhe catturate dai gruppo, nell'ordine che i gruppi stessi compaiono con l'espressione regolare fornita con una stringa|
|[string_to_array](funzioni/string_to_array.md)|Divide la stringa in un array usando il delimitatore fornito e la stringa opzionale per valori mancanti|


![](/img/arrays/gruppo_arrays1.png)

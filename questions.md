## How many documents do you have?

len(df): 1977


## Is the dataset balanced across the two classes?

category
sci.med      990
sci.space    987
Name: count, dtype: int64
Fördelningen mellan klasserna analyseras genom att räkna antalet dokument per kategori, vilket visar att datasetet är relativt balanserat mellan de två klasserna.

## Print 2–3 documents per class. Just read them. What do you notice — vocabulary differences, length, formatting noise, anything?

sci.med: innehåller medicinska ord som “disease”, “patients” och “treatment”.
sci.space: innehåller ord kopplade till rymden som “spacecraft”, “mission” och “orbit”. texterna är ganska ostrukturerade men går ändå att sätta in i respektive klass

# \# Analiza calității și a prețurilor unui catalog fictiv

# 

# Proiect realizat în cadrul cursului \*\*AI-Powered Data Analysis: A Practical Introduction\*\*. Analiza folosește Python, pandas și Jupyter pentru a verifica datele și a explora prețurile dintr-un catalog simulat.

# 

# \## Întrebări

# 

# \- Cât de complete și consecvente sunt înregistrările?

# \- Cum variază prețurile între categorii?

# \- Există prețuri atipice în raport cu propria categorie?

# 

# \## Fișiere

# 

# \- `analiza\_catalog\_produse.ipynb` — pașii analizei, verificările și vizualizările.

# \- `catalog\_1000\_produse\_simulat.xlsx` — catalogul simulat și dicționarul de date.

# 

# \## Metode

# 

# Am verificat valorile lipsă și duplicate, statusurile de calitate, prețurile, moneda și cifra de control a codurilor EAN simulate. Am comparat prețurile pe categorii folosind mediana și boxploturi și am aplicat regula IQR pentru a semnala valori potențial atipice.

# 

# \## Rezultate principale

# 

# \- 1.000 de produse analizate; nu au fost găsite valori lipsă sau ID-uri duplicate.

# \- 59 de produse (5,9%) sunt marcate în fișier pentru verificare.

# \- Laptop are cea mai mare mediană a prețurilor (6.349 lei), iar Iluminat cea mai mică (306,5 lei).

# \- Regula IQR nu a semnalat prețuri atipice în interiorul categoriilor.

# 

# \## Cum rulezi notebookul

# 

# Păstrează notebookul și fișierul Excel în același folder. Deschide notebookul în Jupyter și rulează celulele de sus în jos.

# 

# Pachete necesare: `pandas`, `matplotlib` și `openpyxl`.

# 

# \## Limitări

# 

# Datele și prețurile sunt fictive. Codurile EAN sunt simulate și nu confirmă alocarea oficială. Catalogul nu conține vânzări sau date de piață; rezultatele descriu doar setul de date analizat.

# 

# AI-ul a fost folosit ca sprijin pentru structurarea analizei, explicații și cod. Calculele au fost rulate în Python și verificate în notebook.


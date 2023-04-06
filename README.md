# SecventaCool
Pentru acest proiect am avut de realizat un program care analizeza o secventa de numere introduse de la tastatura si arata daca numerele din secventa sunt distincte ,iar daca acestea sunt distincte ordoneaza numerele din secventa incat sa obtinem cea mai mare valoare care se poate forma prin rearanjarea numerelor,dar daca secventa nu are doar numere distincte programul va afisa doar numerele distince din secventa.

Cerinta:
Se consideră un șir A format din N elemente naturale nenule. 
Numim secvență de lungime K a șirului A orice succesiune de elemente consecutive din șir de forma Ai, Ai+1, ..., Ai+K-1.
O secvență o numim secvență cool dacă elementele care o compun sunt distincte și pot fi rearanjate astfel încât să alcătuiască o secvență continuă de numere consecutive. 
De exemplu, considerând șirul 
A = (3, 1, 6, 8, 4, 5, 6, 7, 4, 3, 4), atunci secvența (8, 4, 5, 6, 7) este o secvență cool deoarece conține elemente distincte ce pot fi rearanjate astfel încât să alcătuiască șirul de numere consecutive 4, 5, 6, 7, 8, pe când secvențele (4, 3, 4), (6, 7, 4, 3) nu sunt considerate secvențe cool.
Cerință:
    Pentru o valoare dată K să se verifice dacă secvența A1, A2 ... AK este secvență cool. 
    Dacă secvența este cool, atunci se va afișa cea mai mare valoare ce aparține secvenței. 
    Dacă secvența nu este cool, atunci se va afișa numărul elementelor distincte din secvența 
A1, A2, ..., AK, adică numărul elementelor care apar o singură dată.
Date de intrare:
    Se citesc N și K de la tastatură care vor determina numărul de elemente din sir respectiv lungimea secvenței cool de verificat.
Exemple:
INPUT:
7 4
6 4 5 7 8 3 5
OUTPUT: 
7
Secvența 6 4 5 7 este cool.
Valoarea maximă din secvență este 7
INPUT:
7 6
6 4 5 7 5 4 3
OUTPUT:
2
Secvența 6 4 5 7 5 4 nu este secvență cool. Numărul valorilor distincte din secvență este 2. Valorile distincte sunt: 6, 7

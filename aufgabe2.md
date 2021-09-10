## 2. Datentypen, Operatoren und Variablen

### Recherche- und Theoriefragen

1. Was ist der Unterschied zwischen ” == ” und ” === “ ? 
2. Wozu dient in JS das Semikolon (;) ?


### Praktische Coding-Aufgaben

1. Welche Ausgaben erhälst du? Überlege erst und probiere es anschließend aus. Schreibe das Ergebnis neben die Aufgaben

```
var var1 = 5.0;
var var2 = var1 + 2;
var1 = 6;
console.log(var1);                                   //Output:
console.log(var2);                                   //Output:
console.log(var1 + var2);                            //Output:
var2 = "Hallo";
console.log(var1 + var2);                            //Output:
console.log(var1 , var2);                            //Output:
console.log(11 % 3);                                 //Output:

var myString = "hello";
var helloWorld = myString + " " + "world";
console.log(helloWorld);                             //Output:
```



2. Deklariere eine Variable namens `name` und weise ihr einen String als Wert zu. Erstelle als nächstes eine zweite Variable namens `currentYear`, die als Wert das aktuelle Jahr zugewiesen bekommt. Weise einer dritten Variable namens `birthYear` dein Geburtsjahr zu. Als letztes deklariere eine Variable namens `age` und berechne dein Alter mit Hilfe der vorher erstellten Variablen `currentYear` und `birthYear`.




3. Welche Ausgaben erhälst du? Schreibe sie neben die Aufgaben

``` 
var a = true; 
var b = false;

!a                  // Output: 
a && b              // Output:
a || b              // Output:
9 >= 7 && 5 < 3     // Output:
2 != 2              // Output:
"a" == "a"          // Output:
"2" == 2            // Output:
"2" === 2           // Output:
```

***
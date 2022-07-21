<!--- Exemple Headings -->

# exemple de títol H1

exemple de títol H1
=

## exemple de títol H2

exemple de títol H2
-

### exemple de títol H3

#### exemple de títol H4

##### exemple de títol H5

###### exemple de títol H6

<!--- italica -->

Aquesta paraula en _italica_

<!--- strong -->

Aquesta paraula en **negreta**

<!--- strikethrough -->

Aquesta paraula en ~~ratllada~~

<!--- ul -->

- primer
  - primer primer
* segon
  * segon primer
+ tercer
  + tercer primer

- primer
    - primer primer
    - segon primer
        - segon primer   
        - segon segon
            - tercer primer   


<!--- ol -->

1. primer
   1. primer primer
   1. segon primer
1. segon
1. tercer

<!--- links -->

[imago.cat](https://www.imago.cat)

[imago.cat](https://www.imago.cat "web personal")

<!--- cita -->

> "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."



`console.log("hola món")`


#### javascript
```javascript
<script>

function lletra(){
   	var v_dni = document.getElementById('dni');
   	var lletres = ['T','R','W','A','G','M','Y','F','P','D','X','B','N','J','Z','S','Q','V','H','L','C','K','E'];
    var numeroDni = v_dni.value % 23;
    var lletraDni = lletres[numeroDni];

    document.getElementById("lletra").value = lletraDni;

}

</script>
```

#### HTML
```html
<label for="dni2">Escriu aquí el teu NIE:</label><br><br>
<input type="text" id="lletraPrimera" name="lletraPrimera2" size="1">
<input type="text" id="dni2" name="dni2" placeholder="NIE" size="8">
<input type="button" value="Calcular lletra" class="colorButton" onclick="lletra2()">
<input type="text" id="lletra2" name="lletra2" size="1"><br>
```

#### CSS
``` CSS
* {
    font-family: monospace;
    margin: 0px;
}

body {
    margin: 20px;
    margin-top: 40px;
    background-color: whitesmoke;
}

p{
    margin-top: 10px;
}
```

|exx4tx             |ihnuvn              |ytbybyub            |
|-------------------|--------------------|--------------------|
|text de la columa 1|text de la columna 2|text de la columna 3|
|segon text 1       |segon text 2        |segon text 3        |
|tercer text 1      |tercer text 2       |tercer text 3       |
|quart text 1       |quart text 2        |quart text 3        |

---
___
***

<!--- imatges -->
![imatge del jo](face2.png "el guapus")



<!--- Regles específiques de github-->

* [x] Task 1
* [] Task 2
* [] Task 3
* [x] Task 4
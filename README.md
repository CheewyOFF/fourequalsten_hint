# 4=10's Solution Generator

***by Cheewy***

## Description : 

This tiny program in Python allows you to quickly and simply calculate every possible solutions to the famous *4=10* game.</br>
I had a lot of fun developping it, I hope you will enjoy it.</br>

*Note : The code don't have comments, but if you want some, just send me an email and I will do it.*

## DISCLAIMER BEFORE USING IT

*Use this program sparingly, or only when you are **REALLY** stuck and you have no more daily solution left.*</br>
*Using this program too much will ruin your entire game experience, and will be very insulting to the game developpers.*</br>
*I am **NOT** responsible for any bad game experience.*</br>

## Installation :

**1. Use pip to install the package**

For Unix/macOS :
```
python3 -m pip install fourequalsten_hint
```
For Windows :
```
py -m pip install fourequalsten_hint
```
**2. Import the package in your program</br>**

Code to write down in your file *before using the commands of the package* :</br>
```
import fourequalsten_hint as feth
```

## Utilisation Guide :

**If you just want the answers :**

1. Create a python file anywhere on your computer (ex: ```test.py```)
2. In this file, write down the following code :
```
import fourequalsten_hint as feth
feth.fancy_solve()
```
3. Execute the program and follow the instructions in the terminal</br></br>

**If you want to use the functions in your program :**

```
feth.solve("<THE DIGITS>","<THE BANNED OPERATORS>",<TYPE OF RETURN>)
```

*Note : Documentation of the functions are right underneath*

## Documentation
- ```feth.solve("<THE DIGITS>","<THE BANNED OPERATORS>",<TYPE OF RETURN>)```</br></br>
  The ```solve()``` function takes 3 parameters :
    - 1rst : String made of 4 digits (the ones in the enigma)</br>
      *Ex :* ```"1234"```
    - 2nd : String made of the banned operators</br>
        Working chars :
        - '+' for plus
        - '-' for minus
        - '*' for multiplication
        - '/' for division
        - Empty string for none : ""
      *Ex :* ```"+"```, ```"-+"```, ```""```
    - 3rd : 0 or 1 depending of the informations you want in return</br>
        - 0 : Returns one possible solution in the form of a string</br>
          *Ex :* ```"(1+2+3)+4"```</br>
        - 1 : Returns every possible solutions in the form of a list of strings</br>
          *Ex :* ```["(1+2+3)+4", ... , "4+3+2+1"]```
      
  *Note : If there's no result, the function will return an empty list*
  
- ```feth.fancy_solve()```</br>
  The ```fancy_solve()``` function takes no parameters, and will return nothing.</br>
  It is made of multiple affordable inputs, prints and os.clear to give to the user a casual and simple use of the program.
  
## License

<a href="https://github.com/CheewyOFF/fourequalsten_hint/blob/main/LICENSE">MIT License</a>

## Credits :

### Fourequalsten_hint

Developper : Cheewy</br>
Email : cheewy.perso@gmail.com

### 4=10

Developper : Sveinn Steinarsson</br>
Website : fourequalsten.app</br>
Email : fourequalsten@fourequalsten.app</br>
Youtube Channel : svenstone</br>

Download game on Google Play Store : <a href="https://play.google.com/store/apps/details?id=app.fourequalsten.fourequalsten_app&hl=en_US&gl=US" target="_blank">Click here</a></br>
Download game on Apple Play Store : <a href="https://apps.apple.com/us/app/4-10/id1609871477" target="_blank">Click here</a>

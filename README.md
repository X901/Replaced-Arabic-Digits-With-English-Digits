# Replaced-Arabic-Digits-With-English-Digits

This project will help you fixed crash when entring Arabic/Hindi numbers 
like **١,٢,٣,٤,٥,٦,٧,٨,٩,٠**

It will convert it to english numbers
**1,2,3,4,5,6,7,8,9,0**

without changing user interface

so user will see **١**
but in the code it will converted to **1**

## What you need to do ?
is copying and pasting `ReplacedArabicDigitsWithEnglish.swift` to your project

and then just add `.replacedArabicDigitsWithEnglish`

fox example

`label.text = "١"`

make it like this

`label.text = "١".replacedArabicDigitsWithEnglish`

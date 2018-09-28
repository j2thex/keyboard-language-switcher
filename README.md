# keyboard-language-switcher

## What is this?
This is an Alfred Workflow script, written by Jeffrey Smith 2016, which uses apple script language to convert language of selected text. Similar to what Punto Switcher does, but it's russian and can't be  trusted.

Currently it supports Russian to English and English to Russian conversion.

The script switches the language after conversion, so you can continue typing in the correct language. 
It also restores your clipboard to previous state after conversion. 

## How to install?
Download the .workflow file and double click to add it to Alfred. 
The Workflow uses Alt + Shift + Z hotkey to convert. 

My flow is like this: 
1) I start typing something
2) I realize I'm typing in the worng language
3) I press ALT + SHIFT + LEFT to select the word I typed worng 
4) I press ALT + SHIFT + Z to convert 

You can download the .scpt file to see how the script works in applescript and tune it to your liking. 

## Ver 0.2
Capital letters now converted to capital letters
Clipboard state is restored

## Known bugs
Can't convert multiple languages in selection

You are welcome to contribute.
J.S.
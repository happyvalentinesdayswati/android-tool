# android-tool
This is a script whichh can help you in Android development practices.

## Installation Guide

You can install it using 

		sudo pip install android-tool
   
   
or you can downoad from https://pypi.python.org/pypi?:action=display&name=android-tool&version=1.1.2

## How to use

1)you can import it using 

			from androidtool import android_tool

2)Right now only one feature is implemted.If you have strings.xml filled with english words and want to localize it to some other language, just insert the csv file, which has the translation, from English to whichever desired language.original file should contain the xml file which you want to parse.

			localizeStringsXml(originalFile,csvFile,finalFile)
            
3)This stores the key-value pair from xml file and pairs that key to the translation of that value from csv file.Final file can have any name, it will be generated with xml syntax.

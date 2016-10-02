# DJBTool version 1.01
Web URL: http://forum.xda-developers.com/showthread.php?t=3455067

![alt tag](https://github.com/djb77/windows_scripts/raw/djbtool-win/android/djbtool-win/djbtool.gif?raw=true?raw=true)

Inspired by APKMultiTool (created by raziel23x / XDA)

Created by djb77 / XDA (some portions from APKMultiTool by raziel23x / XDA)

Build Date: 3rd October 2016

Using APKTool 2.2.0 and 7-Zip 16.03

## REQUIREMENTS
- Windows Operating System (Windows 7 or newer)
- Java JDK 8

## WHAT DOES THIS PROGRAM DO?
- Decompile/Compile APK files (Manually or Automatic Batch)
- Decompile/Compile JAR files (Manually or Automatic Batch)
- Sign APK/JAR/ZIP files (Automatic Batch)

## QUICK INSTRUCTIONS
- Load your framework-res.apk, twframework-res.apk, and 
  SystemUI.apk into the "framework" folder, then select 
  option 5 in the main menu to install the framework.
  
- Put the APK / JAR files you want to decompile into the 
  "files_original" folder. You can either decompile them one
  at a time with option 1, or decompile the whole lot at
  once with option 2.
  
- To compile your APK / JAR files, you can select option 3
   to choose which file you wish to compile, or you can 
   select option 4 which will compile all the decompiled
   APK / JAR files. The orignal signature files are inserted
   back into the new files. 
   
   NOTE: YOU WILL NEED TO RE-SIGN THE FILES IF YOU HAVE
   CHANGED THE ANDROIDMANIFEST.XML FILE[
   
- Use option 6 to sign your files, it will also let you copy
  over any newly compiled APK / JAR files, and also has the
  support to sign ZIP files as well.

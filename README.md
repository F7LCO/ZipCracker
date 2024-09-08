<div align="center">
  <img src="Images/ZipCracker.jpg" alt="Zip Cracker Image" style="border: 17px solid; border-radius: 15px;"/>
</div>

# About ZipCracker
This is open source zip password cracker. It brute force's the zip to reveal its password, to brute force it must need a valid and password protected zip file and also a password list. It has its own password list containing 999999 passwords.

## Used Dependencies
DDAnimatoo for change screen animation.
`com.github.michelelacorte:DDAnimatoo:1.0.0`<br>
Zip4j for extracting the zip file.
`net.lingala.zip4j:zip4j:2.11.5`

## Screenshots

<p align="center">
  <img src="Images/Screenshot_2024-09-08-15-07-40-488_com.FALCO.ZipCracker.jpg" width="45%" />
  <img src="Images/Screenshot_2024-09-08-15-06-03-504_com.FALCO.ZipCracker.jpg" width="45%" />
</p>

<p align="center">
  <img src="Images/Screenshot_2024-09-08-15-04-56-018_com.FALCO.ZipCracker.jpg" width="45%" />
  <img src="Images/Screenshot_2024-09-08-15-03-58-195_com.FALCO.ZipCracker.jpg" width="45%" />
</p>

## Does it works
Yes it 100% works. If the zip password is in the password list then it will detect the password and show it in yhe screen.

## Bugs
There are some minor bugs that will be solved in next update. I have managed to detect on bug and i am constantly trying to fix it, the bug is
```error
android.view.ViewRootImpl$CalledFromWrongThreadException: Only The original thread that created a view hierarchy can touch its views.
```

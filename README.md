# Bújócska időzítő

Modern, teljes képernyős Windows-játékmester alkalmazás visszaszámlálóval,
zenei lejátszási listával és az életben lévő játékosok számlálásával.

## Fő funkciók

- TM Pizza-stílusú fekete, bordó és narancs felület;
- lekerekített, áttetsző panelek és animált háttér;
- óra, perc, másodperc és induló játékosszám beállítása;
- több MP3, WAV vagy WMA zene, átrendezés és véletlen sorrend;
- animált három másodperces játékindítás;
- teljes képernyős játéknézet;
- a játékképernyőn csak az idő és az életben lévő játékosok láthatók;
- külön szünet- és eredményképernyő;
- a beállítások automatikus megjegyzése.

## Irányítás játék közben

| Billentyű | Művelet |
|---|---|
| `SPACE` | Egy játékos kiesett |
| `Backspace` | Az utolsó kiesés visszavonása |
| `P` | Szünet / folytatás, a zenével együtt |
| `Esc` | Játék leállítása és vissza a vezérlőpulthoz |
| `Enter` | Eredményképernyőről vissza a vezérlőpulthoz |

## EXE készítése Windowson

1. Telepítsd a Python 3-at a [python.org](https://www.python.org/downloads/)
   oldalról. Telepítéskor pipáld be az **Add Python to PATH** lehetőséget.
2. Csomagold ki ezt a ZIP-et.
3. Kattints duplán a `BUILD_EXE.bat` fájlra.
4. Az elkészült program itt lesz:
   `dist\BujocskaIdozito.exe`

Az elkészült EXE másik Windows 10/11-es gépre is átmásolható. A felülethez a
Windows beépített WebView2 megjelenítője szükséges, amely a naprakész Windows
10/11 rendszereken általában már telepítve van.

## Futtatás EXE építése nélkül

Kattints duplán a `RUN.bat` fájlra. Első futtatáskor a fájl telepíti a szükséges
Python-csomagokat.

## Megjegyzés a zenéhez

A zenelejátszás a Windows saját médiarendszerét használja. Az MP3 és WAV
formátum a legbiztosabb. A zenék nem kerülnek bele az EXE-be; a program a
kiválasztott fájlok eredeti helyét jegyzi meg.

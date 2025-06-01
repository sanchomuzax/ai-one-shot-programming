# Space Invaders Remastered - Játék Dokumentáció

## Áttekintés
A Space Invaders Remastered egy modern újragondolása a klasszikus űrhajós lövöldözős játéknak. A játékban az űrhajóddal védekezel az idegen invázió ellen, miközben pontokat gyűjtesz és egyre nehezebb szinteken haladsz előre.

## Főbb Jellemzők
- 🚀 Modern, neon-stílusú grafikák és vizuális effektek
- 🌌 Dinamikus háttér csillagmező parallax hatással
- 👾 Több szintű nehézségi rendszer (a játék haladtával nehezedik)
- 💥 Részecske-effektek robbanásokhoz
- 🎮 Érintőképernyős támogatás mobil eszközökhöz
- 🎹 Billentyűzet és érintővezérlés
- 🔊 Hanghatások és háttérzene

## Játékmenet
1. **Cél**: Lődd le az összes idegen inváziót mielőtt elérik a Földet!
2. **Pontozás**: Minden lelőtt idegen után pontokat kapsz (magasabban lévő idegenek többet érnek)
3. **Életek**: 3 életed van, minden találat után egyet veszítesz
4. **Szintek**: Minden sikeres invázió visszaverése után nehezebb szintre kerülsz

## Vezérlés
### Asztali számítógép:
- **Balra mozgás**: Bal nyíl vagy A billentyű
- **Jobbra mozgás**: Jobb nyíl vagy D billentyű
- **Lövés**: Szókör

### Mobil eszköz:
- **Balra mozgás**: Érintsd meg a képernyő bal alsó részét
- **Jobbra mozgás**: Érintsd meg a képernyő jobb alsó részét
- **Lövés**: Nyomd meg a FIRE gombot

## Technikai Részletek
- **Fejlesztőeszköz**: HTML5, CSS3, JavaScript
- **Grafika**: Canvas API
- **Hang**: Web Audio API
- **Reszponzív design**: Minden képernyőmérethez alkalmazkodik
- **Könyvtárak**: Orbitron betűtípus Google Fonts-ról

## Fejlesztési Jegyzetek
- A játék teljes mértékben egyetlen HTML fájlban található
- A kód moduláris szerkezetű, könnyen bővíthető
- A játékállapotot egy központi `game` objektum kezeli
- Az animációk `requestAnimationFrame` API-val készültek

## Telepítés és Futtatás
1. Töltsd le a `DeepSeek R1 0528 - Space Invaders Remastered.html` fájlt
2. Nyisd meg a fájlt bármely modern webböngészőben (Chrome, Firefox, Edge)
3. Kattints a "START MISSION" gombra a játék indításához

## Licenc
A játék ingyenesen használható oktatási és szórakoztatási célokra. A forráskód módosítható és terjeszthető a MIT licenc feltételei szerint.

![image](https://raw.githubusercontent.com/sanchomuzax/ai-one-shot-programming/refs/heads/main/DeepSeek%20R1%200528%20-%20Space%20Invaders%20Remastered.png)

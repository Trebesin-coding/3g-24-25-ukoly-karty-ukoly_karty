# Karetní úkoly

-   Úkoly níže jsou řazeny podle obtížnosti (obtížnější úkoly budou hodnoceny výrazně vyšší vahou)

-   Odevzdávejte do příslušných složek včetně všech obrázků

-   Není potřeba dodržovat grafickou úpravu zadání 1:1. Klidně vymyslete vlastní barevný styl karet/stránek

-   Odevzdávejte kdykoliv, následující úkoly nemají pevný termín odevzdání (ale je potřeba někde zmínit, že jste úkol odevzdali)

-   Pokud se na něčem zaseknete, neváhejte se přijít poradit

-   Pokud se nebude dařit vytvořit verzi ze zadání, zkuste třeba jednodušší verzi nebo naopak, pokud jsou úkoly moc jednoduché, zkuste vytvořit vylepšenou verzi

-   Tento repozitář obsahuje automatický pull request - tento pull request nemergujte, slouží pro zpětnou vazbu a komunikaci k vašemu kódu

### Video materiál

Zkoukněte následující video, jak vytvořit efekt otáčené karty v CSS - [card flip](https://www.youtube.com/watch?v=OV8MVmtgmoY)

Popřípadě na [W3 schools](https://www.w3schools.com/howto/howto_css_flip_card.asp) je také návod na kýžený efekt, video výše jej však lépe vysvětluje.

## 1. Náhodná barva

_Obtížnost 1/5_

-   Na stránce je karta. Po kliku na ní se náhodně vygeneruje jedna z herních barev.

_Hint: Může se hodit následující array: `const suits = ["♠", "♥", "♦", "♣"]`_

![random_suit](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/6ee0258a-bc0e-4174-a9fd-2c9ea299e925)

## 2. Skořápky

_Obtížnost 3/5_

Skořápky a jejich karetní podoba Three-card Monte jsou známou podvodnickou hrou, kterou nelze vyhrát. Vytvořte její webovou verzi.

-   Karty začínájí odhalené, uživatel má možnost zapamatovat si, kde je eso
-   Po kliku na tlačítko začíná hra, karty se otočí rubem
-   Po kliku na jakoukoliv kartu se karty opět otočí lícem, přičemž uživatel nikdy nevyhraje
-   Karta na kterou uživatel klikl bude vždy nevýherní karta (v ukázce 2♣) a eso se vždy bude nacházet na jiné pozici, než uživatel kliknul
-   Tlačítko umožní hrát znovu
-   Na stránce je počítadlo proher

[Nepohyblivý obrázek zadání](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/cf77cd0f-3b24-4fa7-a5f5-e98e1ac83d14)

![monte-gif](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/3898d491-29d7-4d44-9771-c971141d4aaa)

### 3. Nejhorší kouzelník na světě

_Obtížnost 3/5_

Vytvořte stránku s nejhorším kouzelníkem na světě.

_Hint: může se hodit jeden array na barvy a jeden na hodnoty karet_

Ve složce [nejhorsi_kouzelnik](/nejhorsi_kouzelnik) naleznete obrázky a font ze zadání

-   Kouzelník vyzve uživatele, ať zvolí kartu, kterou se následně pokusí uhodnout, pomocí ~~mocné magie~~ náhody
-   Kouzelník zvolí náhodnou kartu
-   Uživatel zvolí, jestli chce dát kouzelníkovi další šanci na uhodnutí karty
-   Maximum 3 pokusy
-   Kouzelníkova nálada upadá s počtem neuhodnutých pokusů
-   Po kliknutí na tlačítko po konci hry se spustí oslavný/smutný gif

Nepohyblivé obrázky z různých fází hry: [obr1](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/c4966bfa-1ec1-4ab3-baae-7a6eb785e488) [obr2](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/6b4c2f0b-e66a-4d22-9d89-05b156b38d7e) [obr3](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/e7f0a882-b7b5-45a1-bf40-9301e44468f5) [obr4](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/5727e8b9-92b5-47a6-9974-6341d3312d5f) [obr5](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/57cc31ad-525a-45a5-af72-d8512bfc4d84)

[Alternativní gif - vítězství](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/39185363-0d6e-46dd-9eec-119ca7ca87df)

![worst_mag_lose](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/1179e6a9-6690-4c1b-a40a-144b449ac14e)

## 4. Pexeso

### 4a Pexeso pro jednoho hráče

_Obtížnost 4/5_

Vytvořte pexeso pro jednoho hráče

_Hint: při větším počtu karet se může hodit vytváření zadní a přední strany karty pomocí pseudo elementů `::before` a `::after` - není nutné, ale umožní to přehlednější HTML kód_

-   Je to pexeso

![1 player pexeso](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/3ae57dcd-9997-4f04-ab0f-2661b911e92a)

### 4b Pexeso pro dva hráče

_Obtížnost 5/5_

Vytvořte pexeso pro dva hráče

-   Je to pexeso
-   Střídají se dva hráči
-   Na stránce je počítadlo skóre pro dva hráče
-   Stránka oznámí výsledek zápasu
-   Možné vylepšení: ukazatel, který hráč je na řadě

![2 player pexeso](https://github.com/JS-Trebesin/ukoly_karty/assets/84028625/6945c544-ac83-432f-b816-7f87efe8d83d)

### 4c Pexeso proti počítači

_Obtížnost 500/5_

Vytvořte pexeso, kde hraje jeden hráč proti počítači

-   Je to pexeso
-   Střídají se dva hráči
-   Jeden z hráčů je počítač
-   Je potřeba vytvořit AI, v tomto případě myšleno logiku, jak počítač postupuje - jak otáčí karty, jestli si pamatuje odehrané karty, atd.
-   Možnost vícero obtížnost - AI s perfektní pamětí vs AI která otáčí karty úplně náhodně


## 5. Jiná karetní hra/stránka

Vytvořte jinou/vlastní karetní hru nebo stránku

*Obtížnost ?/5*

- Větší bere? 
- Blackjack? 
- Vlastní originální stránka

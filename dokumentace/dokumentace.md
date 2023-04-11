# Technická dokumentace vybraných metod pro analýzu časových řad

Tento dokument obsahuje technickou dokumentaci vybraných metod pro analýzu časových řad.

## Co se zde dočtu

Metody analýzy jsou rozděleny do samostatných kapitol, kde každá kapitola obsahuje dané sekce:

- **Vedlejší názvy**
    - Sekce obsahuje seznam názvů, označení a zkratek metody.
- **Možné použití**
    - Sekce obsahuje primární (viz [Informační ikony](#informační-ikony)) informační ikony, popisující možné využití metody.
- **Koncept**
    - Sekce obsahuje podrobný popis metody - na jakém principu metoda funguje. Součástí této sekce jsou také vzorce pro výpočet metody či doplňujících funkcí.
- **Parametry**
    - Sekce obsahuje podrobný popis parametrů metody. 
- **Podmínky použití**
    - Sekce obsahuje popis charakteristiky, kterou musí zpracovávaná data splňovat, aby bylo použití metody co nejfektivnější.
- **Použití**
    - Pro každé 'možné použití' je připraven názorný příklad výpočtu a interpretace výsledků. 
    - Obsahuje následující sekce:
        - Podmínky použití
            - Sekce obsahuje popis charakteristiky, kterou musí zpracovávaná data splňovat.
        - ...
        - ...

_obrázek příkladu kapitoly (metody) s vyznačenými sekcemi_

### Informační ikony

- **Typ metody**
    - Primární ikony označují význam použití metody. Primární ikony jsou barevně rozlišené pro rychlou orientaci v textu.
    - Seznam:
        - :small_red_triangle: označuje metodu pro detekci anomálií v datech
        - :large_blue_circle: označuje metodu pro předzpracování dat
        - :large_orange_diamond: označuje metodu pro shlukování dat

- **Doplňující informace**
    - Sekundární ikony označují doplňující informace (varování, tip). Sekundarní ikony nejsou barevně rozlišené
    - Seznam:
        - :grey_exclamation: označuje varování
        - :grey_question: označuje tip

## Reference použití metod

- **Detekce anomálií**
    - Metoda použití mezikvartilového rozptylu
    - Metoda použití z-skóre
    - Symbolic aggregate approximation
- **Předzpracování dat**
    - Symbolic aggregate approximation
    - Dynamic time warping
    - Klouzavý průměr
- **Shlukování dat**
    - K-means clustering
    - Dynamic time warping
    - Symbolic aggregate approximation

## Metody

## Reference

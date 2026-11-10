## Role 1: Vykreslování mapy a ukazatelů
- Vytvoř si soubor *mapa_test.py*.

- Napiš kód, který pomocí knihoven folium a streamlit-folium zobrazí mapu vycentrovanou na Olomouc.

- Vytvoř testovací list s vymyšlenými nebezpečnými místy od Role 4.

- Napiš for cyklus, který projde tento seznam a přidá na mapu folium.Marker s červenou ikonou a popiskem.

*streamlit run nazev_souboru.py*

## Role 2: Databáze, její napojení a funkce k přidávání do ní, AI implementace
- Vytvoř si soubor *data_test.py*.

- Vytvoř jednoduchý formulář pomocí st.form: textové pole (st.text_input) pro název, políčko pro popis problému a tlačítko st.form_submit_button.

- Napiš funkci uloz_data(nazev, popis), která vezme tento text a přidá ho listu v Pythonu

## Role 3: Navigace, vyhýbání se nebezpečným místům
- Vytvoř si soubor *navigace_test.py*.

- Najdi si v dokumentaci OpenRouteService, jak vykreslit trasu pro chodce z Hejčína na hlavní nádraží.

- Vytvoř skrz st.button tlačítko _Najdi trasu_ a nech zobrazit výsledná data trasy, abychom viděli, že API funguje.

## Role 4: Vedení, design, prezentace
- Otevři si mapy, najdi v Olomouci 5 reálných míst, která by mohla být nebezpečná (žádný chodník, rychlá auta, hnízdo pofiderních osob, chybějící přechod...) a zapiš si jejich souřadnice. Předáš je Roli 1.

- V hlavním souboru *app.py* navrhni rozložení stránky. Použij st.sidebar pro boční panel a st.columns pro rozdělení obrazovky (např. vlevo mapa, vpravo formulář,...).

- Založ prezentaci a vytvoř první 3 slidy: 1. Název týmu a logo, 2. Jaký problém řešíme, 3. Naše řešení.
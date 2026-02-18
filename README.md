# 🦷 Plan Higieny Jamy Ustnej

Interaktywny kreator spersonalizowanych planów higieny jamy ustnej dla higienistek stomatologicznych.

## Demo

👉 **[https://numerika-ai.github.io/higienistka/](https://numerika-ai.github.io/higienistka/)**

## Funkcje

### 📋 Kreator Planu (statyczny)
- 7 pytań → automatycznie generowany plan higieny
- Lista zakupów z konkretnymi produktami
- Plan poranny i wieczorny krok po kroku
- 13 Zasad Higieny Jamy Ustnej
- Drukowanie / eksport do PDF

### 💬 Live Chat AI
- Rozmowa z AI (GPT-OSS 120B via LiteLLM)
- Chatbot prowadzi higienistkę przez ankietę
- Automatyczne składanie planu z bloków
- Zabezpieczenie RODO (brak danych osobowych)
- ⚠️ Wymaga dostępu do sieci lokalnej (LiteLLM na 192.168.1.80:4000)

## Biblioteka Bloków

System używa 39 gotowych bloków tekstu:
- **R1-R6** — Rozpoznania kliniczne (6 problemów)
- **F1-F3 / F1p-F3p** — Szczoteczki (zakupy + plan)
- **G1-G4 / G1p-G4a / G3p** — Przestrzenie międzyzębowe
- **H1-H3 / H1p-H3p / H2a-H2b** — Pasty
- **I1 / I1p** — Płyn do płukania
- **J1 / J1p** — Skrobak do języka
- **X1-X3** — Terminy wizyt
- **Z1-Z5** — Bloki stałe (wstęp, zasady, kontakt, cele)

## Stack

- Czysty HTML/CSS/JS (zero zależności)
- GitHub Pages (hosting)
- LiteLLM + GPT-OSS 120B (opcjonalny backend AI)

## Autorzy

Numerika.ai — Bartosz & Dominika  
Built with 🖤 by Wiki (AI Assistant)

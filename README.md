# Simulare Examen Radiologie

Această aplicație web permite simularea unui test grilă cu 32 de întrebări (16 cu un singur răspuns corect și 16 cu răspunsuri multiple), folosind întrebări din domeniul radiologiei.

## Funcționalități
- Încărcare automată a setului de întrebări.
- Selectarea răspunsurilor corecte cu afișare scor.
- Afișare imagini (dacă există).
- Resetarea progresului și regenerarea testelor.

## Utilizare
1. Accesează pagina încărcată pe GitHub Pages.
2. Apasă pe `Generează Test`.
3. Bifează răspunsurile și apasă `Trimite Testul`.

## Structura întrebărilor
Fișierul `data/intrebari.json` conține:
- câmpul `question`: textul întrebării,
- câmpul `image`: imagine asociată (dacă este),
- `answers`: listă cu răspunsuri, fiecare având `text` și `is_correct`.

## Autor
Creat pentru simulare examen în domeniul medical (radiologie).

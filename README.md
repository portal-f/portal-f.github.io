# Portal F

Portal de învățare simplă și accesibilă pentru toți.

## 🌟 Despre

Portal F este punctul central de acces pentru resurse educaționale simplificate:

- **📰 Știri Simple**: Articole de știri în română simplificate la nivel A2
- **🎓 Lecții de Engleză**: Cursuri interactive pentru vorbitori nativi de română

## 🔗 Arhitectura

Portal F conectează mai multe proiecte educaționale independente:

1. **portal-f.github.io** (acest proiect) - Landing page principal
2. **stiri-simple.github.io** - Știri românești simplificate  
3. **audio-engleza.github.io** - Lecții de engleză audio pentru începători

## 🚀 Funcționare

Fiecare link din portal adaugă parametrul `?portal=https://portal-f.github.io` care:
- Activează butonul de înapoi în proiectele țintă
- Menține continuitatea navigării
- Păstrează independența fiecărui proiect

## 🌐 Links

- **Portal Principal**: https://portal-f.github.io
- **Știri Simple**: https://stiri-simple.github.io  
- **Lecții Engleză**: https://audio-engleza.github.io

## 📱 Caracteristici

- **Design Responsive**: Optimizat pentru toate dispozitivele
- **Accesibilitate**: Suport complet pentru cititori de ecran
- **Navigare Simplă**: Interfață intuitivă și clară
- **Proiecte Independente**: Fiecare resursă poate funcționa autonom

## 🏗️ Deployment

Pentru a publica pe GitHub Pages:

1. Creează repository-ul `portal-f.github.io` în organizația `portal-f`
2. Push codul:
```bash
git init
git add .
git commit -m "Initial commit: Portal F"
git branch -M main
git remote add origin https://github.com/portal-f/portal-f.github.io.git
git push -u origin main
```
3. Site-ul va fi disponibil automat la https://portal-f.github.io

---
*Powered by [Zeeguu](https://github.com/zeeguu) technology*
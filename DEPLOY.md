# Deployment Instructions for Portal F

## 🚀 Publicare pe GitHub Pages

### 1. Creează repository-ul pe GitHub

**IMPORTANT**: Repository-ul TREBUIE să se numească exact `portal-f.github.io`

Pe GitHub:
1. Du-te la https://github.com/portal-f
2. Click "New repository"  
3. **Nume**: `portal-f.github.io` (EXACT acest nume!)
4. Public repository
5. NU adăuga README, .gitignore sau license

### 2. Publică codul

```bash
cd /Users/gh/zeeguu/portal-f.github.io

# Inițializează git
git init
git add .
git commit -m "Initial commit: Portal F"

# Conectează la GitHub
git branch -M main
git remote add origin https://github.com/portal-f/portal-f.github.io.git

# Push
git push -u origin main
```

### 3. Verifică deployment

- GitHub Pages se activează AUTOMAT pentru `[org-name].github.io`
- Site-ul va fi disponibil la: **https://portal-f.github.io**
- Durează ~5-10 minute pentru prima publicare

## 📝 Actualizări

Pentru actualizări ulterioare:

```bash
cd /Users/gh/zeeguu/portal-f.github.io
git add .
git commit -m "Update portal"
git push
```

## 🔧 Troubleshooting

### Site-ul nu apare?
- Verifică numele: TREBUIE să fie `portal-f.github.io`
- Repository-ul trebuie să fie public
- Așteaptă 10 minute

### Link-urile nu funcționează?
- Verifică că știrile sunt la: https://stiri-simple.github.io
- Verifică că lecțiile sunt la: https://audio-engleza.github.io

## 🌐 URL-uri Finale

- **Portal F**: https://portal-f.github.io
- **Știri (cu back button)**: https://stiri-simple.github.io/?portal=https://portal-f.github.io
- **Lecții (cu back button)**: https://audio-engleza.github.io/?portal=https://portal-f.github.io

---
*Notă: Pentru organizații GitHub, repository-ul `[org-name].github.io` este servit automat ca GitHub Pages*
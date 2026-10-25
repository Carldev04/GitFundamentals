# 🌿 Git & GitHub Fundamentals

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Git Bash](https://img.shields.io/badge/Git%20Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

Dobro došli u moj repozitorij posvećen savladavanju sustava za kontrolu verzija **Git** i platforme **GitHub**! Ovaj repozitorij sadrži strukturirane bilješke, primjere naredbi, praktične vježbe i konfiguracijske predloške organizirane kroz 6 tematskih cjelina.

---

## 📚 Popis lekcija i struktura repozitorija

Lekcije prate cjelokupan proces rada s verzijama koda — od prve inicijalizacije u terminalu do timskog rada i objave projekta online:

| # | Mapa (Lekcija) | Obuhvaćeni koncepti i opis |
| :--- | :--- | :--- |
| **01** | [`01_Osnove_Gita`](./01_Osnove_Gita) | Uvod u Git i GitHub, instalacija, rad u Git Bash terminalu, `git init`, `add`, `commit` i domaći zadatak |
| **02** | [`02_Github_Gitignore`](./02_Github_Gitignore) | Povezivanje lokalnog i udaljenog repozitorija (`remote`, `push`) te konfiguracija `.gitignore` datoteke |
| **03** | [`03_Github_Pregled`](./03_Github_Pregled) | Pregled GitHub sučelja, analiza povijesti promjena (commits), Issues i upravljanje postavkama repozitorija |
| **04** | [`04_Branch_PullRequest`](./04_Branch_PullRequest) | Kreiranje i prebacivanje grana (`branch`, `checkout`/`switch`), spajanje (`merge`) i otvaranje Pull Requestova |
| **05** | [`05_Workflow`](./05_Workflow) | Git Workflow u praksi — standardni tijek rada na projektima, rješavanje konflikata i dobre prakse |
| **06** | [`06_Deployment`](./06_Deployment) | Kako okačiti sajt online — besplatan hosting i objava statičkih web stranica putem GitHub Pagesa |

---

## ⚡ Brzi podsjetnik (Git Cheat Sheet)

Najčešće korištene naredbe obrađene kroz lekcije:

```bash
# 1. Inicijalizacija i provjera stanja
git init                        # Kreiranje novog lokalnog Git repozitorija
git status                      # Provjera statusa datoteka (modified, staged, untracked)

# 2. Spremanje promjena (Staging & Commit)
git add .                       # Dodavanje svih promjena u staging area
git commit -m "Opis promjene"   # Spremanje snimke stanja (commit) s porukom

# 3. Rad s granama (Branching)
git branch naziv-grane          # Kreiranje nove grane
git checkout naziv-grane        # Prebacivanje na željenu granu
git merge naziv-grane           # Spajanje grane u trenutnu aktivnu granu

# 4. Rad s GitHubom (Remote)
git remote add origin <url>     # Povezivanje lokalnog repozitorija s GitHubom
git push -u origin main         # Slanje lokalnih commitova na GitHub
git pull                        # Preuzimanje i spajanje najnovijih promjena s GitHuba

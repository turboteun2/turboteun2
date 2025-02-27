# Git Commands Cheat Sheet

Een overzicht van veelgebruikte Git-commando's, gesorteerd op categorie. **Meest gebruikte commando's zijn gemarkeerd met ⭐.**

## 1. Configuratie
```bash
git config --global user.name "Jouw Naam"      # Stel je naam in
git config --global user.email "jouw@email.com" # Stel je e-mail in
```

## 2. Repositories
```bash
git init           # ⭐ Initialiseer een nieuwe Git-repository
git clone <url>    # ⭐ Clone een bestaande repository
```

## 3. Status & Log
```bash
git status         # ⭐ Bekijk de status van je repository
git log           # Bekijk commit-historie
git log --oneline # Verkorte log-weergave
```

## 4. Toevoegen & Committen
```bash
git add <bestand>    # Voeg een specifiek bestand toe
git add .           # ⭐ Voeg alle gewijzigde bestanden toe
git commit -m "Bericht" # ⭐ Commit de wijzigingen met een bericht
```

## 5. Branches
```bash
git branch             # Toon beschikbare branches
git branch <naam>      # Maak een nieuwe branch
git checkout <naam>    # ⭐ Wissel naar een andere branch
git switch <naam>      # Alternatief voor checkout
git merge <branch>     # Merge een branch in de huidige branch
git branch -d <naam>   # Verwijder een branch
```

## 6. Pushen & Pullen
```bash
git remote add origin <url> # Koppel een repository aan een remote

git push origin <branch>  # ⭐ Push wijzigingen naar remote repository
git pull origin <branch>  # ⭐ Haal de laatste wijzigingen op van remote repository
```

## 7. Terugdraaien & Herstellen
```bash
git checkout -- <bestand>   # Herstel een bestand naar de laatste commit
git reset HEAD <bestand>    # Verwijder een bestand uit de staging area
git reset --hard <commit>   # ⭐ Reset naar een specifieke commit (let op: wijzigingen gaan verloren!)
```

## 8. Stashing (Tijdelijk Opslaan)
```bash
git stash          # ⭐ Sla tijdelijke wijzigingen op zonder te committen
git stash pop      # Haal de opgeslagen wijzigingen terug
git stash list     # Bekijk alle opgeslagen stashes
```

## 9. Tags
```bash
git tag <versie>   # Maak een nieuwe tag
git tag            # Bekijk alle tags
git push origin <tag> # Push een tag naar remote repository
```

## 10. Handige Extra's
```bash
git diff           # Bekijk verschillen tussen commits of bestanden
git rebase <branch> # Herschrijf commit-historie
```

## Veelgebruikte Commando's ⭐
- `git status`
- `git add .`
- `git commit -m "Bericht"`
- `git push origin <branch>`
- `git pull origin <branch>`
- `git checkout <branch>`
- `git reset --hard <commit>`
- `git stash`

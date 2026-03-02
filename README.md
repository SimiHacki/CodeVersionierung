# CodeVersionierung

# Aufgabe 2 – Branching Strategien (Kurzfassung)

## 1. GitHub Flow
**Charakteristika:** Einfache Strategie, ein Hauptzweig `main`, Feature-Branches, Merge per Pull Request, ideal für CI/CD.  
**Vorteile:** Sehr simpel, schnelle Deployments, wenig Overhead.  
**Nachteile:** Wenig Kontrolle für komplexe Releases, kein separates Release-/Hotfix-Management.

## 2. GitFlow
**Charakteristika:** Strukturierte Strategie mit `main`, `develop`, sowie `feature`, `release`, `hotfix` Branches.  
**Vorteile:** Klare Prozesse, geeignet für große Projekte und geplante Releases.  
**Nachteile:** Höhere Komplexität, weniger passend für kontinuierliche Deployments.

## 3. Trunk-Based Development
**Charakteristika:** Nur ein Hauptzweig, sehr kurze Feature-Branches, häufige kleine Commits, Feature Flags.  
**Vorteile:** Sehr schnelle Integration, optimal für CI/CD.  
**Nachteile:** Erfordert strenge Tests und Disziplin; Feature-Flag-Verwaltung nötig.

## Kurzvergleich
| Strategie | Komplexität | Einsatz |
|----------|-------------|---------|
| GitHub Flow | niedrig | kleine Teams, Web-Apps, schnelles Deployment |
| GitFlow | hoch | große Projekte, klassische Release-Zyklen |
| Trunk-Based | mittel | Teams mit starkem CI/CD-Fokus |

# GitHub Organisationssystem Guide

Interaktive, zweisprachige Lernseite (Deutsch / Türkisch) für die geplante GitHub-Struktur von **Agentur, TFV und Fures**.

## Inhalt
- GitHub Organization, persönliche Accounts und Repositories
- Ownership, Organization- und Repository-Rollen
- Technische GitHub-Rechte vs. rechtliche Eigentümerschaft
- Wie größere Unternehmen GitHub strukturieren
- Zielstruktur Agentur / TFV / Fures
- Monorepo vs. mehrere Repositories
- Netlify-Deployment
- GitHub Free / Actions
- Migrationsplan und FAQ

## Struktur bearbeiten
Auf der Website oben **„Struktur bearbeiten / Yapıyı düzenle“** wählen.

Die aktuelle Organization-Struktur kann als JSON angepasst werden. Änderungen werden sofort visualisiert, per localStorage im Browser gespeichert und können exportiert/importiert werden.

Die Standardstruktur liegt in `data.js`.

## Netlify
Die Seite ist statisch und braucht keinen Build.

- Base directory: leer
- Build command: leer
- Publish directory: `.`

## Aktuelle Default-Struktur
- Agentur: Andreas
- TFV: Andreas, Furkan technische Mitarbeit
- Fures: Furkan + Gülben

Hinweis: GitHub-Rollen bilden technische Zugriffsrechte ab. Rechtliche Eigentumsverhältnisse werden dadurch nicht automatisch festgelegt.

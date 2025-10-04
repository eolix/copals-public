# CoPals Translations (i18n)

Thank you for helping make CoPals available in more languages!

The CoPals app uses **react-i18next** + **expo-localization**.  
All translation files live here at the root of the repository.

## Available Languages
| Flag | Language                  | Code | Status    |
|------|---------------------------|------|-----------|
| English (default)          | `en` | Complete  | in v1.1.1 |
| Spanish                   | `es` | Complete  | in v1.1.1 |
| Italian                   | `it` | Complete  | in v1.1.1 |
| French                    | `fr` | Complete  | in v1.1.1 |
| German                    | `de` | Complete  | in v1.1.1 |
| Japanese                  | `ja` | Complete  | in v1.1.1 |
| Brazilian Portuguese (Brazil) | `br` | Complete  | in v1.1.1 |

## How to Add or Improve a Translation
1. Fork this repository
2. Create a new file `<language-code>.json` (e.g. `pl.json` for Polish)  
   → Copy the structure from `en.json` and translate the values
3. Or edit an existing file to fix/improve translations
4. Open a Pull Request 

> All PRs are reviewed and merged only by the project maintainer.

## How to Report a Bug or Request a Feature in CoPals
This repository is also the official place for:
- Translation-related bugs
- General CoPals bug reports
- Feature requests

Please use the corresponding issue template:
- [Report a bug](https://github.com/eolix/copals-public/issues/new?template=bug_report.md)
- [Request a feature](https://github.com/eolix/copals-public/issues/new?template=feature_request.md)

## File Format Example (`fr.json`)
```json
{
    "general": {
      "error": "Erreur"
    },
    "profile": {
      "accountSettings": "Paramètres du compte"
    },
    "requests": {
      "loadingRequests": "Chargement des demandes..."
    },
    "navigation": {
      "calendar": "Calendrier"
    },
    "calendar": {
      "regularSchedule": "Planning régulier"
    },
    "journal": {
      "meal": "Repas"
    },
    "auth": {
      "existingAccount": "Compte existant"
    },
    "appstore": {
      "appname": "CoPals"   
    }
  }
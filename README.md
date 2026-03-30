# ObsidiaNorth — Website

Statische landingspagina voor ObsidiaNorth, gehost via AWS Amplify.

## Deployment via AWS Amplify

### Optie 1: Via Git (aanbevolen)

1. Push deze repository naar GitHub (of CodeCommit)
2. Ga naar AWS Amplify Console
3. Klik op **'New app'** > **'Host web app'**
4. Koppel je GitHub-account en selecteer deze repository
5. Amplify detecteert automatisch de amplify.yml
6. Klik **'Save and deploy'**

### Optie 2: Handmatig uploaden (zonder Git)

1. Ga naar AWS Amplify Console
2. Klik op **'New app'** > **'Host web app'**
3. Kies **'Deploy without Git provider'**
4. Maak een ZIP van de projectmap (inclusief index.html)
5. Upload de ZIP en klik **'Save and deploy'**

## Projectstructuur

    .
    index.html      Hoofdpagina (enkelvoudige HTML-site)
    amplify.yml     AWS Amplify build-configuratie
    README.md       Deze instructies
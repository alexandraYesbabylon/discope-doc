# Communication

## Emails (SMTP)
Cette configuration permet d'établir les paramètres nécessaires pour l'envoi d'e-mails via un serveur SMTP. Elle inclut des éléments essentiels tels que l'hôte SMTP, le port, le nom d'affichage du compte, le nom d'utilisateur, le mot de passe et l'adresse e-mail associée. De plus, il est important de fournir une adresse e-mail pour signaler les abus. Tous ces paramètres doivent être définis dans le fichier `config.json`.

#### Paramètres de configuration SMTP

EMAIL_SMTP_HOST : Nom d'hôte du serveur SMTP pour l'envoi d'e-mails.

EMAIL_SMTP_PORT : Port à utiliser pour les connexions SMTP.

EMAIL_SMTP_ENCRYPT : Couches de chiffrement à utiliser pour les connexions SMTP ('tls' ou 'ssl', false pour SMTP sans chiffrement).

EMAIL_SMTP_ACCOUNT_DISPLAYNAME : Nom à afficher pour le compte de messagerie.

EMAIL_SMTP_ACCOUNT_USERNAME : Nom du compte (ou adresse e-mail) à utiliser pour l'authentification sur le serveur SMTP.

EMAIL_SMTP_ACCOUNT_PASSWORD : Mot de passe à utiliser pour l'authentification sur le serveur SMTP.

EMAIL_SMTP_ACCOUNT_EMAIL : Adresse e-mail à utiliser comme expéditeur (doit être autorisée par le serveur SMTP).

EMAIL_SMTP_ABUSE_EMAIL : Adresse e-mail pour signaler les abus.

#### Exemple de fichier `config.json` :

```json
{
    "EMAIL_SMTP_HOST": "SSL0.PROVIDER.NET",
    "EMAIL_SMTP_PORT": "2525",
    "EMAIL_SMTP_ENCRYPT": "tls",
    "EMAIL_SMTP_ACCOUNT_DISPLAYNAME": "Yesbabylon Symbiose",
    "EMAIL_SMTP_ACCOUNT_USERNAME": "account.username",
    "EMAIL_SMTP_ACCOUNT_PASSWORD": "password",
    "EMAIL_SMTP_ACCOUNT_EMAIL": "email.to.send.from@provider.com",
    "EMAIL_SMTP_ABUSE_EMAIL": "abuse@example.com"
}
```
## Templates

La configuration de templates permet de créer des modèles d’e-mails destinés aux clients. Chaque modèle est composé de plusieurs sections :  

- Objet : Définir le titre ou sujet de l'e-mail.  
- Corps : Rédiger le contenu principal du message.  
- En-tête (header) et Pied de page (footer) : Sections facultatives pour structurer l’e-mail.  

Ces modèles sont associés à une catégorie spécifique et à un type prédéfini, tels que :  

- Devis  
- Option  
- Contrat  
- Facture  
- Financement  

Par défaut, une catégorie de modèle est définie pour faciliter l’organisation.  

### Fichiers joints

Les modèles peuvent inclure des fichiers joints grâce à l’option "pièces jointes". Cela permet d’ajouter les documents nécessaires directement dans l’e-mail envoyé au client.  

### Traduction des Templates

Chaque partie d’un template doit être traduite dans les différentes langues prévues pour l’envoi.
Par défaut, la langue utilisée est celle définie par l’utilisateur dans les paramètres.  
Les traductions garantissent une communication adaptée aux préférences linguistiques des clients.  

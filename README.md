# Routine de création de projet


## Création du projet

```bash
ng new my-project --style=less
cd my-project
```


## Création des directives récurrentes

```bash
ng generate directive directives/alert/alert
ng generate directive directives/copyright/copyright
```


## Création des services récurrents

```bash
ng generate service services/rest/rest
ng generate class services/http_interceptor/http --type=interceptor
```


## Création des composants récurrents

```bash
ng generate component components/header
ng generate component components/footer
ng generate component components/homepage
ng generate component components/contact
ng generate component components/terms-of-use
ng generate component components/privacy-policy
ng generate component components/eula
ng generate component components/credits
```


## Création des composants de sécurité

```bash
ng generate guard guards/auth/auth
ng generate service services/auth/auth
ng generate module security
ng generate component security/register
ng generate component security/login
ng generate component security/forgotten-password
ng generate component security/reset-password
ng generate component security/logout
```


## Création des modules métiers

```bash
ng generate module modules/pizzas
ng generate component modules/pizzas/components/index
ng generate component modules/pizzas/components/details
ng generate component modules/pizzas/components/create
ng generate component modules/pizzas/components/update
ng generate component modules/pizzas/components/delete
ng generate component modules/pizzas/form
ng generate service modules/pizzas/form/form
ng generate interface interfaces/pizza
```
---
description: >-
  Mettre en place un système de règlement avec validation. Les nouveaux
  arrivants pourront obtenir un rôle une fois qu'ils auront pris connaissance
  des règles du serveur.
---

# Règlement

## Création du règlement

Commencez par créer votre règlement en utilisant la commande `rules create` ou `@DraftBot#0535 rules create`.

Par la suite **DraftBot** vous demandera quel est le rôle que vous souhaitez attribuer aux membres qui attesteront avoir pris connaissance de ce règlement. Répondez alors simplement avec le nom du rôle que vous souhaitez associer à la validation.

{% hint style="info" %}
Si vous ne souhaitez pas notifier toutes les personnes qui ont d'ores et déjà le rôle destiné au règlement, vous pouvez simplement répondre le nom du rôle. Cela fonctionnera tout aussi bien que la mention.
{% endhint %}

![Exemple de règlement après création](https://raw.githubusercontent.com/DraftBot/Documentation/8fcb724f18dad6c490ae316c6a61ceeee1f1dd94/.gitbook/assets/reglement.png)

{% hint style="danger" %}
En retirant la réaction :white\_check\_mark: les membres perdent également le rôle associé.
{% endhint %}

**Astuce :** _Afin de profiter au maximum de cet outil, nous vous conseillons d'empêcher le rôle @everyone d'accéder aux principaux salons du serveur, excepté celui d'accueil, et de permettre l'accès aux autres salons uniquement au rôle qui sera obtenus par le règlement. Ainsi, seules les personnes ayant pris connaissance du règlement du serveur pourront réellement accéder au serveur._&#x20;

## Ajout de règles

Pour conserver une communauté stable, il est nécessaire de mettre en place un système de règles à suivre. Vous pourrez facilement en ajouter à votre règlement grâce à la commande `rules <argument> <message>` ou `@DraftBot#0535 rules <argument> <message>`.

| Arguments | Description                                                                                                               |
| --------- | ------------------------------------------------------------------------------------------------------------------------- |
| argument  | L'argument est l'action que vous souhaitez faire : **ajouter (add)** et **retirer (remove)** une règle de votre règlement |
| message   | L'argument message représente l'ID du message où se trouve le règlement                                                   |

{% hint style="info" %}
Besoin d'aide pour récupérer l'identifiant d'un message ? [Cliquez ici !](../../autres/recuperer-un-identifiant.md#message)
{% endhint %}

Une fois ces deux arguments renseignés, **DraftBot** vous demandera le titre de la règle et la description détaillée de cette règle.&#x20;

Une fois votre règlement créé vous devriez avoir quelque chose de ce type :

![](https://raw.githubusercontent.com/DraftBot/Documentation/8fcb724f18dad6c490ae316c6a61ceeee1f1dd94/.gitbook/assets/rules.png)

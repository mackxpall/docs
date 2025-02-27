---
title: Informationen zu Marketplace-Badges
intro: 'Erfahre mehr über die Badges, die du möglicherweise für einige Apps und Aktionsauflistungen auf {% data variables.product.prodname_marketplace %} siehst.'
redirect_from:
  - /developers/github-marketplace/about-verified-creator-badges
  - /developers/github-marketplace/about-marketplace-badges
versions:
  fpt: '*'
  ghec: '*'
ms.openlocfilehash: bba9137fc39c1bc101a75650dcea03e651d37fff
ms.sourcegitcommit: fb047f9450b41b24afc43d9512a5db2a2b750a2a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/11/2022
ms.locfileid: '145089724'
---
## Für GitHub-Apps

Bestimmte Apps in {% data variables.product.prodname_marketplace %} verfügen über den Badge {% octicon "verified" aria-label="The verified badge" %} sowie über eine QuickInfo mit dem Hinweis, dass die Domäne und die E-Mail-Adresse des Herausgebers verifiziert wurden. Das bedeutet, dass die App im Besitz einer Organisation ist, die folgende Anforderungen erfüllt:

- Sie hat den Besitz ihrer Domäne bestätigt und verfügt über einen Badge vom Typ „Verifiziert“ für ihr Profil.
- Sie hat ihre E-Mail-Adresse bestätigt, sodass der Support von {% data variables.product.prodname_dotcom %} die Organisation erreichen kann.
- Sie schreibt die zweistufige Authentifizierung für ihre Organisation vor. Weitere Informationen findest du unter [Erfordern der zweistufigen Authentifizierung in deiner Organisation](/organizations/keeping-your-organization-secure/requiring-two-factor-authentication-in-your-organization).

![Marketplace-Badge für GitHub Apps](/assets/images/marketplace/apps-with-verified-publisher-badge-tooltip.png)

{% note %} Die App wird von {% data variables.product.prodname_dotcom %} nicht analysiert. Der Marketplace-Badge {% octicon "verified" aria-label="The verified badge" %} bestätigt lediglich, dass der Herausgeber die oben aufgeführten Anforderungen erfüllt.
{% endnote %}

Informationen dazu, wie du diesen Badge deiner App hinzufügen kannst, findest du unter [Beantragen der Herausgeberüberprüfung für deine Organisation](/developers/github-marketplace/applying-for-publisher-verification-for-your-organization).

Einige Apps in {% data variables.product.prodname_marketplace %} verfügen über den Badge {% octicon "verified" aria-label="The verified badge" %} sowie über eine QuickInfo mit dem Hinweis, dass die App die Anforderungen für die Veröffentlichung erfüllt (anstelle des Hinweises, dass die Domäne und die E-Mail-Adresse des Herausgebers verifiziert wurden). Das bedeutet, dass die App zwar die unter [Voraussetzungen für die Veröffentlichung einer App](/developers/github-marketplace/requirements-for-listing-an-app) beschriebenen Veröffentlichungsanforderungen erfüllt, der Herausgeber aber nicht überprüft wurde, wie unter [Beantragen der Herausgeberüberprüfung für deine Organisation](/developers/github-marketplace/applying-for-publisher-verification-for-your-organization) beschrieben. Der Preisplan von Apps mit diesem Badge kann erst geändert werden, wenn der Herausgeber erfolgreich eine Überprüfung beantragt hat.

![Marketplace-Badge für GitHub Apps](/assets/images/marketplace/apps-with-unverified-publisher-badge-tooltip.png)

Weitere Informationen zu den Voraussetzungen für die Veröffentlichung einer App auf {% data variables.product.prodname_marketplace %} findest du unter [Voraussetzungen für die Veröffentlichung einer App auf {% data variables.product.prodname_marketplace %}](/marketplace/getting-started/requirements-for-listing-an-app-on-github-marketplace/).

Informationen zur Suche nach Apps findest du unter [Durchsuchen des {% data variables.product.prodname_marketplace %}](/search-github/searching-on-github/searching-github-marketplace).

## Für GitHub Actions 

Bei Aktionen mit dem Badge {% octicon "verified" aria-label="The verified badge" %} oder mit dem Badge für überprüfte Ersteller wurde der Ersteller der Aktion von {% data variables.product.prodname_dotcom %} als Partnerorganisation verifiziert.

![Badge für überprüfte Ersteller für GitHub Actions](/assets/images/marketplace/verified-creator-badge-for-actions.png)

Informationen zum Veröffentlichen einer GitHub-Aktion auf {% data variables.product.prodname_marketplace %} findest du unter [Aktionen auf dem GitHub-Marktplatz veröffentlichen](/actions/creating-actions/publishing-actions-in-github-marketplace).

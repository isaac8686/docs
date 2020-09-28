---
title: Aplicar políticas do GitHub Actions na sua conta corporativa
intro: 'Os proprietários de empresas podem habilitar, desabilitar limitar {{ site.data.variables.product.prodname_actions }} para uma conta corporativa.'
product: '{{ site.data.reusables.gated-features.enterprise-accounts }}'
miniTocMaxHeadingLevel: 4
versions:
  free-pro-team: '*'
---

### Sobre as permissões de {{ site.data.variables.product.prodname_actions }} para a sua conta corporativa

Por padrão, {{ site.data.variables.product.prodname_actions }} é habilitado em todas as organizações que pertencem a uma conta corporativa. Você pode optar por desabilitar {{ site.data.variables.product.prodname_actions }} para todas as organizações que pertencem a uma conta corporativa ou apenas permitir organizações especificadas. Você também pode limitar o uso de ações públicas, de modo que as pessoas só possam usar ações locais que existem na sua organização.

Para obter mais informações sobre {{ site.data.variables.product.prodname_actions }}, consulte "[Sobre {{ site.data.variables.product.prodname_actions }}](/actions/getting-started-with-github-actions/about-github-actions)."


### Gerenciar as permissões de {{ site.data.variables.product.prodname_actions }} para a sua conta corporativa

{{ site.data.reusables.enterprise-accounts.access-enterprise }}
{{ site.data.reusables.enterprise-accounts.policies-tab }}
{{ site.data.reusables.enterprise-accounts.actions-tab }}
{{ site.data.reusables.actions.enterprise-actions-permissions }}

### Habilitar fluxos de trabalho para bifurcações privadas do repositório

{{ site.data.reusables.github-actions.private-repository-forks-overview }}

#### Configurar a política de uma bifurcação privada para a sua conta corporativa

{{ site.data.reusables.enterprise-accounts.access-enterprise }}
{{ site.data.reusables.enterprise-accounts.policies-tab }}
{{ site.data.reusables.enterprise-accounts.actions-tab }}
{{ site.data.reusables.github-actions.private-repository-forks-configure }}
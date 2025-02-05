---
title: Desbloquear un usuario desde tu organización
intro: 'Organization owners and moderators can unblock a user who was previously blocked, restoring their access to the organization''s repositories.'
redirect_from:
  - /articles/unblocking-a-user-from-your-organization
  - /github/building-a-strong-community/unblocking-a-user-from-your-organization
versions:
  fpt: '*'
  ghec: '*'
topics:
  - Community
shortTitle: Desbloquear desde tu organización
---

Después de desbloquear un usuario desde tu organización, este podrá contribuir con los repositorios de tu organización.

Si seleccionaste una cantidad de tiempo específica para bloquear al usuario, se desbloqueará de forma automática cuando termine ese período de tiempo. Para obtener más información, consulta "[Bloquear un usuario de tu organización](/articles/blocking-a-user-from-your-organization)".

{% tip %}

**Sugerencia**: Las configuraciones que se hayan eliminado cuando bloqueaste al usuario de tu organización, como el estado de colaborador, las estrellas y las observaciones, no se restaurarán cuando desbloquees al usuario.

{% endtip %}

## Desbloquear un usuario en un comentario

1. Navega hasta el comentario cuyo autor quieres desbloquear.
2. En la esquina superior derecha del comentario, haz clic en {% octicon "kebab-horizontal" aria-label="The horizontal kebab icon" %}, luego haz clic en **Unblock user** (Desbloquear usuario). ![Ícono kebab horizontal y menú de moderación de comentarios que muestra la opción de desbloquear usuario](/assets/images/help/repository/comment-menu-unblock-user.png)
3. To confirm you would like to unblock the user, click **OK**.

## Desbloquear un usuario en los parámetros de la organización


{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.block_users %}
1. En "Blocked users" (Usuarios bloqueados), al lado del usuario que quieres desbloquear, haz clic en **Unblock** (Desbloquear). ![Botón Unblock user (Desbloquear usuario)](/assets/images/help/organizations/org-unblock-user-button.png)

## Leer más

- "[Bloquear a un usuario de tu organización](/communities/maintaining-your-safety-on-github/blocking-a-user-from-your-organization)"
- "[Bloquear a un usuario desde tu cuenta personal](/communities/maintaining-your-safety-on-github/blocking-a-user-from-your-personal-account)"
- "[Desbloquear a un usuario desde tu cuenta personal](/communities/maintaining-your-safety-on-github/unblocking-a-user-from-your-personal-account)"
- "[Informar abuso o spam](/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam)"

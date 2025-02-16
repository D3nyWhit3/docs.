---
title: Using SAML for enterprise IAM
shortTitle: SAML for enterprise IAM
intro: 'You can centrally manage {% ifversion ghes or ghae %}accounts and {% endif %}access to {% ifversion ghes %}{% data variables.location.product_location %}{% elsif ghae %}your enterprise{% elsif ghec %}your enterprise''s resources{% endif %} with SAML single sign-on (SSO){% ifversion ghec or ghae %} and System for Cross-domain Identity Management (SCIM){% endif %}.'
versions:
  ghec: '*'
  ghes: '*'
redirect_from:
  - /github/setting-up-and-managing-your-enterprise/configuring-identity-and-access-management-for-your-enterprise-account
  - /admin/authentication/managing-identity-and-access-for-your-enterprise
  - /admin/authentication/configuring-authentication-and-provisioning-with-your-identity-provider
  - /enterprise/admin/articles/configuring-saml-authentication
  - /enterprise/admin/articles/about-saml-authentication
  - /enterprise/admin/user-management/using-saml
  - /enterprise/admin/authentication/using-saml
  - /admin/authentication/using-saml
  - /enterprise/admin/authentication/authenticating-users-for-your-github-enterprise-server-instance/using-saml
  - /admin/identity-and-access-management/authenticating-users-for-your-github-enterprise-server-instance/using-saml
children:
  - /deciding-whether-to-configure-saml-for-your-enterprise-or-your-organizations
  - /configuring-saml-single-sign-on-for-your-enterprise
  - /configuring-user-provisioning-with-scim-for-your-enterprise
  - /managing-team-synchronization-for-organizations-in-your-enterprise
  - /configuring-saml-single-sign-on-for-your-enterprise-using-okta
  - /disabling-saml-single-sign-on-for-your-enterprise
  - /configuring-authentication-and-provisioning-for-your-enterprise-using-azure-ad
  - /enabling-encrypted-assertions
  - /updating-a-users-saml-nameid
  - /switching-your-saml-configuration-from-an-organization-to-an-enterprise-account
  - /troubleshooting-saml-authentication
---

{% data reusables.enterprise-accounts.emu-saml-note %}

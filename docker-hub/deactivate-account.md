---
title: Deactivating an account or an organization
description: Learn how to deactivate a Docker Hub account or an organization
keywords: Docker Hub, delete, deactivate, account, organization
---

Your Docker Hub account or organization may also be linked to other Docker products and services, so deactivating it will also disable access to those products and services.

## Deactivating an account

Before deactivating your Docker Hub account, please complete the following:

1. Download any images and tags you want to keep:
   `docker pull -a <image>:<tag>`.

2. If you belong to any organizations, remove your account from all of them.

3. If you are the sole owner of an organization,  either add someone to the **owners** team and then remove yourself from the organization, or deactivate the organization. Similarly, if you are the sole owner of a company, either add someone else as a company owner and then remove yourself, or deactivate the company.

4. If you have an active subscription, downgrade it to the **Docker Personal** subscription.

      In Docker Hub, navigate to **_Your Account_** > **Account Settings** > **Billing**.

5. Unlink your [Github and Bitbucket accounts](../docker-hub/builds/link-source.md#unlink-a-github-user-account).

Once you have completed all the steps above, you may deactivate your account. On Docker Hub, go to **_Your Account_** > **Accounts Settings** > **Deactivate Account**.

> This cannot be undone! Be sure you've gathered all the data you need from your account before deactivating it.
{: .warning }


## Deactivating an organization

Before deactivating an organization, please complete the following:

1. Download any images and tags you want to keep:
  `docker pull -a <image>:<tag>`.

2. If you have an active subscription, downgrade it to the **Docker Free Team** subscription:

      In Docker Hub, navigate to **Organizations** > **_Your Organization_** > **Billing**.

3. Remove all other members, including those in the **Owners** team, within the organization.

4. Unlink your [Github and Bitbucket accounts](../docker-hub/builds/link-source.md#unlink-a-github-user-account).

Once you have completed all the steps above, you may deactivate your organization. On Docker Hub, go to **Organizations** > **_Your Organization_** > **Settings** > **Deactivate Org**.

> This cannot be undone! Be sure you've gathered all the data you need from your organization before deactivating it.
{: .warning }

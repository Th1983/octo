---
title: GitHub Marketplace アプリケーションのキャンセル
intro: '{% data variables.product.prodname_marketplace %}のアプリケーションは、いつでもアカウントからキャンセルおよび削除できます。'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/canceling-a-github-marketplace-app
  - /articles/canceling-an-app-for-your-personal-account/
  - /articles/canceling-an-app-for-your-organization/
  - /articles/canceling-a-github-marketplace-app
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-github-marketplace-apps/canceling-a-github-marketplace-app
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Cancellation
  - Marketplace
  - Organizations
  - Trials
  - User account
shortTitle: Marketplaceアプリケーションのキャンセル
---

アプリケーションをキャンセルすると、そのプランは現在の支払いサイクルが終わるまで有効のままとなり、 次の支払いサイクルで無効となります。 詳しい情報については、[{% data variables.product.prodname_marketplace %}の支払いについて](/articles/about-billing-for-github-marketplace)を参照してください。

有料プランの無料トライアルをキャンセルすると、そのプランはすぐにキャンセルされ、キャンセルしたアプリケーションにアクセスできなくなります。 無料トライアル期間中にキャンセルしない場合、アカウントで設定された支払い方法で、トライアル期間の終了時にプランに対して課金されます。 詳しい情報については、[{% data variables.product.prodname_marketplace %}の支払いについて](/articles/about-billing-for-github-marketplace)を参照してください。

{% data reusables.marketplace.downgrade-marketplace-only %}

## 個人アカウントのアプリケーションをキャンセルする

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.billing_plans %}
{% data reusables.marketplace.cancel-app-billing-settings %}
{% data reusables.marketplace.cancel-app %}

## 個人アカウントのアプリケーション無料トライアルをキャンセルする

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.billing_plans %}
{% data reusables.marketplace.cancel-free-trial-billing-settings %}
{% data reusables.marketplace.cancel-app %}

## Organization の無料トライアルをキャンセルする

{% data reusables.marketplace.marketplace-org-perms %}


{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.billing_plans %}
{% data reusables.marketplace.cancel-app-billing-settings %}
{% data reusables.marketplace.cancel-app %}

## Organization のアプリケーション無料トライアルをキャンセルする

{% data reusables.marketplace.marketplace-org-perms %}


{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.billing_plans %}
{% data reusables.marketplace.cancel-free-trial-billing-settings %}
{% data reusables.marketplace.cancel-app %}

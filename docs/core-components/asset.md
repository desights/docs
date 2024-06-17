# 🪙 Asset

{% hint style="danger" %}
This page is being updated and content might change. The content below is not in its final form.
{% endhint %}

Asset is the core component of Desights Protocol. If we were to choose one biggest value proposition of Desights, it would be Asset. Desights Protocol exists to facilitate the creation of Assets.&#x20;

Each Asset is a DAO and comes with its own governance. Governance token of Asset is represented by symbol <mark style="color:yellow;">$asset</mark> within Desights. $asset is an ERC20 token and also represents the Ownership rights of that particular Asset. Meaning that if you are holding $asset token of a given asset, you are co-owner of that asset and can take part in the governance of that Asset based on your Ownership percentage (i.e.) the amount of $asset held by your wallet compared with total supply of that $asset. \
\


## Lifecycle of an Asset

### 1. Created

Asset is always created within a Challenge. It cannot exist outside the Challenge. It makes logical sense, because Asset is typically created to solve the Challenge. When Asset is created, it assumes the initial blueprint of Ownership Split defined within a Challenge.

### 2. Delisted

When an Asset is created it is delisted by default. Meaning that this asset is not available to be consumed by subscription, purchase or any other monetisation model.  Reason for delisting Asset as a default is because when it is created Asset might be in its raw form and doesn't provide any value add. (e.g.) when an AI model is created in its raw form (without any training on data), they are just algorithms and don't have much value to itself.&#x20;

### 3. Listed

Initially when Asset is created, it is unlisted meaning that it cannot be subscribed or purchased. Listing/Delisting is handled by toggling `isListed` flag on Asset to `true` or `false`. When Asset is listed, it is said to be generating revenue. This revenue is then passed down to the co-owners as royalties based on their Ownership percentage.&#x20;


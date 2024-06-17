# 🧩 Challenge

{% hint style="danger" %}
This page is being updated and content might change. The content below is not in its final form.
{% endhint %}

<figure><img src="../.gitbook/assets/challenge-architecture (1).png" alt=""><figcaption><p>Challenge DAO Architecture diagram</p></figcaption></figure>

Challenge is a core component within Desights. Challenge by itself is generic that can have various implementations depending on the use case.  \
For (e.g.) In our [competitions platform](../products/competitions.md), challenge is implemented as a Competition. \
If you are building a Data Union, then Challenge can be implemented as the union project. Basically, Challenge can be seen as a Project or entity which allows collection of funds, distribution of collected funds and creation of assets by utilising those funds. \
\
Challenge comes with its own funding pool and governance. Each Challenge in itself is a DAO. Henceforth, we will use Challenge and ChallengeDAO interchangeably. Both these terms refer to the same component - The Challenge.\
\
ChallengeDAO consists of three main roles -

### 1. Initiator

As name suggest, this role gets assigned to whoever initiated the Challenge. Since Initiators are the first members of the ChallengeDAO, they  are the ones who decides initial [Ownership Split](ownership-split.md) for the Assets created under this Challenge.&#x20;

{% hint style="info" %}
We have a dedicated section for to understand [Ownership Splits](ownership-split.md)
{% endhint %}

### 2. Funder

Anyone who funds a Challenge by depositing Funding Asset defined in a Challenge becomes a Funder. The amount of Ownership Shares received by a given funder for Assets created under the Challenge that they funded, depends on two factors -

1. Total Ownership Allocation for Funders of the Challenge
2. Amount that the Funder funded in that Challenge

Based on the ownership shares held by funders, they can participate in ChallengeDAO governance. &#x20;

&#x20;\
One could also create a Challenge without funding it. This is technically possible and make sense if you are working on your project (read - Challenge) and don't require funding at the moment, you can define Ownership Split accordingly. Ownership split can always change later based on governance majority. \

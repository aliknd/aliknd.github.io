---
title: "TikTokActions: A TikTok-Derived Video Dataset for Human Action Recognition"
collection: publications
link: https://aliknd.github.io/publications/2024-02-14-paper-number-5
excerpt: 'We release this dataset as a valuable resource for building domain-specific foundation models for human movement modeling tasks such as action recognition.'
date: 2024-02-14
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2402.08875'
citation: 'Qian, Y., Sun, Y., Kargarandehkordi, A., Mutlu, O. C., Surabhi, S., Chen, P., ... & Washington, P. (2024). TikTokActions: A TikTok-Derived Video Dataset for Human Action Recognition. arXiv preprint arXiv:2402.08875.'
---

The increasing variety and quantity of tagged multimedia content on platforms such as TikTok provides an opportunity to advance computer vision modeling. We have curated a distinctive dataset of 283,582 unique video clips categorized under 386 hashtags relating to modern human actions. We release this dataset as a valuable resource for building domain-specific foundation models for human movement modeling tasks such as action recognition. To validate this dataset, which we name TikTokActions, we perform two sets of experiments. First, we pretrain the state-of-the-art VideoMAEv2 with a ViT-base backbone on TikTokActions subset, and then fine-tune and evaluate on popular datasets such as UCF101 and the HMDB51. We find that the performance of the model pre-trained using our Tik-Tok dataset is comparable to models trained on larger action recognition datasets (95.3% on UCF101 and 53.24% on HMDB51). Furthermore, our investigation into the relationship between pre-training dataset size and fine-tuning performance reveals that beyond a certain threshold, the incremental benefit of larger training sets diminishes. This work introduces a useful TikTok video dataset that is available for public use and provides insights into the marginal benefit of increasing pre-training dataset sizes for video-based foundation models.

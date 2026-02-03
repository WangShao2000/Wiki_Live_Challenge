# The Voiceverse NFT Plagiarism Scandal: A Case Study in Digital Ethics, Intellectual Property, and the AI-Web3 Convergence
## 1\. Executive Summary
The **Voiceverse NFT plagiarism scandal** of January 2022 stands as a seminal event in the history of digital media, marking the violent intersection of three volatile industries: the burgeoning market for Non-Fungible Tokens (NFTs), the rapid unregulated expansion of Generative Artificial Intelligence (AI), and the established labor structures of the video game voice acting industry. The incident centered on **Voiceverse NFT**, a commercial venture by the synthetic speech company **LOVO, Inc.**, and its high-profile partnership with veteran voice actor **Troy Baker**. The initiative collapsed within two weeks following revelations that Voiceverse had misappropriated proprietary audio technology from **15.ai**, a non-commercial, academic AI research project created by an anonymous developer known as "15."

This report provides an exhaustive analysis of the scandal, tracing its origins in the "crypto-hype" cycle of late 2021, dissecting the forensic evidence of the theft, and evaluating the long-term legal consequences that culminated in the 2024 class-action lawsuit *Lehrman v. Lovo, Inc.*. Through a detailed examination of primary sources, technical logs, and court filings, the analysis demonstrates how this specific controversy exposed the systemic vulnerabilities in intellectual property law regarding AI training data—vulnerabilities that would define the "AI Boom" of the mid-2020s. Furthermore, the report explores the cultural fallout of Baker’s "Hate or Create" ultimatum, which became a defining case study in the breakdown of trust between creators and their audiences in the Web3 era.

## 2\. Contextual Framework: The Digital Landscape of Early 2022
To fully comprehend the magnitude of the Voiceverse scandal, one must first reconstruct the specific technological and economic climate of January 2022\. This period represented a unique inflection point where the speculative frenzy of the "NFT Bubble" began to collide with the nascent, yet rapidly advancing, field of deep learning-based media synthesis.

### 2.1 The Peak and Precarity of the NFT Market
By the beginning of 2022, the market for Non-Fungible Tokens (NFTs) had reached a fever pitch, with trading volumes soaring from US$82 million in 2020 to US$17 billion in 2021[1] . Proponents of the technology championed it as a revolutionary mechanism for digital ownership, promising creators—artists, musicians, and performers—a way to enforce scarcity on digital goods and secure perpetual royalties from secondary sales[2] .

However, this economic boom was accompanied by intense socio-political polarization. Critics, particularly within the gaming and tech-literate communities, viewed NFTs as environmentally catastrophic due to the high energy consumption of "Proof of Work" blockchains like Ethereum (before its "Merge" upgrade)[1] . Furthermore, the market was rife with fraud, "rug pull" exit scams, and wash trading, leading to a pervasive skepticism among consumers[1] .

In the video game industry, this tension was palpable. Major publishers who attempted to integrate NFTs faced immediate and overwhelming hostility. A notable precursor to the Voiceverse incident occurred on December 16, 2021, when the developers of *S.T.A.L.K.E.R. 2: Heart of Chernobyl* announced an NFT integration, only to cancel it less than an hour later due to a ferocious fan backlash[5] . This environment meant that any new entrant into the NFT space, especially one connected to gaming culture, was walking onto a battlefield primed for conflict.

### 2.2 The State of Generative Voice AI
Parallel to the crypto phenomenon was the quiet but rapid maturation of AI Text-to-Speech (TTS) technology. Historically, TTS relied on "concatenative synthesis," a labor-intensive process of splicing together thousands of pre-recorded phonemes. This method produced the robotic, unnatural voices associated with early GPS navigators and screen readers[6] .

The introduction of deep neural networks (DNNs) revolutionized this field. By 2020, models could learn to synthesize highly realistic speech from relatively small datasets, a process known as "voice cloning" or "style transfer." This technology promised democratization—allowing independent creators to voice their characters without expensive studio time—but also threatened the livelihoods of professional voice actors by commodifying their vocal identities[7] .

Into this volatile mix entered **15.ai**, a non-commercial research project that became a cultural phenomenon, and **Voiceverse**, a commercial entity seeking to monetize similar capabilities through the mechanism of blockchain ownership.

## 3\. Profile of Actors
The conflict was driven by three distinct entities, each representing a different ethos in the digital economy: the corporate disruptor (LOVO/Voiceverse), the established industry veteran (Troy Baker), and the independent open-source researcher (15.ai).

### 3.1 LOVO, Inc. and Voiceverse NFT
**LOVO, Inc.**, headquartered in San Francisco with roots in Seoul, was a venture-backed startup founded by Tom Lee and a team of AI experts from U.C. Berkeley[9] . Positioning itself as a leader in the "Web3" space, LOVO sought to bridge the gap between AI synthesis and the metaverse.

Their flagship initiative, **Voiceverse NFT**, was marketed as the "world's first voice NFT." The value proposition was unique: rather than buying a static JPEG image (the standard NFT use case), buyers would purchase ownership rights to a specific "AI Voice Model." This model could then be used to generate unlimited audio for podcasts, videos, or games, with the owner ostensibly receiving royalties whenever others used that voice[2] .

Financially, LOVO was aggressive. In April 2022, even amidst the fallout of the scandal, the company announced a $6.5 million Pre-Series A funding round led by Hashed, a prominent crypto investment firm[10] . This funding underscored the significant institutional capital betting on the convergence of AI and blockchain, regardless of the ethical controversies brewing on the ground.

### 3.2 15.ai: The Non-Commercial Pioneer
On the opposite end of the spectrum was **15.ai**, a project created by an anonymous researcher known as "15" (often represented by a pony avatar, reflecting the project's roots in the *My Little Pony: Friendship Is Magic* fandom)[5] .

Launched in 2020, 15.ai was a technical marvel. It demonstrated that deep learning models could generate emotionally expressive speech with as little as 15 seconds of target audio data[12] . The platform was explicitly **non-commercial**. The creator funded the substantial AWS infrastructure costs—peaking at $12,000 per month—out of personal savings from a previous startup exit[12] .

The project's Terms of Service (ToS) were simple but strict: users could generate audio for free, provided they credited 15.ai and did not use the output for commercial purposes[12] . This "hacker ethos"—free tools for the community, strict anti-corporate enclosure—garnered 15.ai a fiercely loyal following among internet subcultures, particularly the *Team Fortress 2* and *My Little Pony* communities, who used the tool to create viral memes and fan animations[14] .

### 3.3 Troy Baker: The Industry Face
**Troy Baker** is arguably one of the most recognizable voices in modern gaming. With a résumé including Joel Miller in *The Last of Us*, Booker DeWitt in *BioShock Infinite*, and Higgs in *Death Stranding*, Baker cultivated a public persona as a champion of the "actor's craft"[2] . He frequently spoke about the importance of performance capture and the human soul in storytelling.

However, Baker's relationship with his audience had shown fractures prior to 2022\. He had previously faced criticism for a 2017 music crowdfunding campaign that allegedly failed to deliver promised rewards or refunds, a point of contention that resurfaced immediately during the Voiceverse backlash[5] . His decision to partner with an AI company—technically positioning himself to sell the very thing (human voice) he advocated for—was perceived by many as a betrayal of his profession and his colleagues[5] .

## 4\. The Anatomy of the Scandal
The Voiceverse scandal unfolded with the speed and intensity characteristic of social media crises. It can be segmented into three distinct phases: The Announcement, The Revelation of Theft, and The Collapse.

### 4.1 Phase I: The "Hate or Create" Announcement (January 14, 2022\)
On the morning of January 14, 2022, Troy Baker posted a thread to Twitter announcing his partnership with Voiceverse NFT. The announcement was designed to be provocative, but it backfired spectacularly due to a specific rhetorical choice.

**The Tweet:**

*"I’m partnering with Voiceverse NFT to explore ways where together we might bring new tools to new creators to make new things, and allow everyone a chance to own & invest in the IP’s they create. We all have a story to tell. You can hate. Or you can create. What’ll it be?"* 2

Analysis of the Rhetoric:  
The phrase "You can hate. Or you can create" was interpreted as a preemptive dismissal of valid criticism. By framing skepticism of NFTs as "hate," Baker alienated the very audience he sought to engage. The dichotomy implied that those concerned about the environmental impact of blockchain or the ethics of AI were merely destructive "haters," while those buying into the scheme were "creators"[17] .  
The Immediate Backlash:  
Within hours, the tweet had generated thousands of negative responses (a "ratio"). High-profile peers and commentators weighed in.

* **Environmental Concerns:** Critics pointed out that Voiceverse relied on the Ethereum blockchain, which at the time was highly energy-intensive[3] .  
* **Economic Threat:** Voice actors and unions viewed the partnership as a "class traitor" moment. If a star like Baker normalized selling voice rights as NFTs, it could establish a precedent where lesser-known actors would be coerced into signing away their vocal rights for a pittance, leading to their eventual replacement by their own AI clones[2] .

### 4.2 Phase II: The Forensic Discovery of Theft (January 14–15, 2022\)
As the cultural backlash raged, a far more damaging technical scandal was brewing. The creator of 15.ai, alerted by the sudden visibility of Voiceverse, began investigating the company's marketing materials to understand the competing technology.

The Discovery:  
Voiceverse had posted a promotional video on Twitter featuring a "Chubbiverse" character (a cartoon cat) speaking with a synthesized voice. To the ear of 15.ai's creator, the audio artifacts—the specific digital "glitches" and cadence—were unmistakably those of the 15.ai engine[3] .  
The Forensic Evidence:  
15.ai conducted a review of their server logs. Because 15.ai stores generation requests to optimize the model, the creator was able to locate a specific entry that matched the Voiceverse audio perfectly.

* **Source Material:** The logs showed that the audio was generated using the **Twilight Sparkle** and **Rainbow Dash** voice models from the 15.ai platform[13] .  
* **Obfuscation Technique:** Voiceverse had taken the raw output from 15.ai and applied a pitch-shifting algorithm (raising the pitch) to disguise the voice. While this changed the auditory character enough to fool a casual listener, the spectral fingerprint and prosody remained identical to the 15.ai output[3] .  
* **The "Smoking Gun":** 15.ai posted a screenshot of these logs to Twitter, directly juxtaposing the timestamp of the generation with the Voiceverse marketing post. The tweet caption was stark: Voiceverse was "actively attempting to appropriate my work for their own benefit"[3] .

The Ethical Violation:  
This was not merely a copyright infringement; it was model laundering. Voiceverse was pitching investors and customers on the quality of their proprietary AI technology. By using 15.ai's output in their marketing, they were effectively presenting a competitor's free, academic work as their own commercial product. This constituted a deceptive business practice under the guise of technological innovation[5] .

### 4.3 Phase III: Admission, Confrontation, and Collapse (January 15–31, 2022\)
Faced with irrefutable evidence, Voiceverse attempted damage control. Their response, however, exacerbated the situation.

The "Marketing Team" Defense:  
Voiceverse issued a statement admitting the use of 15.ai assets but attempted to shift liability to a third party.  
*"Our marketing team had used 15.ai without proper attribution while rushing to create a technology demo..."* 5

This admission confirmed the theft but framed it as a procedural error rather than a systemic failure. The excuse—that they were "rushing"—was widely mocked. It implied that a company raising millions of dollars for "Web3 voice technology" did not actually have its own working technology ready for its launch announcement[5] .

The "Go F\* Yourself" Moment:\*\*  
In response to Voiceverse's tepid admission and promise to "rectify" the situation (which involved merely deleting the tweet), the creator of 15.ai replied with a simple, three-word tweet: "Go fuck yourself"[5] .  
This response went viral, rallying the internet around the independent developer. It symbolized the broader resentment of the "maker" community against "taker" crypto-platforms that sought to financialize the commons without contributing to it.  
Troy Baker’s Withdrawal:  
For two weeks, Troy Baker attempted to weather the storm. On the Play, Watch, Listen podcast (Jan 15), he expressed regret for the "hate or create" phrasing but defended the utility of the project for independent developers[5] . He argued that if this specific partnership wasn't the right avenue, he would find another, but he refused to immediately disavow Voiceverse[5] .  
However, as the "plagiarism" narrative solidified and mainstream outlets like *IGN*, *Eurogamer*, and *The Verge* picked up the story, the association became toxic. On January 31, 2022, Baker officially announced he was ending the partnership.

*"Intentions aside, I’ve heard you and apologize for accusing anyone of 'hating' just by simply disagreeing with me."* 16

Voiceverse claimed the split was mutual, but the project's public credibility was effectively destroyed[5] .

## 5\. Technical Analysis: The Mechanism of AI Voice Theft
To understand why this scandal terrified the voice acting industry, one must understand the technical mechanisms involved. The Voiceverse incident demonstrated how easily AI models could be used to strip-mine creative labor.

### 5.1 Voice Skins vs. Voice NFTs
Voiceverse marketed their product as "Voice NFTs." In theory, this meant a user would own a token on the blockchain (ERC-721 standard) that granted license rights to a specific "Voice Skin"[1] .

* **Voice Skin:** A set of weights and parameters in a neural network (likely a variant of Tacotron 2 or similar architecture at the time) that defines the timbre, accent, and intonation of the speaker.  
* **The Theft:** By using 15.ai's output, Voiceverse was selling the *result* of 15.ai's neural weights as a demonstration of their own. They were selling the "fruit" of 15.ai's "tree" while claiming to have grown the orchard[3] .

### 5.2 The 15.ai Architecture
15.ai was notable for its efficiency. The developer, "15," utilized a proprietary implementation of deep learning that optimized for "low-shot learning."

* **Data Requirements:** While commercial models often required hours of studio-quality audio, 15.ai could clone a voice with 15 seconds of noisy data[12] .  
* Emotional Context: The model could infer emotional states (anger, joy, sadness) even if those emotions were not present in the target's training data. This made it uniquely powerful for creative expression[12] .  
  The fact that Voiceverse—a company with millions in funding—had to steal from a solo developer's passion project highlighted a "quality gap" in the industry: open-source and passion-driven projects were often outperforming commercial "vaporware."

## 6\. Legal Implications and the 2024 Class Action
The Voiceverse scandal was not an isolated incident but a prelude to a massive legal reckoning for its parent company, LOVO, Inc. The pattern of behavior exposed in Jan 2022—appropriating voices without consent—formed the backbone of a landmark lawsuit filed two years later.

### 6.1 *Lehrman v. Lovo, Inc.* (2024)
On September 25, 2024, voice actors **Paul Skye Lehrman** and **Linnea Sage** filed a class-action lawsuit against LOVO, Inc. in the U.S. District Court for the Southern District of New York[21] .

The Plaintiffs' Case:  
Lehrman and Sage alleged that they were approached on freelance platforms (like Fiverr) to provide voice samples for "internal research" or "academic scripts." They were paid nominal fees (often under $100).

* **The Deception:** Unbeknownst to them, LOVO used these samples to train their commercial AI engine.  
* **The Discovery:** Lehrman discovered his voice being used to host a podcast about AI, while Sage found her voice listed for sale on LOVO's marketplace under a pseudonym[23] .  
* **Connection to Voiceverse:** The lawsuit cited the 2022 plagiarism of 15.ai as evidence of LOVO's "willful and systematic" disregard for intellectual property rights. It painted a picture of a company whose business model was predicated on theft[12] .

### 6.2 The July 2025 Ruling: A Legal Turning Point
In July 2025, Judge J. Paul Oetken issued a critical ruling on LOVO's motion to dismiss. This opinion established several key precedents for the AI industry[22] .

**Table 1: Key Rulings in *Lehrman v. Lovo, Inc.* (July 2025\)**

| Legal Claim | Statute / Basis | Ruling | Significance for AI Industry |
| :---- | :---- | :---- | :---- |
| **Copyright Infringement (Voice)** | US Copyright Act | **Dismissed** | Reaffirmed that a "voice" *per se* is not copyrightable; only the specific *recording* is. |
| **Copyright Infringement (Training)** | US Copyright Act | **Proceeded** | The court allowed the claim that LOVO infringed copyright by *copying* the source files into their training database without license. |
| **False Advertising** | Lanham Act | **Proceeded** | The court found it plausible that LOVO misled consumers by claiming to "own" or "license" voices they had stolen, constituting unfair competition. |
| **Right of Publicity** | NY Civil Rights Law §§ 50-51 | **Proceeded** | Rejected LOVO's defense that the statute of limitations had passed. The court ruled that every time the AI generated a new clip, it was a "republication" of the violation[24] |

This ruling was a catastrophic blow to the "move fast and break things" model of AI development. It suggested that while you cannot copyright a voice, you cannot build a business on deceiving customers about the *provenance* of that voice[25] .

## 7\. Industry Fallout and Legacy
The reverberations of the Voiceverse scandal extended far beyond the parties involved, influencing labor relations, platform policies, and the cultural perception of AI.

### 7.1 The 2023 SAG-AFTRA Strike
The anxieties articulated during the Voiceverse backlash—that AI would turn actors into training data—became the central pillar of the **2023 SAG-AFTRA strike**.

* **The Warning Shot:** Voiceverse was cited in union discussions as a "proof of concept" for the threat. It showed that companies would not self-regulate and would actively hide the source of their data[8] .  
* **The Result:** The strike resulted in new contract provisions requiring explicit consent and separate compensation for the creation of "digital replicas," protections that were directly informed by the type of exploitation seen in the LOVO/Voiceverse case[26] .

### 7.2 The Fate of the Players
* **15.ai:** Following the scandal, the service struggled with the immense server loads and the increasing toxicity of the AI space. It went offline in September 2022\. However, the project's legacy endured. In May 2025, the creator launched **15.dev**, a successor platform, continuing the mission of non-commercial, accessible synthesis[12] .  
* **Voiceverse / LOVO:** While LOVO managed to raise $6.5 million in April 2022 (post-scandal), their brand never fully recovered. They faced the costly 2024 class action. Furthermore, the confusion with the unrelated platform **Voice.com** (which shut down in 2024 27) often led to reports that Voiceverse had closed, though LOVO remained operationally active but legally besieged[28] .  
* **Troy Baker:** Baker successfully pivoted away from the scandal. By disengaging completely from the NFT space and issuing a clear apology, he retained his standing in the industry, starring in the HBO adaptation of *The Last of Us*. His case serves as a crisis management textbook example: the "Hate or Create" tweet remains a cautionary meme, but his career survived because he bowed to the collective pressure of his community[30] .

### 7.3 The Normalization of Skepticism
The lasting legacy of the Voiceverse scandal is the "inoculation" of the gaming community against Web3 and AI hype. When future projects announced "AI voices" or "NFT integration," the immediate public question became: "Where is the data from?"  
The scandal taught audiences to look for the "logs"—to demand forensic proof of ownership. It validated the "Right-Click Saver" mentality: that the technical complexity of NFTs often served to obscure simple, old-fashioned theft[2] .

## 8\. Conclusion
The Voiceverse NFT plagiarism scandal was a perfect storm that exposed the ethical vacuum at the heart of the 2022 "Web3" gold rush. It demonstrated that behind the complex jargon of "blockchain," "smart contracts," and "generative synthesis," the basic mechanisms of value creation often relied on the uncompensated appropriation of others' labor—whether that was the open-source code of a solo developer like 15.ai or the vocal performances of freelancers like Paul Skye Lehrman.

While Troy Baker's involvement brought the incident to the world stage, the true significance lies in the legal precedents it helped spawn. The forensic unmasking of Voiceverse by 15.ai proved that "AI laundering"—hiding theft behind algorithmic processing—leaves traces. The subsequent *Lehrman v. Lovo* lawsuit in 2024 and the SAG-AFTRA protections of 2023 confirmed that the law and labor unions would eventually catch up to the technology. The scandal stands as a historical marker: the moment when the "black box" of AI creation was forced open, revealing the stolen human effort inside.

## 9\. See Also
* **Non-Fungible Token (NFT):** A unique digital identifier that cannot be copied, substituted, or subdivided, that is recorded in a blockchain, and that is used to certify authenticity and ownership.  
* **Generative Artificial Intelligence:** Artificial intelligence capable of generating text, images, or other media, using generative models.  
* **Deepfake:** Synthetic media in which a person in an existing image or video is replaced with someone else's likeness.  
* **SAG-AFTRA:** The labor union representing approximately 160,000 media professionals, which struck in 2023 over AI issues.  
* **Model Laundering:** The practice of training a machine learning model on stolen or copyrighted data and then presenting the model as a proprietary creation to obscure the data's origin.


Note on Citations:  
This report synthesizes information from various documented sources identified in the research snippets, including Wikipedia archives 5, news reporting from IGN and Eurogamer 3, court documents from Lehrman v. Lovo 22, and social media archives[5] .

## References
[1] Non-fungible token \- Wikipedia, accessed December 19, 2025， [https://en.wikipedia.org/wiki/Non-fungible\_token](https://en.wikipedia.org/wiki/Non-fungible_token)  
[2] Troy Baker Announces NFT Project For His Voice, Responds To Criticisms \- GameSpot, accessed December 19, 2025， [https://www.gamespot.com/articles/troy-baker-announces-nft-project-for-his-voice-responds-to-criticisms/1100-6499648/](https://www.gamespot.com/articles/troy-baker-announces-nft-project-for-his-voice-responds-to-criticisms/1100-6499648/)  
[3] Troy Baker-backed NFT firm admits using voice lines taken from another service without permission \- Eurogamer, accessed December 19, 2025， [https://www.eurogamer.net/troy-baker-backed-nft-firm-admits-using-voice-lines-taken-from-another-service-without-permission](https://www.eurogamer.net/troy-baker-backed-nft-firm-admits-using-voice-lines-taken-from-another-service-without-permission)  
[4] Two California Men Charged in Largest NFT Scheme Prosecuted to Date, accessed December 19, 2025， [https://www.justice.gov/archives/opa/pr/two-california-men-charged-largest-nft-scheme-prosecuted-date](https://www.justice.gov/archives/opa/pr/two-california-men-charged-largest-nft-scheme-prosecuted-date)  
[5] Voiceverse NFT plagiarism scandal \- Wikipedia, accessed December 19, 2025， [https://en.wikipedia.org/wiki/Voiceverse\_NFT\_plagiarism\_scandal](https://en.wikipedia.org/wiki/Voiceverse_NFT_plagiarism_scandal)  
[6] Preventing the Harms of AI-enabled Voice Cloning | Federal Trade Commission, accessed December 19, 2025， [https://www.ftc.gov/policy/advocacy-research/tech-at-ftc/2023/11/preventing-harms-ai-enabled-voice-cloning](https://www.ftc.gov/policy/advocacy-research/tech-at-ftc/2023/11/preventing-harms-ai-enabled-voice-cloning)  
[7] Ethical concerns related to voice cloning & misuse of AI-generated Voiceovers, accessed December 19, 2025， [https://www.pixazo.ai/blog/ethical-concerns-ai-generated-voiceovers](https://www.pixazo.ai/blog/ethical-concerns-ai-generated-voiceovers)  
[8] "The effect is, frankly, catastrophic" \- the voice actors and unions fighting back against gaming's controversial use of AI \- Eurogamer, accessed December 19, 2025， [https://www.eurogamer.net/video-game-publishers-developers-normalise-ai-tools-voice-work-ethical-unions-actors-fighting-back](https://www.eurogamer.net/video-game-publishers-developers-normalise-ai-tools-voice-work-ethical-unions-actors-fighting-back)  
[9] LOVO Raises $6.5M Pre-Series A to Develop the Voice of Web 3.0 \- Chainwire, accessed December 19, 2025， [https://chainwire.org/2022/04/07/lovo-raises-6-5m-pre-series-a-to-develop-the-voice-of-web-3-0/](https://chainwire.org/2022/04/07/lovo-raises-6-5m-pre-series-a-to-develop-the-voice-of-web-3-0/)  
[10] LOVO Beefs Up Voiceverse Development With $6.5M Pre-Series A Round Led By Hashed, accessed December 19, 2025， [https://www.nftgators.com/lovo-beefs-up-voiceverse-development-with-6-5m-pre-series-a-round-led-by-hashed/](https://www.nftgators.com/lovo-beefs-up-voiceverse-development-with-6-5m-pre-series-a-round-led-by-hashed/)  
[11] World's First Voice NFT sells out in 10 minutes\! \- The Korea Herald, accessed December 19, 2025， [https://www.koreaherald.com/article/2777830](https://www.koreaherald.com/article/2777830)  
[12] 15.ai \- Wikipedia, accessed December 19, 2025， [https://en.wikipedia.org/wiki/15.ai](https://en.wikipedia.org/wiki/15.ai)  
[13] 15.ai: All about 15.ai and the best alternative | Speechify, accessed December 19, 2025， [https://speechify.com/blog/15-ai/](https://speechify.com/blog/15-ai/)  
[14] 15.AI is some SCARY STUFF\!\! Discussing the implications of AI voice generation\! \- YouTube, accessed December 19, 2025， [https://www.youtube.com/watch?v=FUvqiJo9yUw](https://www.youtube.com/watch?v=FUvqiJo9yUw)  
[15] What's going on with Troy Baker and why are people mad at him? : r/OutOfTheLoop \- Reddit, accessed December 19, 2025， [https://www.reddit.com/r/OutOfTheLoop/comments/sewkvs/whats\_going\_on\_with\_troy\_baker\_and\_why\_are\_people/](https://www.reddit.com/r/OutOfTheLoop/comments/sewkvs/whats_going_on_with_troy_baker_and_why_are_people/)  
[16] Troy Baker ends partnership with NFT firm and says sorry for 'hate or create' comment | VGC, accessed December 19, 2025， [https://www.videogameschronicle.com/news/troy-baker-ends-partnership-with-nft-firm-and-says-sorry-for-hate-or-create-comment/](https://www.videogameschronicle.com/news/troy-baker-ends-partnership-with-nft-firm-and-says-sorry-for-hate-or-create-comment/)  
[17] Troy Baker NFT News \- "You can hate or you can create" : r/thelastofus \- Reddit, accessed December 19, 2025， [https://www.reddit.com/r/thelastofus/comments/s3y6vf/troy\_baker\_nft\_news\_you\_can\_hate\_or\_you\_can\_create/](https://www.reddit.com/r/thelastofus/comments/s3y6vf/troy_baker_nft_news_you_can_hate_or_you_can_create/)  
[18] Troy Baker's Partner Voice NFT Platform Voiceverse Admits to ..., accessed December 19, 2025， [https://www.nftgators.com/troy-bakers-partner-voice-nft-platform-voiceverse-admits-to-stealing-audio/](https://www.nftgators.com/troy-bakers-partner-voice-nft-platform-voiceverse-admits-to-stealing-audio/)  
[19] Voiceverse NFT Service Reportedly Uses Stolen Technology from 15ai \[UPDATE\], accessed December 19, 2025， [https://wccftech.com/voiceverse-nft-service-uses-stolen-technology-from-15ai/](https://wccftech.com/voiceverse-nft-service-uses-stolen-technology-from-15ai/)  
[20] Voice Actor Troy Baker Pulls Out of NFT Partnership \[Update\] \- IGN, accessed December 19, 2025， [https://www.ign.com/articles/troy-baker-nft-voiceverse-pulls-out](https://www.ign.com/articles/troy-baker-nft-voiceverse-pulls-out)  
[21] Actors file class action claiming AI startup stole voices, accessed December 19, 2025， [https://topclassactions.com/lawsuit-settlements/class-action-news/actors-file-class-action-claiming-ai-startup-stole-voices/](https://topclassactions.com/lawsuit-settlements/class-action-news/actors-file-class-action-claiming-ai-startup-stole-voices/)  
[22] 1 UNITED STATES DISTRICT COURT SOUTHERN DISTRICT OF NEW YORK PAUL LEHRMAN, et al., Plaintiffs, \-v- LOVO, INC., Defendant. 24-CV-, accessed December 19, 2025， [https://nysd.uscourts.gov/sites/default/files/2025-07/Lovo%20v%20Lehrman.pdf](https://nysd.uscourts.gov/sites/default/files/2025-07/Lovo%20v%20Lehrman.pdf)  
[23] VO artists allege an AI company cloned their voices in lawsuit \- Marketplace, accessed December 19, 2025， [https://www.marketplace.org/episode/voice-over-artists-allege-an-ai-company-cloned-their-voices-in-lawsuit](https://www.marketplace.org/episode/voice-over-artists-allege-an-ai-company-cloned-their-voices-in-lawsuit)  
[24] New York Court Tackles the Legality of AI Voice Cloning | Insights | Skadden, Arps, Slate, Meagher & Flom LLP, accessed December 19, 2025， [https://www.skadden.com/insights/publications/2025/07/new-york-court-tackles-the-legality-of-ai-voice-cloning](https://www.skadden.com/insights/publications/2025/07/new-york-court-tackles-the-legality-of-ai-voice-cloning)  
[25] Lehrman v. Lovo Inc. | Loeb & Loeb LLP, accessed December 19, 2025， [https://www.loeb.com/en/insights/publications/2025/07/lehrman-v-lovo-inc](https://www.loeb.com/en/insights/publications/2025/07/lehrman-v-lovo-inc)  
[26] Voice actors and generative AI: Legal challenges and emerging protections \- IAPP, accessed December 19, 2025， [https://iapp.org/news/a/voice-actors-and-generative-ai-legal-challenges-and-emerging-protections](https://iapp.org/news/a/voice-actors-and-generative-ai-legal-challenges-and-emerging-protections)  
[27] NFT Marketplace Voice Announces its Closure; Assures Asset Safety By Coin Edition, accessed December 19, 2025， [https://ng.investing.com/news/cryptocurrency-news/nft-marketplace-voice-announces-its-closure-assures-asset-safety-1058795](https://ng.investing.com/news/cryptocurrency-news/nft-marketplace-voice-announces-its-closure-assures-asset-safety-1058795)  
[28] NFT Marketplace Voice Announces Its Closure \- Cryptonews.net, accessed December 19, 2025， [https://cryptonews.net/news/nft/24669372/](https://cryptonews.net/news/nft/24669372/)  
[29] Voiceverse \- NFT Project | Crypto-Fundraising, accessed December 19, 2025， [https://crypto-fundraising.info/projects/voiceverse](https://crypto-fundraising.info/projects/voiceverse)  
[30] After backlash, Troy Baker announces he will no longer be partnering with the "voice NFT" project Voiceverse, accessed December 19, 2025， [https://www.web3isgoinggreat.com/single/2022-01-31-3](https://www.web3isgoinggreat.com/single/2022-01-31-3)  
[31] Journalistic hype: WIRED's coverage of NFTs, metaverses and generative AI, accessed December 19, 2025， [https://hypestudies.org/media/pages/resources/journalistic-hype-wired-s-coverage-of-nfts-metaverses-and-generative-ai/abeaa7c3fd-1753267690/09\_etac6\_echauri\_journalistic-hype.pdf](https://hypestudies.org/media/pages/resources/journalistic-hype-wired-s-coverage-of-nfts-metaverses-and-generative-ai/abeaa7c3fd-1753267690/09_etac6_echauri_journalistic-hype.pdf)

---
title: Expanding the Thresholds of IDP Through Vital Information Harvesting, Object Spotting, and Lexical Analysis
date: 2024-08-21T17:45:05.017Z
updated: 2024-08-22T17:45:05.017Z
categories:
  - abbyy
thumbnail: https://thmb.techidaily.com/b9b7665577f766113660c4c3c2e978c3705b755579fa83e6d4b9ffe0b41b7175.jpg
---

## Expanding the Thresholds of IDP Through Vital Information Harvesting, Object Spotting, and Lexical Analysis

[Back to The Intelligent Enterprise](https://tools.techidaily.com/abbyy/products/)

## Pushing the Boundaries of IDP: Object Detection, Word Recognition, and Key-Value Extraction

###### by Max Vermeir, Senior Director of AI Strategy

One of the most defining characteristics of IDP is the strategic use of AI as the core foundation for automating document-centric tasks. ABBYY developers explain three exciting new AI models that are pushing the boundaries of IDP in key-value extraction, object detection, and word recognition.

One of the most defining characteristics of intelligent document processing (IDP) is the strategic use of artificial intelligence (AI) as the core foundation for automating document-centric tasks. AI models and algorithms enable contextual understanding to improve speed and accuracy, driving business value for customers with document-heavy workflows. 

[ABBYY Vantage](https://tools.techidaily.com/abbyy/products/) exemplifies this concept with its library of pre-trained “skills,” also known as pre-trained AI document processing models. By narrowing the scope of an AI solution to excel at a specific task, these purpose-built AI skills work efficiently to accelerate outcomes in specialized contexts. 

In a recent showcase session presented by the ABBYY research and development team, our developers Konstantin Anisimovich, Evgenii Orlov, Ivan Zagaynov, and Andrew Upshinskiy explained three exciting new AI models that are pushing the boundaries of IDP in key-value extraction, object detection, and word recognition.

#### 1\. Key-value extraction 

Identifying key information is an essential Vantage skill that allows for actionable data to be extracted from a document type. Document-specific models at the core of the skill are trained to identify fields such as “company name,” “address,” or “zip code,” enabling the corresponding values to be extracted. Separate models are made for different document types, determining the fields that the model will look for.

This process is known as **key-value pairs extraction**. This entails finding all possible “keys,” or field names; all possible “values,” which are the contents of those fields; as well as the associations between keys and corresponding values. But how is the model trained to make these associations?

Taking a large, general key-value extraction model and training it on a set of documents allows the model to build proficiency in automatic markup. Through a process called **knowledge distillation**, or the transferring of knowledge from a large AI model to a smaller one, more specialized AI models can be built that operate at a lower computational cost and greater inference speeds, than their larger counterparts.

ABBYY’s current path towards this solution consists of two independent workflows: entity extraction and linking models for general documents, and key summarization and QA models for text-heavy documents such as contracts. Both models are based on the transformer architecture that is ubiquitous in modern neural networks, e.g., the GPT-family and other LLMs.

![pushing-the-boundaries-of-idp-2](https://content.abbyy.com/-/media/project/abbyy/abbyy/insights/intelligent-enterprise/content-media/pushing-the-boundaries-of-idp-2.png)

The image above portrays a form-like document where green highlights indicate keys, and yellow highlights indicate values that must be extracted from their respective keys. In a form, there are visual indicators such as layouts and blank cells that suggest where key-values lie. The world classification model tags each word as either a background or a part of a key or value, while the entity linking model combines the tagged words into key/value sequences and matches them together. Within this workflow, text is processed by a RoBERTa transformer, while visual data (images) are processed by a compact YOLOv8 model.

For text-heavy documents, a text summarization model extracts a list of all keys from the document, and a question-answering model finds corresponding value excerpts using information about the key. Once again, two separate models are used in this workflow: for key extraction, an encoder-decoder architecture uses a multimodal LayoutLM-like transformer encoder to extract rich features from the data, and a BART transformer decoder extracts relevant key word sequences using the encoded data. The value extraction model is based on a RoBERTa transformer and employs query paraphrasing and adversarial data to enhance performance.

Webinar

#### The AI within Your IDP Platform

[Learn more](https://tools.techidaily.com/abbyy/products/)

#### 2\. Detecting objects in a document image

Object detection is a crucial stage of document processing, as elementary objects must eventually be extracted from the document. This entails estimating the size of the text, correcting the skew of a page, adjusting images to a normalized state, and other variables before objects can be extracted.

A document can be thought of as a “bag of objects,” with such objects including signatures, stamps, checkmarks, separators, barcodes, printed and handwritten text, and other possible entities.

Historically, there have been two approaches to this detection: classic methods and neural networks.

Classic methods are based on well-known and trusted algorithms but tend to be limited in their ability to handle photos and corrupted documents. This can introduce complications when dealing with shadows, distortion, and other forms of visual noise, impacting results in the object detection stage. Neural networks, by contrast, are a state-of-the-art solution that ABBYY has already used for over five years, yielding optimal results in detecting various kinds of objects. However, this requires a neural network for each object type, making this approach unfeasible when detecting multiple object varieties.

As such, ABBYY came to a solution involving a universal feature extractor common to several object detection nets within a neural network. This “backbone net” delegates feature extraction to several detection heads, each with a unique architecture allowing them to detect a specific object.

To consume less processing power in contexts requiring simultaneous data processing, this solution breaks document pages into several overlapping stripes, preserving objects that may occur at the boundary of each section. After processing each stripe, the contained objects are fed to detection heads and used for future tasks such as maintaining document structure or reconstructing paragraphs and tables. This process is called single-page parallel processing, as each striped section of a document can be processed by their respective detection heads in parallel.

#### 3\. Advanced word recognition

Traditional OCR involves an input of a line image containing text that then yields an output of a Unicode text sequence. The classic approach segments to approximate one-word fragments, finds the hypothesis for character segmentation points using a linear division graph, and finally constructs words from these hypotheses.

This approach can have complications. Segmentation points are often found heuristically; when the heuristic assumption is inadequate, the process will not work. In some languages, like Arabic and Bengali, there isn’t an easy heuristic case. This is also the case for handwritten text, which would require a level of script accuracy that is rare in handwriting.

As such, ABBYY developed an end-to-end approach for both handwritten and printed text recognition. An entire text sequence is extracted at once, removing the need for establishing boundaries within the document.

In printed cases, these documents are easy to identify elements and markup accordingly. This is an easier task for a neural network—the scan quality rate of the Latin model is 99.8 percent. The only flaw is inherent to the speed/quality balance. 

The architecture for end-to-end OCR generally consists of three parts: the backbone (visual transformer), which is responsible for image extraction; sequential modeling (transformer encoder), which is needed for some contextual features in an overall sequence; and the decoder, which is the algorithm determining how the text is ultimately written considering the feature set and previous steps in the process. This pipeline is then supplemented with ABBYY’s LLM that takes into account all the context of the recognition process and provides enhanced output of the recognized text, leading to incredible accuracy rates, especially in low-quality documents.

#### Evolving IDP: driving efficiency and versatility

The advances to ABBYY’s AI models reflect enterprises’ increasing need for agility and efficiency in document processing, not only in processing time, but also in energy consumption and general versatility. 

By broadening the capabilities of modern OCR with improved object detection, more inclusive word recognition, and the reliable extraction of actionable key values, ABBYY is expanding the scope of how intelligent document processing can transform business-critical processes.

Visit [abbyy.com/vantage](https://tools.techidaily.com/abbyy/products/) to learn more about purpose-built AI in IDP.

#### Subscribe for updates

Get updated on the latest insights and perspectives for business & technology leaders

First name\*

Last name

E-mail\*

Сountry\*

СountryAfghanistanAland IslandsAlbaniaAlgeriaAmerican SamoaAndorraAngolaAnguillaAntarcticaAntigua and BarbudaArgentinaArmeniaArubaAustraliaAustriaAzerbaijanBahamasBahrainBangladeshBarbadosBelgiumBelizeBeninBermudaBhutanBoliviaBonaire, Sint Eustatius and SabaBosnia and HerzegovinaBotswanaBouvet IslandBrazilBritish Indian Ocean TerritoryBritish Virgin IslandsBrunei DarussalamBulgariaBurkina FasoBurundiCambodiaCameroonCanadaCape VerdeCayman IslandsCentral African RepublicChadChileChinaChristmas IslandCocos (Keeling) IslandsColombiaComorosCongo (Brazzaville)Congo, (Kinshasa)Cook IslandsCosta RicaCroatiaCuraçaoCyprusCzech RepublicCôte d'IvoireDenmarkDjiboutiDominicaDominican RepublicEcuadorEgyptEl SalvadorEquatorial GuineaEritreaEstoniaEthiopiaFalkland Islands (Malvinas)Faroe IslandsFijiFinlandFranceFrench GuianaFrench PolynesiaFrench Southern TerritoriesGabonGambiaGeorgiaGermanyGhanaGibraltarGreeceGreenlandGrenadaGuadeloupeGuamGuatemalaGuernseyGuineaGuinea-BissauGuyanaHaitiHeard and Mcdonald IslandsHoly See (Vatican City State)HondurasHong Kong, SAR ChinaHungaryIcelandIndiaIndonesiaIraqIrelandIsle of ManIsraelITJamaicaJapanJerseyJordanKazakhstanKenyaKiribatiKorea (South)KuwaitKyrgyzstanLao PDRLatviaLebanonLesothoLiberiaLibyaLiechtensteinLithuaniaLuxembourgMacao, SAR ChinaMacedonia, Republic ofMadagascarMalawiMalaysiaMaldivesMaliMaltaMarshall IslandsMartiniqueMauritaniaMauritiusMayotteMexicoMicronesia, Federated States ofMoldovaMonacoMongoliaMontenegroMontserratMoroccoMozambiqueMyanmarNamibiaNauruNepalNetherlandsNetherlands AntillesNew CaledoniaNew ZealandNicaraguaNigerNigeriaNiueNorfolk IslandNorthern Mariana IslandsNorwayOmanPakistanPalauPalestinian TerritoryPanamaPapua New GuineaParaguayPeruPhilippinesPitcairnPolandPortugalPuerto RicoQatarRomaniaRwandaRéunionSaint HelenaSaint Kitts and NevisSaint LuciaSaint Pierre and MiquelonSaint Vincent and GrenadinesSaint-BarthélemySaint-Martin (French part)SamoaSan MarinoSao Tome and PrincipeSaudi ArabiaSenegalSerbiaSeychellesSierra LeoneSingaporeSint Maarten (Dutch part)SlovakiaSloveniaSolomon IslandsSouth AfricaSouth Georgia and the South Sandwich IslandsSouth SudanSpainSri LankaSurinameSvalbard and Jan Mayen IslandsSwazilandSwedenSwitzerlandTaiwan, Republic of ChinaTajikistanTanzania, United Republic ofThailandTimor-LesteTogoTokelauTongaTrinidad and TobagoTunisiaTurkeyTurks and Caicos IslandsTuvaluUgandaUkraineUnited Arab EmiratesUnited KingdomUnited States of AmericaUruguayUS Minor Outlying IslandsUzbekistanVanuatuVenezuela (Bolivarian Republic)Viet NamVirgin Islands, USWallis and Futuna IslandsWestern SaharaZambiaZimbabwe

* I have read and agree with the [Privacy policy](https://tools.techidaily.com/abbyy/products/) and the [Cookie policy](https://tools.techidaily.com/abbyy/products/).\*

* I agree to receive email updates from ABBYY Solutions Ltd. such as news related to ABBYY Solutions Ltd. products and technologies, invitations to events and webinars, and information about whitepapers and content related to ABBYY Solutions Ltd. products and services.  
    
I am aware that my consent could be revoked at any time by clicking the unsubscribe link inside any email received from ABBYY Solutions Ltd. or via [ABBYY Data Subject Access Rights Form](https://tools.techidaily.com/abbyy/products/).

Referrer

Query string

GA Client ID

UTM Campaign Name

UTM Source

UTM Medium

UTM Content

ITM Source

Page URL

Captcha Score

Connect with us

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-in-2024-heaviest-airborran-aerial-haulers-ultimate-choices/"><u>[New] In 2024, Heaviest Airborran Aerial Haulers - Ultimate Choices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-thankful-innovations-premium-and-budget-outro-themes/"><u>[New] Thankful Innovations  Premium & Budget Outro Themes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-economic-blueprint-for-music-video-filming/"><u>[New] The Economic Blueprint for Music Video Filming</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-quest-achieving-immaculate-upconversion-from-sdr-to-hdri/"><u>[New] The Ultimate Quest  Achieving Immaculate Upconversion From SDR to HDRI</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-top-picks-for-novice-gopro-enthusiasts/"><u>[New] Top Picks for Novice GoPro Enthusiasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-subtle-sound-shifts-in-garageband-productions/"><u>[Updated] 2024 Approved  Subtle Sound Shifts in Garageband Productions</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-enhancing-engagement-through-thoughtful-youtube-tags-for-2024/"><u>[Updated] Enhancing Engagement Through Thoughtful YouTube Tags for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-from-live-to-recording-maximizing-your-gaming-sessions-value/"><u>[Updated] From Live to Recording  Maximizing Your Gaming Sessions' Value</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-art-of-leading-lines-crafting-images-on-iphones/"><u>[Updated] The Art of Leading Lines  Crafting Images on iPhones</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-encyclopedia-of-motion-sensing-types-and-applications/"><u>[Updated] The Encyclopedia of Motion Sensing  Types & Applications</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-to-6-best-nft-services-for-creative-geniuses/"><u>[Updated] The Ultimate Guide to 6 Best NFT Services for Creative Geniuses</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-list-10-text-effects-to-elevate-your-clips/"><u>[Updated] The Ultimate List  10 Text Effects to Elevate Your Clips</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-tier-strategies-for-flawless-srt-file-integration-on-vero-and-tumblr/"><u>[Updated] Top-Tier Strategies for Flawless SRT File Integration on Vero & Tumblr</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-collection-top-notch-free-meme-designs/"><u>[Updated] Ultimate Collection  Top-Notch FREE Meme Designs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unleash-creativity-with-animated-gifs/"><u>[Updated] Unleash Creativity with Animated GIFS</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-quickcapture-ultimate-scan/"><u>2024 Approved  QuickCapture Ultimate Scan</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-complete-guide-to-upgrading-mp4-with-premium-srt-sound/"><u>2024 Approved  The Complete Guide to Upgrading MP4 With Premium SRT Sound</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-7-sites-for-swapping-outringtone-files-on-snapchat/"><u>2024 Approved  Top 7 Sites for Swapping Outringtone Files on Snapchat</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-clearer-eliminate-backgrounds-effectively/"><u>2024 Approved  Ultimate Clearer  Eliminate Backgrounds Effectively</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-united-creatives-brands-meet-youtube/"><u>2024 Approved  United Creatives  Brands Meet YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-best-free-worldwide-calling-applications-we-love/"><u>Discover the Best Free Worldwide Calling Applications We Love!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-honor-v-purse-by-drfone-android/"><u>Full Guide to Unlock Your Honor V Purse</u></a></li>
<li><a href="https://win-answers.techidaily.com/getting-apex-legends-running-again-quick-fixes-for-launch-problems/"><u>Getting Apex Legends Running Again: Quick Fixes for Launch Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-data-from-iphone-12-mini-using-stellar-data-recovery-for-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Data from iPhone 12 mini using Stellar Data Recovery for iPhone? | Stellar</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-reinstall-hardware-drivers-on-windows-11107-by-drivereasy-guide/"><u>How to use Device Manager to reinstall hardware drivers on Windows 11/10/7</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-8-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone 8 Without a Home Button</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-total-360-giroptic-vr-capture-examination/"><u>In 2024, Total 360 Giroptic VR Capture Examination</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tune-into-the-beats-with-these-free-online-scanners/"><u>In 2024, Tune Into the Beats with These Free Online Scanners</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unveiling-your-design-how-to-eliminate-backgrounds-in-figma/"><u>In 2024, Unveiling Your Design  How To Eliminate Backgrounds in Figma</u></a></li>
<li><a href="https://techtrends.techidaily.com/making-sense-of-staying-connected-a-guide-to-understanding-t-mobiles-domestic-roaming-plan/"><u>Making Sense of Staying Connected: A Guide to Understanding T-Mobile's Domestic Roaming Plan</u></a></li>
<li><a href="https://extra-skills.techidaily.com/sculpting-digital-landscapes-with-windows-10s-latest-features-for-2024/"><u>Sculpting Digital Landscapes with Windows 10'S Latest Features for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/strategic-sharing-of-tiktok-content-on-twitter-for-2024/"><u>Strategic Sharing of TikTok Content on Twitter for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/"><u>The Ultimate Step-by-Step Guide to Kinemaster's Green Screen Mastery for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-guide-to-top-sierra-dvd-makers-for-2024/"><u>Ultimate Guide to Top Sierra DVD Makers for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
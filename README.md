# HackTricks Cloud

<details>

<summary><strong>AWS हैकिंग सीखें शून्य से लेकर हीरो तक</strong> <a href="https://training.hacktricks.xyz/courses/arte"><strong>htARTE (HackTricks AWS Red Team Expert)</strong></a><strong> के साथ!</strong></summary>

HackTricks का समर्थन करने के अन्य तरीके:

* यदि आप अपनी **कंपनी का विज्ञापन HackTricks में देखना चाहते हैं** या **HackTricks को PDF में डाउनलोड करना चाहते हैं** तो [**सब्सक्रिप्शन प्लान्स**](https://github.com/sponsors/carlospolop) देखें!
* [**आधिकारिक PEASS & HackTricks स्वैग**](https://peass.creator-spring.com) प्राप्त करें
* [**The PEASS Family**](https://opensea.io/collection/the-peass-family) की खोज करें, हमारा विशेष [**NFTs**](https://opensea.io/collection/the-peass-family) संग्रह
* 💬 [**Discord समूह**](https://discord.gg/hRep4RUj7f) में शामिल हों या [**टेलीग्राम समूह**](https://t.me/peass) में या मुझे **Twitter** 🐦 पर [**@carlospolopm**](https://twitter.com/carlospolopm) पर **फॉलो करें**.
* **अपनी हैकिंग ट्रिक्स साझा करें, HackTricks** और [**HackTricks Cloud**](https://github.com/carlospolop/hacktricks-cloud) github repos में PRs सबमिट करके.

</details>

<figure><img src=".gitbook/assets/cloud.gif" alt=""><figcaption></figcaption></figure>

_Hacktricks logos & motion designed by_ [_@ppiernacho_](https://www.instagram.com/ppieranacho/)_._

{% hint style="success" %}
इस पृष्ठ पर आपका स्वागत है जहां आपको CI/CD & Cloud से संबंधित प्रत्येक **हैकिंग ट्रिक/तकनीक/जो भी** मिलेगा जो मैंने **CTFs**, **वास्तविक** जीवन **पर्यावरण**, **शोध** करते हुए, और **पढ़ते हुए** शोध और समाचारों से सीखा है.
{% endhint %}

## **Pentesting CI/CD Methodology**

**HackTricks CI/CD Methodology में आपको CI/CD गतिविधियों से संबंधित इंफ्रास्ट्रक्चर को pentest करने का तरीका मिलेगा.** एक **परिचय के लिए** निम्नलिखित पृष्ठ पढ़ें:

{% content-ref url="pentesting-ci-cd/pentesting-ci-cd-methodology.md" %}
[pentesting-ci-cd-methodology.md](pentesting-ci-cd/pentesting-ci-cd-methodology.md)
{% endcontent-ref %}

## Pentesting Cloud Methodology

**HackTricks Cloud Methodology में आपको क्लाउड पर्यावरणों को pentest करने का तरीका मिलेगा.** एक **परिचय के लिए** निम्नलिखित पृष्ठ पढ़ें:

{% content-ref url="pentesting-cloud/pentesting-cloud-methodology.md" %}
[pentesting-cloud-methodology.md](pentesting-cloud/pentesting-cloud-methodology.md)
{% endcontent-ref %}

## License

**Copyright © Carlos Polop 2023. जहां अन्यथा निर्दिष्ट नहीं है (पुस्तक में कॉपी की गई बाहरी जानकारी मूल लेखकों की है), [**HACK TRICKS CLOUD**](https://github.com/carlospolop/hacktricks-cloud) पर Carlos Polop का टेक्स्ट**[ **Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**](https://creativecommons.org/licenses/by-nc/4.0/)** के तहत लाइसेंस प्राप्त है.**\
**यदि आप इसे व्यावसायिक उद्देश्यों के लिए उपयोग करना चाहते हैं, तो मुझसे संपर्क करें.**

## **Disclaimer**

{% hint style="danger" %}
यह पुस्तक, 'HackTricks Cloud,' केवल शैक्षिक और सूचनात्मक उद्देश्यों के लिए है। इस पुस्तक में निहित सामग्री 'जैसी है' आधार पर प्रदान की जाती है, और लेखक और प्रकाशक इसकी पूर्णता, सटीकता, विश्वसनीयता, उपयुक्तता, या इस पुस्तक में निहित जानकारी, उत्पादों, सेवाओं, या संबंधित ग्राफिक्स की उपलब्धता के बारे में कोई प्रतिनिधित्व या वारंटी नहीं देते हैं। इसलिए इस जानकारी पर आपका निर्भर होना पूरी तरह से आपके अपने जोखिम पर है।

लेखक और प्रकाशक किसी भी नुकसान या क्षति के लिए, इसमें सीमितता के बिना, अप्रत्यक्ष या परिणामी नुकसान या क्षति, या इस पुस्तक के उपयोग से उत्पन्न होने वाले डेटा या लाभ के किसी भी नुकसान या क्षति के लिए किसी भी घटना में उत्तरदायी नहीं होंगे।

इसके अलावा, इस पुस्तक में वर्णित तकनीकें और युक्तियां केवल शैक्षिक और सूचनात्मक उद्देश्यों के लिए प्रदान की जाती हैं, और किसी भी अवैध या दुर्भावनापूर्ण गतिविधियों के लिए उपयोग नहीं की जानी चाहिए। लेखक और प्रकाशक किसी भी अवैध या अनैतिक गतिविधियों का समर्थन या संवर्धन नहीं करते हैं, और इस पुस्तक में निहित जानकारी का कोई भी उपयोग उपयोगकर्ता के अपने जोखिम और विवेक पर है।

उपयोगकर्ता इस पुस्तक में निहित जानकारी के आधार पर की गई किसी भी कार्रवाई के लिए अकेले जिम्मेदार है, और यहां वर्णित किसी भी तकनीक या युक्तियों को लागू करने का प्रयास करते समय हमेशा पेशेवर सलाह और सहायता लेनी चाहिए।

इस पुस्तक का उपयोग करके, उपयोगकर्ता इस पुस्तक के उपयोग से उत्पन्न होने वाले किसी भी नुकसान, हानि, या क्षति के लिए लेखकों और प्रकाशकों को किसी भी और सभी दायित्व और जिम्मेदारी से मुक्त करने के लिए सहमत होता है।
{% endhint %}

<details>

<summary><strong>AWS हैकिंग सीखें शून्य से लेकर हीरो तक</strong> <a href="https://training.hacktricks.xyz/courses/arte"><strong>htARTE (HackTricks AWS Red Team Expert)</strong></a><strong> के साथ!</strong></summary>

HackTricks का समर्थन करने के अन्य तरीके:

* यदि आप अपनी **कंपनी का विज्ञापन HackTricks में देखना चाहते हैं** या **HackTricks को PDF में डाउनलोड करना चाहते हैं** तो [**सब्सक्रिप्शन प्लान्स**](https://github.com/sponsors/carlospolop) देखें!
* [**आधिकारिक PEASS & HackTricks स्वैग**](https://peass.creator-spring.com) प्राप्त करें
* [**The PEASS Family**](https://opensea.io/collection/the-peass-family) की खोज करें, हमारा विशेष [**NFTs**](https://opensea.io/collection/the-peass-family) संग्रह
* 💬 [**Discord समूह**](https://discord.gg/hRep4RUj7f) में शामिल हों या [**टेलीग्राम समूह**](https://t.me/peass) में या मुझे **Twitter** 🐦 पर [**@carlospolopm**](https://twitter.com/carlospolopm) पर **फॉलो करें**.
* **अपनी हैकिंग ट्रिक्स साझा करें, HackTricks** और [**HackTricks Cloud**](https://github.com/carlospolop/hacktricks-cloud) github repos में PRs सबमिट करके.

</details>

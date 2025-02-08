---
title: "What is OSINT?"
source: "https://www.varonis.com/blog/what-is-osint"
author:
  - "[[Kody Kinzie]]"
published: 2020-06-17
created: 2024-12-21
description: "Open source intelligence is often utilized by hackers and red teams to leverage public data while conducting investigations, often using database searches."
tags:
  - "clippings"
---
OSINT stands for open source intelligence and refers to the practice of collecting data from free sources that are available to the general public. As information becomes more available from a vast number of sources, skilled researchers can often find nearly any type of data they’re looking for, provided they know where to look. These sources include both public and private databases that hackers, journalists, spies, and ordinary people all use to do the work of collecting information every day.

Much of this information simply isn’t able to be retrieved through search engines and requires knowledge of where the right database is located to get the right answers. Fortunately, there are a multitude of tools that both beginners and seasoned investigators can take advantage of to use OSINT sources while conducting research.

In this article, we'll cover the following:

- [What should I do for OSINT to protect my organization?](https://www.varonis.com/blog/#investigation)
- [How to conduct an OSINT investigation](https://www.varonis.com/blog/#conduct)
- [OSINT Frameworks & Tools](https://www.varonis.com/blog/#tools)
- [OSINT Techniques](https://www.varonis.com/blog/#tech)
- [OSINT, SOCMINT, & HUMINT](https://www.varonis.com/blog/#osh)
- [OSINT on Phone Numbers](https://www.varonis.com/blog/#phone)
- [OSINT on Names](https://www.varonis.com/blog/#names)
- [OSINT on Businesses](https://www.varonis.com/blog/#business)
- [OSINT on Websites](https://www.varonis.com/blog/#websites)
- [Resources for OSINT research](https://www.varonis.com/blog/#research)
- [Dangers of OSINT Research](https://www.varonis.com/blog/#dangers)
- [OSINT Regulations](https://www.varonis.com/blog/#regulations)
- [Examples of OSINT Investigations](https://www.varonis.com/blog/#examples)
- [Who Uses OSINT?](https://www.varonis.com/blog/#who)

## What Should I Do for OSINT to Protect My Organization?

Every organization creates data, and much of this data may be public if it’s produced or recorded by a local or state government. Aside from business data, technical data from registration or development of websites or products can expose information about the internal workings of an organization that might otherwise be impossible to find.

The first thing to know about OSINT is that it cuts both ways, and the same data used to learn about a competitor can also be used to infer information about your company or organization. It can be incredibly rewarding to discover what information about you might be more public than you expect and understand how an outsider could know internal details about your organization that make it easier to attack.

## How Do I Conduct an OSINT Investigation?

An OSINT investigation starts with answering an answerable question. Because there is no shortage of data out there, it’s easy to get lost in all the noise if what you’re looking for isn’t clear and answerable in the first place. An example of this might be questioning “is New York safer than Los Angeles?” versus “Have reports of police misconduct increased in Los Angeles county since 1999?” One question calls for an opinion and is difficult to answer, where the second can be easily answered by finding the right record holder.

After establishing the question to answer, the next step is to identify the most likely owner of the best quality data. Primary source information like government or corporate data are the best sources, followed by information created by trade-based organizations or non-governmental agencies (NGO’s) related to the industry or trade your question is related to. Finally, third-party aggregators of data can provide useful links back to a primary source of data, although this “tertiary” data cannot be used as evidence. 

Generally, an investigation will develop an understanding of a subject by asking answerable questions and using the best quality answers to paint a picture. While third-party reports like a newspaper quoting another source are useful, it’s important to be critical of the sources you find during an OSINT investigation. Because there is so much information, much of it inaccurate or published by unreliable sources, OSINT researchers must be extremely critical of the sources of data used, preferring only to use verified primary source data to draw conclusions. 

Because OSINT covers so many different types of data, there are many different types of investigations that can be conducted. This ranges from social media investigations using free tools to comb through vast amounts of Tweets, to geospatial investigations using satellite imagery to locate where photos were taken. 

There are many different resources for investigators looking for more OSINT tools, including the osintframework.com website which lists a huge number of data sources for different types of OSINT investigations. There are also many fantastic free OSINT tools on Github, many of them curated into this “[Awesome-OSINT](https://github.com/jivoi/awesome-osint)” list.

[![What OSINT Techniques Are There?|500](https://www.varonis.com/hs-fs/hubfs/Imported_Blog_Media/VAR_OSINTFramework.jpg?width=1024&height=1376&name=VAR_OSINTFramework.jpg)](https://info.varonis.com/hubfs/Imported_Blog_Media/VAR_OSINTFramework.jpg?hsLang=en)

## What OSINT Techniques Are There?

OSINT tactics can be divided into active and passive techniques, with active tactics involving some sort of actual contact with the target, and passive tactics avoiding any contact with the target. Active techniques always involve some small risk of the target detecting you are investigating them, whereas passive tactics usually involve querying a database maintained by someone else, and usually do not involve any risk of being detected.

[![An active OSINT tactic could be as simple as scanning a website|400](https://www.varonis.com/hs-fs/hubfs/Imported_Blog_Media/VAR_Active-vs-Passive_B.jpg?width=1024&height=912&name=VAR_Active-vs-Passive_B.jpg)](https://info.varonis.com/hubfs/Imported_Blog_Media/VAR_Active-vs-Passive_B.jpg?hsLang=en)

An active OSINT tactic could be as simple as scanning a website or web server owned by a target, or registering to download a competitor’s product catalog. While this small contact probably won’t blow your investigation, matching a download to your organization’s IP address could tip off a subject that your organization is investigating. Comparatively, a passive technique like using a search engine like Shodan to examine services a company is running without scanning them yourself would be nearly impossible for the target to detect.

## How Does OSINT Relate to SOCMINT & HUMINT?

HUMINT, or human intelligence, is old-school intelligence collection done using human sources to collect information. With the explosion of data available to OSINT investigators, HUMINT has been supercharged by the ability to learn nearly everything about the person you need to interview before you even meet them. This gives the investigator a huge advantage when interviewing a source, and can make HUMINT a natural and extremely valuable add-on to any OSINT investigation.

OSINT is the secret power behind many HUMINT collection wins, providing the context to get a person to do something they’re not supposed to do. Often with the right OSINT information, it’s possible to get someone who is aware they hold sensitive information to either grant you access because they think they are supposed to, or because they think you already know the information they have access to.

By taking advantage of the information about a company’s employees on social media as well as internal policies leaked by documents easily found through passive search techniques, it’s simple to understand who has access to the information an investigator needs. This can cut down the time needed to get answers substantially by getting the exact right answer from the right source earlier. 

## How Do I Find OSINT on Phone Numbers?

Phone numbers are often linked to individuals through phone books, social media accounts, and data leaked by businesses who have worked with someone before. When phone numbers turn up in an OSINT investigation, third-party aggregators like [www.opencnam.com](http://www.opencnam.com/), thatsthem.com, and truecaller.com can begin matching the number to businesses or people.

Once you have an initial match, you’ll want to pull details like addresses, names, and social media names to expand the scope of your discovery to other web accounts or documents related to your target. Matching each of these details to even more information is often how a phone number can lead to a business license or other more concrete details.

## How Do I Find OSINT on Names?

Names often appear in documents related to business filings, so the best quality results for name searches related to business owners or powerful people will often be on websites like lilsis.org or OpenCorporates. For normal people, third party aggregators will often attempt to stitch together lots of information about people by name, especially if you know the general area they live in.

While third-party aggregators can’t be used as answers to your investigation, they often point to better sources of data. To start an investigation, sources like pipl.com, beenverified.com, and peekyou.com can get you started, but should only be used to point to other accounts or searchable details like past addresses or phone numbers.

## How Do I Find OSINT on Businesses?

Businesses are some of the easiest entities to find information on, as they need to register a lot of paperwork with public entities to exist. This paperwork is often entirely public and searchable, giving investigators a trove of information full of details which help to expand an investigation in the early stages. 

To get started, it’s best to search the secretary of state website of whichever state a particular organization does business in. This should provide a starting point of data, but can often be expanded on by searching additional states as well. Because there are tax and legal incentives to register in certain states in the US, it’s often worthwhile to check the secretary of state databases in Nevada, Delaware, California, and Wyoming as well.

[![After locating primary source data, third party aggregators like OpenCorporates|450](https://www.varonis.com/hs-fs/hubfs/Imported_Blog_Media/VAR_Timeline.jpg?width=1024&height=1228&name=VAR_Timeline.jpg)](https://info.varonis.com/hubfs/Imported_Blog_Media/VAR_Timeline.jpg?hsLang=en)

After locating primary source data, third party aggregators like OpenCorporates give you the ability to search all secretary of state databases indexed by the service, often locating valuable primary source information somewhere you might have missed. Lilsis.org is also a good source of information about business people including stock options and tax information. 

## How Do I Find OSINT on Websites?

Websites represent a lot of information about a business, both technical and in the way the website has changed messaging and branding over time. For OSINT investigations, websites are often looked at for their technical information, like who registered it, what servers are in use, and what software is maintaining it. This can be done through services like Shodan, which allow you to profile an organization’s technical infrastructure without actually scanning it yourself.

Another source of information is the actual contents of the website, which can include files left unintentionally public, or information that may have been removed from the website in the past. Tools like the Internet Archive can show an investigator how the website has changed over time by comparing snapshots taken years earlier, often pointing to organizational changes or showing who has left or joined the company and when.

Google Dorking is also a powerful way of finding files and other details left open to the internet by accident. By structuring Google search queries to look for certain types of web pages or files, it’s easy to find any parts of a target’s website that might be leaking confidential information.

## What Resources Are There For OSINT Research?

There is a huge community around OSINT investigations that loves to share tricks and techniques for investigations. In particular, Mike Bazell hosts an amazing website and podcast about OSINT that constantly points to new and innovative investigation techniques, and both Twitter and Github are full of new OSINT tools being developed and released by the OSINT community.

## What Dangers Are There in Conducting OSINT Research?

While OSINT is based on public data, there are always risks when doing any sort of investigation that involves either making direct contact with the subject, or a third party who may sell your search to the third party directly. In the example of LinkedIn, you may find a link to a subject’s LinkedIn profile and forget to sign out of your own, prompting LinkedIn to offer the target the information that you were looking at their profile as part of their product. 

This kind of contact can blow an investigation, as can accessing a web resource belonging to a target from your organization’s IP address. If you work for an organization that does not want to be identified while investigating a target, you must always use a VPN to hide the IP address of the place that you’re working from, or risk making your attention to any particular part of the target’s infrastructure obvious. 

Thanks to the many loopholes provided by CCPA, OSINT investigations are generally not something California residents need to worry about. GDPR, however, is more strict with these rules, meaning it’s important to take basic steps during an investigation to ensure you don’t expose personal information of a subject and that you’re storing it properly. This means using encryption to store your investigation notes and not leaving them where they can be accessed by a third party.

## What Are Some Examples of OSINT Investigations?

Bellingcat has produced some of the most dramatic OSINT investigations in recent memory, in particular blowing the lid off denials by the Russian government of involvement in various operations by digging through databases to prove their involvement directly. 

Memorable examples include tying Russian spies to their secret employment by digging through car registration databases (https://www.bellingcat.com/news/2018/10/04/305-car-registrations-may-point-massive-gru-security-breach/comment-page-5/), and linking social media photos to prove Russian soldiers were operating in areas the government claimed they weren’t. Many OSINT investigations cover topics like war crimes in areas too remote or dangerous to access remotely and was used extensively in the investigation into the downing of Malaysian Airlines Flight 17 (MH17). (https://www.bellingcat.com/news/uk-and-europe/2017/12/08/russian-colonel-general-delfin/)

## Who Makes Use of OSINT Reports?

OSINT is a critical part of both public and private intelligence, arming businesses, governments, and individual investigators with a vast amount of high-quality information to base and make decisions on. Whether conducting an investigation for research, business intelligence, or threat analysis, OSINT can allow anyone to have access to some of the best available data in the world. 

×

![Kody Kinzie](https://www.varonis.com/hubfs/Varonis_June2021/Images/kody_bw-150x150.jpg)

Kody Kinzie Kody Kinzie is a security researcher who specializes in open-source intelligence and Wi-Fi security. He teaches cybersecurity to beginners on two popular YouTube channels called Hak5 and Null Byte, as well as organizing cybersecurity training and outreach events in Los Angeles.OSINT 代表开源情报，指的是从免费且对公众开放的来源收集数据的做法。随着信息从大量来源变得更加可用，熟练的研究人员通常可以找到他们正在寻找的几乎任何类型的数据，前提是他们知道在哪里查找。这些来源包括黑客、记者、间谍和普通人每天用来收集信息的各种公共和私人数据库。

这些信息中的大部分无法通过搜索引擎检索，需要知道正确的数据库位置才能获得正确的答案。幸运的是，有许多工具可供初学者和经验丰富的调查人员利用，以便在进行研究时使用 OSINT 来源。

在本文中，我们将涵盖以下内容：

- [我应该为 OSINT 做些什么来保护我的组织？](https://www.varonis.com/blog/#investigation)
- [如何进行 OSINT 调查](https://www.varonis.com/blog/#conduct)
- [OSINT 框架与工具](https://www.varonis.com/blog/#tools)
- [OSINT 技术](https://www.varonis.com/blog/#tech)
- [OSINT、SOCMINT 与 HUMINT](https://www.varonis.com/blog/#osh)
- [关于电话号码的 OSINT](https://www.varonis.com/blog/#phone)
- [关于姓名的 OSINT](https://www.varonis.com/blog/#names)
- [关于企业的 OSINT](https://www.varonis.com/blog/#business)
- [关于网站的 OSINT](https://www.varonis.com/blog/#websites)
- [OSINT 研究的资源](https://www.varonis.com/blog/#research)
- [OSINT 研究的危险](https://www.varonis.com/blog/#dangers)
- [OSINT 法规](https://www.varonis.com/blog/#regulations)
- [OSINT 调查的示例](https://www.varonis.com/blog/#examples)
- [谁使用 OSINT？](https://www.varonis.com/blog/#who)

## 我应该为 OSINT 做些什么来保护我的组织？

每个组织都会产生数据，如果这些数据是由地方政府或州政府生产或记录的，那么其中许多数据可能是公开的。除了业务数据外，从网站或产品的注册或开发中获得的技术数据可能会暴露有关组织内部运作的信息，而这些信息在其他情况下可能难以找到。

关于 OSINT 的第一件事是它具有两面性，用于了解竞争对手的相同数据也可以用来推断有关您公司或组织的信息。发现哪些关于您的信息可能比您预期的更公开，并了解外部人员如何知道有关您组织的内部细节，从而更容易进行攻击，这可能是非常有价值的。

## 如何进行 OSINT 调查？

OSINT 调查从回答一个可回答的问题开始。由于数据量巨大，如果不清楚自己要寻找的是什么，很容易迷失在信息的海洋中。例如，“纽约比洛杉矶更安全吗？”与“自1999年以来，洛杉矶县的警察不当行为报告是否有所增加？”这两个问题。第一个问题需要意见，难以回答，而第二个问题可以通过找到正确的记录持有者轻松回答。

在确定了要回答的问题后，下一步是识别最有可能拥有最佳质量数据的来源。政府或公司数据等原始信息是最好的来源，其次是与您的问题相关的行业或贸易组织或非政府机构（NGO）创建的信息。最后，第三方数据聚合器可以提供有用的链接，指向数据的主要来源，尽管这种“三级”数据不能用作证据。

通常，调查会通过提出可回答的问题并使用最佳质量的答案来描绘一幅画面，从而对主题有一个了解。虽然像报纸引用其他来源的第三方报告是有用的，但在进行 OSINT 调查时，对找到的来源持批判态度非常重要。由于信息量巨大，其中许多信息可能不准确或由不可靠的来源发布，因此 OSINT 研究人员必须对使用的数据来源非常挑剔，最好只使用经过验证的原始数据来得出结论。

由于 OSINT 涵盖了如此多不同类型的数据，因此可以进行许多不同类型的调查。这包括使用免费工具通过社交媒体调查来梳理大量推文，以及使用卫星图像进行地理空间调查以确定照片的拍摄地点。

有许多资源可供调查人员寻找更多的 OSINT 工具，包括 osintframework.com 网站，该网站列出了大量不同类型 OSINT 调查的数据来源。Github 上还有许多出色的免费 OSINT 工具，其中许多被整理到这个“[Awesome-OSINT](https://github.com/jivoi/awesome-osint)”列表中。

[![有哪些 OSINT 技术？|500](https://www.varonis.com/hs-fs/hubfs/Imported_Blog_Media/VAR_OSINTFramework.jpg?width=1024&height=1376&name=VAR_OSINTFramework.jpg)](https://info.varonis.com/hubfs/Imported_Blog_Media/VAR_OSINTFramework.jpg?hsLang=en)

## 有哪些 OSINT 技术？

OSINT 战术可以分为主动和被动技术，主动战术涉及与目标的某种实际接触，而被动战术则避免与目标的任何接触。主动战术总是涉及目标检测到您正在调查他们的风险，而被动战术通常涉及查询由其他人维护的数据库，通常不会涉及被检测到的风险。

[![主动 OSINT 战术可能像扫描网站一样简单|400](https://www.varonis.com/hs-fs/hubfs/Imported_Blog_Media/VAR_Active-vs-Passive_B.jpg?width=1024&height=912&name=VAR_Active-vs-Passive_B.jpg)](https://info.varonis.com/hubfs/Imported_Blog_Media/VAR_Active-vs-Passive_B.jpg?hsLang=en)

主动 OSINT 战术可能像扫描目标拥有的网站或网络服务器一样简单，或者注册下载竞争对手的产品目录。虽然这种小接触可能不会破坏您的调查，但将下载与您组织的 IP 地址匹配可能会提示目标您的组织正在调查他们。相比之下，像使用 Shodan 这样的搜索引擎来检查公司正在运行的服务而不自己扫描的被动技术，几乎不可能被目标检测到。

## OSINT 如何与 SOCMINT 和 HUMINT 相关？

HUMINT，即人类情报，是使用人类来源收集信息的旧式情报收集。随着 OSINT 调查员可用的数据爆炸式增长，HUMINT 通过在您甚至与他们见面之前了解您需要采访的人的几乎所有信息，得到了极大的增强。这为调查员在采访来源时提供了巨大的优势，并且可以使 HUMINT 成为任何 OSINT 调查中自然且极其有价值的补充。

OSINT 是许多 HUMINT 收集胜利背后的秘密力量，提供了让人们做他们不应该做的事情的背景。通常，通过正确的 OSINT 信息，可以让知道他们持有敏感信息的人因为认为他们应该这样做，或者因为他们认为您已经知道他们有权访问的信息而授予您访问权限。

通过利用有关公司员工在社交媒体上的信息以及通过被动搜索技术轻松找到的内部政策泄露的文件，很容易了解谁有权访问调查员需要的信息。这可以通过从正确的来源尽早获得正确的答案，大大减少获取答案所需的时间。

## 如何找到关于电话号码的 OSINT？

电话号码通常通过电话簿、社交媒体账户以及与某人合作过的企业泄露的数据与个人相关联。当电话号码出现在 OSINT 调查中时，第三方聚合器如 [www.opencnam.com](http://www.opencnam.com/)、thatsthem.com 和 truecaller.com 可以开始将号码与企业或个人匹配。

一旦有了初步匹配，您将希望提取地址、姓名和社交媒体名称等详细信息，以扩展您的发现范围，找到与目标相关的其他网络账户或文档。将这些详细信息与更多信息匹配通常是电话号码如何导致商业许可证或其他更具体细节的方式。

## 如何找到关于姓名的 OSINT？

姓名通常出现在与商业文件相关的文档中，因此与企业主或有权势的人相关的姓名搜索的最佳结果通常会在 lilsis.org 或 OpenCorporates 等网站上找到。对于普通人，第三方聚合器通常会尝试通过姓名拼凑大量关于人的信息，特别是如果您知道他们居住的大致区域。

虽然第三方聚合器不能用作调查的答案，但它们通常会指向更好的数据来源。要开始调查，像 pipl.com、beenverified.com 和 peekyou.com 这样的来源可以为您提供起点，但应仅用于指向其他账户或可搜索的详细信息，如过去的地址或电话号码。

## 如何找到关于企业的 OSINT？

企业是一些最容易找到信息的实体，因为它们需要向公共实体注册大量文件才能存在。这些文件通常是完全公开且可搜索的，为调查员提供了一堆充满详细信息的宝藏，这些信息有助于在早期阶段扩展调查。

要开始，最好搜索特定组织所在州的州务卿网站。这应该提供数据的起点，但通常可以通过搜索其他州来扩展。由于在美国某些州注册有税收和法律激励，因此通常值得检查内华达州、特拉华州、加利福尼亚州和怀俄明州的州务卿数据库。

[![在找到原始数据后，像 OpenCorporates 这样的第三方聚合器|450](https://www.varonis.com/hs-fs/hubfs/Imported_Blog_Media/VAR_Timeline.jpg?width=1024&height=1228&name=VAR_Timeline.jpg)](https://info.varonis.com/hubfs/Imported_Blog_Media/VAR_Timeline.jpg?hsLang=en)

在找到原始数据后，像 OpenCorporates 这样的第三方聚合器使您能够搜索服务索引的所有州务卿数据库，通常会在您可能错过的地方找到有价值的原始信息。Lilsis.org 也是关于包括股票期权和税务信息在内的商业人士的良好信息来源。

## 如何找到关于网站的 OSINT？

网站代表了许多关于企业的信息，包括技术和网站随着时间的推移在信息传递和品牌方面的变化。对于 OSINT 调查，网站通常会查看其技术信息，如谁注册了它、使用了哪些服务器以及维护它的软件是什么。这可以通过 Shodan 等服务完成，这些服务允许您在不实际扫描的情况下对组织的技术基础设施进行概况分析。

另一个信息来源是网站的实际内容，可能包括无意中公开的文件，或过去从网站上删除的信息。像互联网档案馆这样的工具可以通过比较多年前拍摄的快照，向调查员展示网站随时间的变化，通常会指出组织的变化，或显示谁离开了公司或加入了公司以及何时加入。

Google Dorking 也是通过意外留在互联网上的文件和其他细节来查找的强大方法。通过构建 Google 搜索查询以查找某些类型的网页或文件，很容易找到目标网站可能泄露机密信息的部分。

## 有哪些 OSINT 研究的资源？

围绕 OSINT 调查有一个庞大的社区，他们喜欢分享调查的技巧和技巧。特别是，Mike Bazell 主持了一个关于 OSINT 的精彩网站和播客，不断指向新的和创新的调查技术，Twitter 和 Github 上充满了 OSINT 社区开发和发布的新的 OSINT 工具。

## 进行 OSINT 研究有哪些危险？

虽然 OSINT 基于公共数据，但在进行任何涉及与目标直接接触或第三方可能将您的搜索直接出售给第三方的调查时，总是存在风险。例如，在 LinkedIn 上，您可能会找到目标的 LinkedIn 个人资料链接，并忘记退出自己的账户，从而提示 LinkedIn 向目标提供您正在查看他们个人资料的信息作为其产品的一部分。

这种接触可能会破坏调查，就像从您组织的 IP 地址访问属于目标的网络资源一样。如果您工作的组织在调查目标时不希望被识别，您必须始终使用 VPN 来隐藏您正在工作的地点的 IP 地址，否则可能会使您对目标基础设施的任何特定部分的关注变得明显。

由于 CCPA 提供的许多漏洞，OSINT 调查通常不是加州居民需要担心的事情。然而，GDPR 对这些规则更为严格，这意味着在进行调查时采取基本步骤以确保您不会暴露目标的个人数据并妥善存储这些数据非常重要。这意味着使用加密来存储您的调查笔记，并且不要将它们留在第三方可以访问的地方。

## 有哪些 OSINT 调查的示例？

Bellingcat 在过去几年中进行了一些最引人注目的 OSINT 调查，特别是通过挖掘数据库直接证明俄罗斯政府的参与，揭开了俄罗斯政府对各种行动的否认。

值得注意的例子包括通过挖掘汽车注册数据库将俄罗斯间谍与他们的秘密雇主联系起来（https://www.bellingcat.com/news/2018/10/04/305-car-registrations-may-point-massive-gru-security-breach/comment-page-5/），以及通过社交媒体照片证明俄罗斯士兵在政府声称他们不在的地区活动。许多 OSINT 调查涵盖了像战争罪这样的主题，这些主题在偏远或危险地区无法远程访问，并在调查马来西亚航空公司 17 号航班（MH17）坠机事件中得到了广泛使用。（https://www.bellingcat.com/news/uk-and-europe/2017/12/08/russian-colonel-general-delfin/）

## 谁使用 OSINT 报告？

OSINT 是公共和私人情报的关键部分，为企业和政府以及个人调查员提供了大量高质量的信息，以便基于这些信息做出决策。无论是进行研究、商业情报还是威胁分析的调查，OSINT 都可以让任何人访问世界上一些最好的可用数据。


![Kody Kinzie](https://www.varonis.com/hubfs/Varonis_June2021/Images/kody_bw-150x150.jpg)

Kody Kinzie Kody Kinzie 是一名安全研究员，专门研究开源情报和 Wi-Fi 安全。他在两个受欢迎的 YouTube 频道 Hak5 和 Null Byte 上教授网络安全给初学者，并在洛杉矶组织网络安全培训和外展活动。
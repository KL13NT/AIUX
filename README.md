# The Arabic Initiative for User Experience (AIUX)

The Arabic Initiative for User Experience (AIUX) is an idea for building a better world for Arabic-speaking users. It outlines ways in which the Arabic community could enhance existing tooling and content to provide a better UX for Arabic-speaking users.

## Translations

-   [Egyptian Arabic - العامية المصرية 🇪🇬](./ar-EG.md)

## Introduction

In light of efforts to improve the technical Arabic content, attention must be paid to all the different groups of Arab peoples and Arabic speakers. Among these efforts, there must be efforts interested in creating assistive technology, improving existing assistive technology, and building a community of content creators with this goal in mind.

There must be efforts to give public attention to people with different needs, such as those with hearing and vision disabilities, by paying attention to the principles of accessibility and raising public awareness of developers and content creators of the importance of these principles.

At the time of writing this file and according to [the Ministry of Health in the Kingdom of Saudi Arabia][1], visually-impaired Arabic speakers were estimated at approximately 12% of the world's visually-impaired population for the year 2010. Also, [the WHO Regional Office for the Eastern Mediterranean][2] calculated that an estimated 28 million people in the Eastern Mediterranean Region suffer hearing impairments.

These, and the language barrier, constitute the seemingly biggest obstacles in Arabic content today. Most of the online content related to the scientific community is presented in English. This language barrier obstacles learners of the Arab world and deeply affects their learning journey until they gain a deep understanding of the language.

Thus it is necessary to continue our efforts towards giving the Arab world a more accessible life, either by building assistive technology, translating content, or producing Arabic content. These are the goals of this initiative.

This initiative consists of 3 sections, called factions, each with a specific goal and specific responsibilities. Each faction has a specific label and their members are responsible for documenting their efforts in an accessible format available to everyone.

> Responsibilities are not 100% clear yet, but should develop over time. As of now, this is only a suggestion to the community.

> I'm still contemplating how the repo will be setup, but for now the repo should stick to labels for issues.

## Assistive Technology Faction (AT)

This faction is appointed the responsibility of developing and improving existing and new assistive technology for Arabic-speaking end-users. Screen readers, browser extensions, translation tools, etc.

## Content Maintenance Faction (CT)

This faction is responsible for translating existing content to Arabic (if needed), creating high-quality Arabic content and building communities around it, and supporting Arabic content. It's also their responsibility to raise awareness about the importance of creating accessible, high-quality Arabic content.

## RTL and BIDI Text Support Faction (TS)

Existing software mostly lacks support for RTL and BIDI text. This is not exclusive to Arabic, but is crucial for mixed and purely Arabic content. Developers face a lot of headache trying to write Arabic programs using English code.

This often forces developers to go for workarounds such as editing BIDI text in BIDI-supporting text editors before copying it back to their code-editor of choice. Adding RTL/BIDI support in these editors will grant thousands of developers an easier workflow.

This is not exclusive to developers either. Design tools, document editing tools, and other tools suffer this lack of RTL/BIDI support. The goal of this faction is to build, contribute to, develop, and document RTL/BIDI support.

## Contributing

This project wouldn't exist without helping hands. It's the efforts of the Arabic and non-Arabic communities, and will continue being so. Any contribution of any kind is welcome. Let it be a question, inquiry, discussion, tool development, translation, etc.

All you have to do is start a discussion on the [discussions page][3]. If the issue in question is purely technical then feel free to create an issue. Guidance will be provided either way. Anyone is welcome to contribute.

>  This is not limited to Arabic-speaking contributors only. Which is one of the reasons documentation is mainly written in English!

> Contributing is not limited to those with experience. Everyone is welcome to contribute!

You can use the Discussions board for:

-   Ideas!
-   Showing off things you built for the community!
-   Questions
-   General, unclassified discussions

> Everything is on [GitHub][4].

> I take the open source community seriously and hold myself and other contributors to high standards of communication. By participating and contributing to this project, you agree to uphold the [Code of Conduct](5).

Each discussion/issue will be given a label based on the faction it belongs to, and its classification.

## Creating Issues in Arabic

To keep Arabic text right-aligned on GitHub use the following HTML code in your issues, PRs, and Markdown files:

```html
<div dir="rtl">
  // اكتب هنا
</div>
```

[1]: https://www.moh.gov.sa/HealthAwareness/HealthDay/2019/Pages/HealthDay-2019-10-10-001.aspx

[2]: http://www.emro.who.int/ar/control-and-preventions-of-blindness-and-deafness/about-the-programme/about-the-programme.html

[3]: https://github.com/KL13NT/AISAUX/discussions

[4]: https://github.com/KL13NT/arabic-a11y

[5]: Code%20of%20Conduct.md

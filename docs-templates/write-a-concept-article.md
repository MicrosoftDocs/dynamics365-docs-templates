---
title: Write a concept article
description: Learn how to write a concept article for Dynamics 365 or Power Platform.
author: Rhanajoy
ms.author: rhcassid
ms.date: 04/07/2022
ms.topic: contributor-guide
ms.prod: non-product-specific
ms.custom: internal-contributor-guide
---

# Write a concept article

A concept article provides an in-depth explanation of an idea, principle, or functionality that’s common or useful across various tasks and is fundamental to understanding and use. It’s distinct from a procedural article, which includes concrete, sequential tasks to achieve a particular end state. A concept article shouldn’t include numbered steps or lots of bulleted lists.

The primary question a concept article needs to answer is:

- What is **X** and how will learning this help me accomplish **Y**?

You might also consider writing a concept article to answer questions such as:

- How does **X** work or what happens when I do **X**?
- How does **X** affect **A**, **B**, and **C**?

Use [this template](concept-template-intro.md) to write a new concept article.

## Metadata

The following metadata needs to be included in a concept article.

| Attribute | Value |
| -- | -- |
| title | Article title (don’t enclose it in quotation marks) |
| description | A brief description of the topic, no more than 160 characters (don’t enclose it in quotation marks) |
| author | Author’s GitHub alias, with correct capitalization |
| ms.author | Author’s Microsoft alias |
| ms.date | Current date, in mm-dd-yyyy format |
| ms.topic | conceptual (don't change this) |
|  |  |

Add other metadata as required for your documentation set.

## H1

Your topic title is the only H1 heading in your article. This title, or headline, should match the article title you listed in the metadata table. The title should be unique. If you have a duplicate title, you will receive a warning in GitHub when you try to merge.

Your H1 should clearly convey what the article is about. The title shouldn’t start with a verb or otherwise insinuate a concrete action or task. Concepts deal with ideas or principles, not actions. Make sure your title doesn’t wrap to a second line if you can avoid it.

### Introduction

Your first paragraph should describe what readers will learn. Answer the primary “What is **X** and how will learning this help me accomplish **Y**?” question. This paragraph should help readers quickly determine whether the article is relevant to them. Keep this introduction short.

It isn’t necessary to include a heading called **Introduction**. This paragraph can just live under the H1 title.

Don’t lead with notes, caveats, or prescriptions. A good lead is a sentence in the form, “**X** is a (type of) **Y** that does **Z**.” For example:

- **Not ideal:**  
    You should apply the new technology of containerization to make all your applications work on all your systems.

- **Better:**  
    Containerization is a form of application encapsulation that bundles all related program files and libraries into a single executable package so an application can run on any host operating system.

Use customer-friendly terms. The language you use throughout, not just in the introduction, should be consistent with the [Microsoft brand “voice”](https://microsoft.sharepoint.com/teams/brandcentral/Pages/The-Microsoft-brand-Identity-Voice.aspx).

Follow these general guidelines:

- Use warm, relaxed, natural language. Write like you’re talking to a friend.
- Write for scanning first, reading second.
- Project friendliness and helpfulness.
- Make it short and simple. Get to the point fast. Don’t use 25 words when 10 will do.
- Make choices and next steps obvious.
- Use strong word choices:
    - Start statements with verbs, not “you can” or “there are.”
    - Whenever possible, use the active voice, not passive (“the pilot landed the plane,” not “the plane was landed by the pilot”).

## Body

Use this part of the article to discuss the subject in greater depth and with more detail. If appropriate, include links to related topics that include more detailed information or procedures.

### H2, H3, H4 headings

Don’t number headings. Follow H2 headings with a sentence or two that explains how this section contributes to the whole or that provides a smooth transition from the heading to the content. Avoid using headings lower than H4.

### Prerequisites

If the reader should understand other concepts before reading this article, make **Prerequisites** your first H2.

### Bulleted and numbered lists

Try not to use bullets in a concept article. Definitely don't use numbered lists.

### Alerts

Avoid using notes, tips, and important alerts in a concept article. Readers tend to skip over them. Instead, put the information in the article text. If you need to use alerts, don’t use more than two, and never put them next to each other.

### Screenshots and videos

When appropriate, use diagrams, tables, or images to reinforce a concept. You might also want to include screenshots and videos. While these can offer value, don’t overdo it. Make sure each screenshot and video offer value to your reader. Don’t rely on the screenshot or video to explain anything, however. For accessibility and usability purposes, you will have to document what is shown in a graphic prior to the graphic.

Make sure that your graphics are clear and legible. For detailed information about how to create screenshots and videos, see [a topic we need to create](filename.md). Here are some general guidelines:

- Screenshots should be .png files. Videos should be ?? files.
- Keep the file sizes as small as possible by ??.
- Etc.

Don’t use animated gifs. Use short videos instead. Animated gifs can cause accessibility issues for neurodiverse readers and readers from different backgrounds.

## Next steps

Concept articles should always conclude with a **Next steps** H2 heading that points to the next logical article. List at least one, but no more than three. Don’t link to troubleshooting content or FAQs, because these imply the customer is going to run into known issues.

## Helpful links

- Link to accessibility guidelines
- Link to title guidelines
- Link to SEO guidelines
- [Overview of the Microsoft voice | Microsoft Style Guide](https://microsoft.sharepoint.com/teams/brandcentral/Pages/The-Microsoft-brand-Identity-Voice.aspx)

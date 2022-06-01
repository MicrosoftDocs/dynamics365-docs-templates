---
title: Write a landing page
description: Learn how to write a landing page for Dynamics 365 or Power Platform documentation.
author: Rhanajoy
ms.author: rhcassid
ms.date: 04/07/2022
ms.topic: contributor-guide
ms.prod: non-product-specific
ms.custom: internal-contributor-guide
---

# Write a landing page

A landing page is the jumping-off point from which the customer’s journey to using our products begins. Alternatively, it’s a one-stop shop for everything customers need to know to use a Microsoft Dynamics 365 or Power Platform product or service. All on one page, they can easily find documentation to help them get started, learn the basics, dig deeper, troubleshoot, find out what’s new, and connect to the wider user community.

The primary question a landing page needs to answer is: Where can I find out more about **X**?

Use [this template](landing-page-template-intro.md) to create a new landing page.

## Metadata

The following metadata needs to be included in a landing page.

| Attribute | Value |
| -- | -- |
| title | Landing page title (don’t enclose it in quotation marks) |
| description | Repeat the title (don’t enclose it in quotation marks) |
| author | Author’s GitHub alias, with correct capitalization |
| ms.author | Author’s Microsoft alias |
| ms.date | Current date, in mm-dd-yyyy format |
| ms.topic | landing-page (don't change this) |
| ms.service | The product name from the Microsoft taxonomy |
|  |  |

Add other metadata as required for your documentation set.

## Components of a landing page

All landing pages should have at least two sections, featured content and content cards, as shown in the following example:

:::image type="content" source="landing-page-template-example.png" alt-text="Screenshot of the Dynamics 365 Fraud Protection landing page.":::

### Featured content

This is the collection of item types (each consisting of an icon and a link) that appear between the page title and the cards that represent the primary landing page content. Each item type highlights one of the links that appear in the associated card. In [the YAML template](landing-page-template.yml), this section is called **highlightedContent**. A maximum of eight item types can be included here. We recommend the following four item types, in no particular order:

- overview (or get-started)
- whats-new
- video
- learn

The remaining item types are architecture, concept, deploy, download, how-to-guide, quickstart, reference, sample, and tutorial.

Feature whichever item types make the most sense for your product or service, but again, try to use no more than four or five (eight is the maximum).

#### Overview/Get started

This section features a link to the best place for customers to start their journey. Whether it’s a product overview article or a workshop landing page, this is the most logical place to start learning how to use the product or service.

#### What’s new

This section features a link to information about new and enhanced features. It could be a simple “What’s new” article or an entire release plan.

#### Video

This section features a link to Microsoft-produced training videos for the product or service. This page should open in a new tab or window.

#### Learn

This section features a link to Microsoft Learn content for the product or service.

### Content cards

This is the collection of cards that serve as a high-level table of contents for the documentation set. Each card has a title and links to related pages. In [the YAML template](landing-page-template.yml), this section is called **additionalContent**.

A good way to organize the cards is to create a logical progression for the reader to follow. It might go something like this:

- **Start your journey with** *name of product or service* (include links to the overview article, release plans or “what’s new” content, and any prerequisites)
- **Set up your environment**
- **Set up** *name of product or service*
- API documentation
- Get in touch

Or, for a product that consists of several different services or functional areas, you might have cards like these:
- ***Name of service or functional area*** (include links to the documentation home page, Microsoft Learn content, and training videos)
- ***Name of service or functional area*** (include links to the documentation home page, Microsoft Learn content, and training videos)
- ***Name of service or functional area*** (include links to the documentation home page, Microsoft Learn content, and training videos)
- **Best practices**

Keep the links on the cards at a high level. Avoid including more than five links on a card. The [home page](filename.md) is the place to go crazy with headings and subheadings. If the documentation set were a roadmap, the landing page would show major cities and the freeways between them; home pages would show the streets in an individual city.

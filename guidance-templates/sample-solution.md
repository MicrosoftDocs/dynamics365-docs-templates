---
title: Replace this text based on the guidance in Completing the metadata under the Article Title section.   
description: Replace this text based on the guidance in Completing the metadata under the Article Title section.
keywords: Replace this text based on the guidance in Completing the metadata under the Article Title section.
ms.service: dynamics-365 #Required. Leave as-is for all things Dynamics 365, but change to dccp for DCCP content.
ms.subservice: guidance #Required. Leave as-is.
ms.topic: conceptual #Required. Leave as-is.
ms.custom: bap-template #Required; Leave as-is.
author: #Required; your GitHub user alias, with correct capitalization. 
ms.date: 06/16/2023
---

# Article title as a scenario

*All descriptive text is formatted in italics to remind you to delete it before you complete and submit your solution. Your article can have only one **H1 heading (#)**, which is the article title. The H1 heading is always followed by a succinct descriptive paragraph that informs the reader what the article is about and how it can help them. Do not start the article with a note or tip. .*

*This template is specific to **Dynamics 365 sample solutions**. Sample solutions are example workloads that guide customers through the design process of solving specific aspects of Dynamics 365 implementations. They provide actionable architecture guidance based on real customer examples. Their goal is to shorten a customer's learning curve by telling them the story of another customer who has been there before. Your article should be broken down into six subheadings (H2, ## in markdown)--Architecture, Scenario details, Considerations, Deploy this scenario, Contributors, and Next steps. The H2 headings and descriptions are included in this template. If you need to create a new heading under one of the H2 headings, use an H3 heading (###).*

***Completing the metadata:***
*This section provides guidance on completing the metadata section at the top of this template. Update the placeholder text based on the following guidance:*

- *title: Use the H1 (#) title of your article from the top of this section. Both titles should be identical. Maximum recommended length is 60 characters. If in doubt of the length, copy it to Word, and then use the Word count feature*
- *description: Provide a brief summary of your article. This is the description that appears in search engine results, so ensure the summary is clear and concise and attracts your intended audience. Maximum recommended length is 150-160 characters. If in doubt of the length, copy it to Word, and then use the Word count feature*
- *ms.date: Enter the date in mm/dd/yyyy format, as shown in the metadata field. Initially this should be the date your article is submitted. After publication, this field should be refreshed whenever the article is updated so readers can see that the content is fresh.*

*Introductory section with no heading*
*After the article title heading, include 1-2 sentences to briefly explain this sample solution.*

*In this section, include 1-2 sentences to briefly explain this solution. The full scenario info will go in the "Scenario details" section, which is below the "Architecture" H2 (top level) heading, below the "Alternatives" H3 header, and above the "Considerations" H2 (top level) header. That includes the "Potential use cases" H3 section, which goes under the "Scenario details" H2 section. The reason why we moved this content down lower, is because customers want the emphasis on the diagram and architecture first, not the scenario.*

## Architecture

*Architecture diagram goes here. Under the architecture diagram, include this sentence and a link to the Visio file or the PowerPoint file:*

Download a [PowerPoint file](https://github.com/microsoft/dynamics365patternspractices/) with this architecture.<!-- Change the link to point to your PowerPoint file>

### Dataflow

*An alternate title for this sub-section is "Workflow" (if data isn't really involved).*
*In this section, include a numbered list that annotates/describes the dataflow or workflow through the solution. Explain what each step does. Start from the user or external data source, and then follow the flow through the rest of the solution (as shown in the diagram).*

Examples:

1. Admin 1 adds, updates, or deletes an entry in Admin 1's fork of the Microsoft 365 config file.
2. Admin 1 commits and syncs the changes to Admin 1's forked repository.
3. Admin 1 creates a pull request (PR) to merge the changes to the main repository.
4. The build pipeline runs on the PR.

### Components

*A bullet list of components in the architecture (including all relevant Dynamics 365 and Azure services) with links to the product service pages.*

*Why is each component there?*
*What does it do and why was it necessary?*
*Link the name of the service (via embedded link) to the service's product service page. Be sure to exclude the localization part of the URL (such as "en-US/").*

- Examples:

  - [Migrate Segmented Entry controls](https://learn.microsoft.com/dynamics365/fin-ops-core/dev-itpro/financial/segmented-entry-control-conversion)
  - [Azure Bot Service](https://azure.microsoft.com/services/bot-service)

### Alternatives

*Use this section to talk about alternative Azure services or architectures that you might consider for this solution. Include the reasons why you might choose these alternatives. Customers find this valuable because they want to know what other services or technologies they can use as part of this architecture.*

*What alternative technologies were considered and why didn't we use them?*
*List all "children" architectures (likely solution ideas) that build off this GAP architecture*

The following alternative solutions provide scenario-focused lenses to build off of this core architecture:  

- [Link to first solution idea or other architecture that builds off this solution](filepath.md)
- [Second solution idea that builds off this solution](filepath.md)

## Scenario details

*This should be an explanation of the business problem and why this scenario was built to solve it.*
*What prompted them to solve the problem?*
*What services were used in building out this solution?*
*What does this example scenario show? What are the customer's goals?*
*What were the benefits of implementing the solution?*

### Potential use cases

*What industry is the customer in? Use the following industry keywords, when possible, to get the article into the proper search and filter results: retail, finance, manufacturing, healthcare, government, energy, telecommunications, education, automotive, nonprofit, game, media (media and entertainment), travel (includes hospitality, like restaurants), facilities (includes real estate), aircraft (includes aerospace and satellites), agriculture, and sports.* 
*Are there any other use cases or industries where this would be a fit?*
*How similar or different are they to what's in this article?*

## Considerations

*REQUIRED STATEMENT: Include the following statement to introduce this section:*

These considerations help implement a solution that includes Dynamics 365 and reflects on the Success by Design framework and the Well-Architected Framework (WAF) pillars. Learn more at [Dynamics 365 guidance documentation](/dynamics365/guidance/).

*Are there any lessons learned from running this that would be helpful for new customers?  What went wrong when building it out?  What went right?*
*How do I need to think about managing, maintaining, and monitoring this long term?*

*REQUIREMENTS: 
*  You must include the "Cost optimization" section.* 
*  You must include at least two of the other H3 sub-sections/pillars: Environment strategy, Data management, Application lifecycle management, Security and Performance efficiency.*

### Environment strategy

*REQUIRED STATEMENT: If using this section, include the following statement to introduce the section:*

Environments are containers that store, manage, and share your organization's data. They also store the data model, application metadata, process definitions, and the security constructs to control access to data and apps. Learn more at [Environment strategy](/dynamics365/fasttrack/implementation-guide/environment-strategy).

### Data management

*REQUIRED STATEMENT: If using this section, include the following statement to introduce the section:*

Data governance, architecture, modeling, storage, migration, integration, and quality can help you make informed decisions, improve your customer engagement, and gather real-time information about your products in the field. Learn more at [Data management](/dynamics365/fasttrack/implementation-guide/data-management).  

### Application lifecycle management

*REQUIRED STATEMENT: If using this section, include the following statement to introduce the section:*

End-to-end lifecycle management can provide improved visibility, automation, delivery, and future planning for a Dynamics 365 solution. Learn more at [Application lifecycle management](/dynamics365/fasttrack/implementation-guide/application-lifecycle-management).  

### Performance efficiency

*REQUIRED STATEMENT: If using this section, include the following statement to introduce the section:*

Performance and early prioritization are directly related to the success of a project. Learn more at [A performing solution, beyond infrastructure](/dynamics365/fasttrack/implementation-guide/performing-solution).  

### Security

*REQUIRED STATEMENT: If using this section, include the following statement to introduce the section:*

Security provides assurances against deliberate attacks and the abuse of your valuable data and systems. Learn more at [Overview of the security pillar](/azure/architecture/framework/security/overview) and [Security in Dynamics 365 implementations](/dynamics365/fasttrack/implementation-guide/security).

*This includes identity and data sovereignty.*
*Are there any security considerations (past the typical) that I should know about this?*
*Because security is important to our business, be sure to include your Azure security baseline assessment recommendations in this section. See [https://aka.ms/AzureSecurityBaselines](https://aka.ms/AzureSecurityBaselines).*

### Cost optimization

*REQUIRED: This section is required. Cost is of the utmost importance to our customers.*

*REQUIRED STATEMENT: Include the following statement to introduce the section:*

Cost optimization is about looking at ways to reduce unnecessary expenses and improve operational efficiencies. Learn more at [Overview of the cost optimization pillar](/azure/architecture/framework/cost/overview).

*How much will this cost to run? See if you can answer this without dollar amounts.
*Are there ways I could save cost?*
*If it scales linearly, than we should break it down by cost/unit. If it does not, why?*
*What are the components that make up the cost?*
*How does scale affect the cost?*

*Link to the pricing calculator with all of the components in the architecture included, even if they're a $0 or $1 usage.*
*If it makes sense, include small/medium/large configurations. Describe what needs to be changed as you move to larger sizes.*

### Operational excellence

*REQUIRED STATEMENT: If using this section, include the following statement to introduce the section:*

Operational excellence covers the operations processes that deploy an application and keep it running in production. Learn more at [Process-focused solution](/dynamics365/fasttrack/implementation-guide/process-focused-solution) and [Overview of the operational excellence pillar](/azure/architecture/framework/devops/overview).

*This includes DevOps, monitoring, and diagnostics.*
*How do I need to think about operating this solution?*

## Deploy this scenario

*(Optional, but greatly encouraged)*
*Is there an example deployment that can show me this in action?  What would I need to change to run this in production?*

## Contributors

*(Expected, but this section is optional if all the contributors would prefer to not include it)*
*Start with the explanation text (same for every section), in italics. This makes it clear that Microsoft takes responsibility for the article (not the one contributor). Then include the "Pricipal authors" list and the "Additional contributors" list (if there are additional contributors). Link each contributor's name to the person's LinkedIn profile. After the name, place a pipe symbol ("|") with spaces, and then enter the person's title. We don't include the person's company, MVP status, or links to additional profiles (to minimize edits/updates). (The profiles can be linked to from the person's LinkedIn page, and we hope to automate that on the platform in the future). Implement this format with the explanation text formatted in italics:*

*This article is maintained by Microsoft. It was originally written by the following contributors.*

**Principal authors:**

- [Author 1 Name](http://linkedin.com/ProfileURL) | (Title, such as "Cloud Solution Architect")
- [Author 2 Name](http://linkedin.com/ProfileURL) | (Title, such as "Cloud Solution Architect")

**Other contributors:**  

- [Contributor 1 Name](http://linkedin.com/ProfileURL) | (Title, such as "Cloud Solution Architect")
- [Contributor 2 Name](http://linkedin.com/ProfileURL) | (Title, such as "Cloud Solution Architect")

> [!TIP]
> To see non-public LinkedIn profiles, sign in to LinkedIn.

## Next steps

*Link to Learn articles, along with any third-party documentation.*
*Where should I go next if I want to start building this?*
*Are there any relevant case studies or customers doing something similar?*
*Is there any other documentation that might be useful? Are there product documents that go into more detail on specific technologies that are not already linked?*

Examples:

- [Azure Kubernetes Service (AKS) documentation](/azure/aks)
- [Azure Machine Learning documentation](/azure/machine-learning)
- [What are Azure Cognitive Services?](/azure/cognitive-services/what-are-cognitive-services)
- [What is Language Understanding (LUIS)?](/azure/cognitive-services/luis/what-is-luis)
- [What is the Speech service?](/azure/cognitive-services/speech-service/overview)
- [What is Azure Active Directory B2C?](/azure/active-directory-b2c/overview)
- [Introduction to Bot Framework Composer](/composer/introduction)
- [What is Application Insights](/azure/azure-monitor/app/app-insights-overview)

## Related resources

*Use "Related resources" for architecture information that's relevant to the current article. Lead this section with links to the solution ideas that connect back to this architecture.*

This solution is a generalized architecture pattern, which can be used for many different scenarios and industries. See the following example solutions that build off of this core architecture:

- [Link to first solution idea or other architecture that builds off this solution](filepath.yml)
- [Second solution idea that builds off this solution](filepath.yml)

*Include additional links to Dynamics 365 or Power Platform guidance, or Azure Architecture Center articles. Here is an example:*

See the following related architecture guides and solutions:

- [Artificial intelligence (AI) - Architectural overview](/azure/architecture/data-guide/big-data/ai-overview)
- [Choosing a Microsoft cognitive services technology](/azure/architecture/data-guide/technology-choices/cognitive-services)
- [Chatbot for hotel reservations](/azure/architecture/example-scenario/ai/commerce-chatbot)
- [Build an enterprise-grade conversational bot](/azure/architecture/reference-architectures/ai/conversational-bot)
- [Speech-to-text conversion](/azure/architecture/reference-architectures/ai/speech-ai-ingestion)
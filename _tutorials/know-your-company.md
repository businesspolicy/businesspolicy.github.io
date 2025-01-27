---
title: Know Your Company
layout: default
nav_order: 2
---
# Know Your Company
{: .no_toc}

## Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Description:**

This lesson will guide you through setting up a robust NotebookLM project for your company analysis. You'll learn how to gather and organize essential information from key sources, preparing you for the in-depth analysis in the upcoming phases of the project.

**Learning Objectives:**

By the end of this lesson, you will be able to:

*   Describe the purpose and content of key source documents: Form 10-K, earnings call transcripts, and DEF 14A.
*   Set up a NotebookLM project and add these source documents.
*   Use NotebookLM's chat feature to extract critical company information for industry, business, and corporate strategy analysis.
*   Develop a workflow for conducting research and analysis using NotebookLM.

**Required Preparation:**

*   Select an S&P 500 company for your company analysis project.
*   Complete the Introduction to Strategy reading and the corresponding Canvas quiz.
*   Complete the NotebookLM tutorial and dry run project.
*   Create CapitalIQ login using Pitt account (See details here: [https://pitt.libanswers.com/faq/52206](https://pitt.libanswers.com/faq/52206)).
*   Watch the provided videos on earnings estimates and surprises.

[![American Airlines Shares Tumble](http://img.youtube.com/vi/DdSO_u42kog/0.jpg)](http://www.youtube.com/watch?v=DdSO_u42kog)
[![American Airlines CEO Robert Ison](http://img.youtube.com/vi/uSRnoANQAaQ/0.jpg)](http://www.youtube.com/watch?v=uSRnoANQAaQ)



## Introduction:  Bootstrapping Your Company Analysis Project

Welcome back! By now, you should have selected an S\&P 500 company for your analysis project. This lesson will guide you through setting up a robust NotebookLM project for your chosen company. You'll learn how to gather and organize essential information from key sources, preparing you for the in-depth analysis in the upcoming phases of the project.

**Why is this important?**

The company analysis project is a significant part of this course, accounting for 50% of your final grade. To succeed in each phase of the analysis (industry, business, and corporate strategy), you need a solid understanding of your chosen company. This includes:

*   Its portfolio of strategic business units
*   Its corporate structure
*   The industries and product markets where it operates
*   Its organizational culture
*   Its leadership team

This lesson will help you develop that baseline knowledge. We'll also address some common questions students have about getting started with the project, such as:

*   Why use the fourth-quarter earnings call transcript?
*   Why focus on specific sections of the Form 10-K?
*   Why is the proxy statement (DEF 14A) relevant?
*   How do I know what questions to ask NotebookLM?
*   How can I direct the AI to focus on specific aspects of a document?

By the end of this lesson, you'll be able to confidently develop a research workflow and independently pursue interesting research questions using NotebookLM.

**Example:**

For the industry analysis phase, you'll need to identify the company's primary industries and key competitors. This information can often be found in the Form 10-K, specifically in the "Business" section. Understanding the company's organizational structure and leadership team is crucial for the corporate strategy analysis phase. The DEF 14A proxy statement provides valuable insights into these aspects.

By addressing these questions and providing clear guidance, this lesson will equip you with the knowledge and skills to effectively use NotebookLM as a powerful tool for your company analysis project.


## Understanding the Sources

In the rapidly evolving world of business, information is the lifeblood of effective strategic decision-making. To truly understand a company's strategic landscape, we need to tap into reliable and relevant sources of information. This section will guide you through the essential sources for your company analysis project and highlight the critical role played by various players in the information ecosystem.

**The SEC**

At the heart of this information ecosystem lies the [Securities and Exchange Commission (SEC)](https://www.investor.gov/introduction-investing/investing-basics/role-sec), a regulatory body tasked with ensuring fair and transparent capital markets. The SEC mandates that publicly traded companies disclose specific information regularly, providing investors and analysts with the insights they need to make informed decisions.

**Essential Source Documents**

For your company analysis project, three key documents provide a wealth of information:

1.  **Form 10-K:** This annual SEC filing offers a comprehensive overview of a company's business, financial performance, and risk factors. Pay close attention to Item 1 (Business), Item 1A (Risk Factors), and Item 7 (Management Discussion and Analysis) for particularly relevant insights. See this investor bulletin from SEC to learn more about how to read the Form 10-K: [https://www.investor.gov/introduction-investing/general-resources/news-alerts/alerts-bulletins/investor-bulletins/how-read](https://www.investor.gov/introduction-investing/general-resources/news-alerts/alerts-bulletins/investor-bulletins/how-read) 
2.  **Earnings Call Transcripts:** These transcripts capture the discussions between company executives and financial analysts, providing valuable insights into a company's strategic priorities, performance drivers, and future outlook. The earnings call transcript for the fourth quarter (Q4) of the financial year tends to have the most detailed discussion on year-on-year performance and strategy execution.
3.  **DEF 14A Proxy Statement:** This document provides detailed information about a company's board of directors, executive compensation, and shareholder proposals, offering insights into a company's governance structure and potential conflicts of interest.  [About two-thirds of S&P 500 companies](https://corpgov.law.harvard.edu/2024/04/13/key-considerations-for-the-2024-annual-reporting-and-proxy-season-proxy-statements/) include a skills matrix for their board of directors, which implicitly conveys the business function expertise and industry experience that the company views as critical for governance and navigating the future.

**The Role of Analysts and Analyst Estimates**

Financial analysts play a crucial role in the ecosystem. They scrutinize company disclosures, conduct independent research, and provide earnings estimates and recommendations to investors. These estimates and the actual reported results often lead to surprises that can significantly impact a company's stock price and future strategic decisions. Understanding how analysts interpret information and form expectations is essential for a comprehensive company analysis.

**Why These Sources Matter**

These sources provide a foundation for understanding a company's strategic position and choices. They offer insights into:

*   **Industry Analysis:** Identifying the company's primary industries, key competitors, and major industry trends.
*   **Business Strategy Analysis:** Understanding the company's competitive advantage, value proposition, and key activities.
*   **Corporate Strategy Analysis:** Evaluating the company's organizational structure, portfolio of businesses, and drivers of profitability.

By carefully examining these documents, you can gain a deeper understanding of your chosen company and develop well-informed strategic recommendations.

## Setting Up Your NotebookLM Project

Now that you understand the importance of key source documents, let's dive into setting up your NotebookLM project. This will be your central hub for organizing information, conducting analysis, and generating insights throughout your company analysis project.

**Gathering Your Source Documents**

Start by gathering the essential documents for your chosen company:

*   **Form 10-K:** This annual SEC filing provides a comprehensive overview of the company's business, financial performance, and risk factors. Focus on Item 1: Business, Item 1A: Risk Factors, and Item 7: Management Discussion and Analysis.
*   **Earnings Call Transcripts:** These transcripts capture discussions between company executives and financial analysts, offering valuable insights into the company's strategic priorities and performance. Start with most recent fourth quarter(Q4) earnings call transcript. In my opinion, more meaningful year-on-year comparisons of performance and strategy execution tend to happen during the last quarter of a financial year.
*   **DEF 14A Proxy Statement:** This document provides detailed information about the company's board of directors, executive compensation, and shareholder proposals. This document is particularly important when you want to trace changes in leadership, and relevant prior experience among board members.

You can typically find these documents on your company's investor relations website or through data aggregators like [Capital IQ](https://www.capitaliq.com/).

**Creating Your NotebookLM Project**

1.  Open NotebookLM and create a new notebook dedicated to your company analysis project.
2.  Give your notebook a clear and descriptive title (e.g., "[Company Name] - Strategic Analysis").
3.  Add the source documents you've gathered to your notebook.

**Best Practices for Setting Up Your Notebook**

Here are some tips to help you organize your NotebookLM project effectively:

1.  **Prioritize Key Documents:** Start by adding only the essential documents (Form 10-K, earnings call transcripts, DEF 14A). You can add more specific sources later as needed for each phase of the analysis.
1.  **Multi-Year Comparison:** If you plan to analyze trends or changes over time, be sure to include documents for multiple years.
1.  **Unique Identifiers:** Rename your sources after importing them to ensure they are easily identifiable (e.g., "AAPL 10-K 2023," "MSFT Q4 2022 Earnings Call").
1.  **Strategic Sorting:**  NotebookLM sorts documents alphabetically. To keep related documents together, use a common prefix in their names (e.g., "industry report - cloud computing" "Industry report - software-as-a-service").
1.  **Section Extraction:** For lengthy documents like the 10-K, consider extracting specific sections as separate sources to make them easier to manage and analyze.
1.  **Prompt Logging:** Keep a log of your chat prompts to retrace your steps or share your analysis process with others.
1.  **Prune Sources:** Periodically review the list of source documents and remove those that you don't need from the notebook. Keep a copy of removed documents on cloud storage. You can add them later if a need arises. 


By following these best practices, you'll create a well-organized and efficient NotebookLM project that will serve as a valuable tool throughout your company analysis.


## Developing a Research Workflow

In the vast landscape of business information, having a structured research workflow is like having a compass and map to guide your journey. It helps you navigate efficiently, ensuring that your efforts are focused and productive.

**A Seven-Step Workflow for Strategic Analysis with NotebookLM**

1.  **Define Your Objective:** Begin by clearly defining your research objective. What specific questions are you trying to answer? What insights do you hope to gain?
2.  **Identify Relevant Sources:** Based on your objective, identify the most relevant sources of information. This may include the core documents (Form 10-K, earnings call transcripts, DEF 14A) as well as industry reports, competitor analyses, and news articles.
3.  **Add and Organize:** Add the selected sources to your NotebookLM project. Organize them logically using sections and labels to ensure easy access and retrieval.
4.  **Pause, Think, and Plan:** Before diving into the analysis, take a moment to pause, think, and plan your approach. Translate your research questions into a series of prompts that you'll use to interact with NotebookLM. Write these prompts down in a separate document and review their order and content. Remember that the AI has memory, so the order of your prompts can influence the responses you receive.
5.  **Extract and Analyze:** Use NotebookLM's chat feature to extract critical information and analyze the data. Ask specific questions, experiment with different chat configurations, and save relevant responses as notes.
6.  **Empathize with Your Audience:**  Put yourself in the shoes of your audience (e.g., a strategy analyst, a board member). Use a different AI assistant like ChatGPT or Gemini to adopt this persona and review your findings. Identify any gaps, inconsistencies, or areas for improvement in your analysis.
7.  **Synthesize and Communicate:** Synthesize your findings into a clear and concise format, whether it's a written report, presentation, or set of strategic recommendations.

**Applying the Workflow**

This workflow will guide your research in each phase of the company analysis project:

*   **Industry Analysis:** Extract information about the company's industry, competitive landscape, and key success factors.
*   **Business Strategy Analysis:** Gather insights into the company's competitive advantage, value proposition, and key activities.
*   **Corporate Strategy Analysis:** Analyze the company's organizational structure, portfolio of businesses, and drivers of profitability.

By following this structured approach, you'll ensure that your research is focused, efficient, and aligned with the goals of each analytical phase.

##  Extracting Vital Company Information 

Now that you have a research workflow, let's focus on extracting the essential information you need to build a solid foundation for your company analysis. This baseline knowledge will be crucial for understanding your company's overall strategic position and navigating the upcoming phases of the project.

**Applying the Seven-Step Workflow**

Remember the seven-step workflow we discussed earlier? Let's apply it here to gather that essential baseline knowledge:

1.  **Define Your Objective:** Your objective is to gain a comprehensive understanding of your chosen company. This includes its history, mission, values, organizational structure, leadership, products and services, key markets, and recent performance.
2.  **Identify Relevant Sources:** The core documents (Form 10-K, earnings call transcripts, DEF 14A) are excellent sources for this baseline information. Focus on sections like "Business," "Risk Factors," "Management's Discussion and Analysis," and "Board of Directors" within these documents.
3.  **Add and Organize:** Ensure these documents are added and organized within your NotebookLM project. Create a dedicated section for "Baseline Knowledge" or something similar.
4.  **Pause, Think, and Plan:**  Before you start chatting with your sources, plan your approach. What are the most critical questions you need to answer to build this foundational knowledge? Jot down your prompts in a separate document, paying attention to their order and how they might influence the AI's responses.
5.  **Extract and Analyze:** Now, engage in a conversation with your NotebookLM assistant. Ask questions like:
    *   "What is the company's mission and vision?"
    *   "What are the company's core values?"
    *   "Describe the company's organizational structure."
    *   "Who are the key leaders in the company?"
    *   "What are the company's main products and services?"
    *   "What are the company's key markets?"
    *   "How has the company performed financially in recent years?"
6.  **Empathize with Your Audience:** Imagine you're presenting this baseline information to a colleague who knows nothing about the company. Use another AI assistant (like ChatGPT or Gemini) to review your findings from the perspective of this audience. Do they have a clear and comprehensive understanding of the company? Are there any gaps or inconsistencies in your information?
7.  **Synthesize and Communicate:**  Compile your findings into a concise summary or overview of the company. This could be a written document, a presentation, or even a set of notes within your NotebookLM project.

**Tips for Effective Extraction**

*   Be curious and ask follow-up questions. The more you explore, the deeper your understanding will be.
*   Experiment with different prompt styles to see how the AI responds.
*   Don't be afraid to rephrase your questions if you're not getting the desired information.
*   Save your prompts and the AI's responses for future reference.

By following this structured approach, you'll gain a comprehensive understanding of your chosen company, laying a solid foundation for the more in-depth analyses in the upcoming phases of the project.


## Wrap-Up and Next Steps 

Congratulations! You've now laid the groundwork for your company analysis project. By understanding the key sources of information and mastering the art of extracting vital insights with NotebookLM, you're well-equipped to embark on the next phases of your strategic journey.

**Key Takeaways:**

*   The SEC plays a crucial role in ensuring transparency and providing access to vital company information.
*   Form 10-K, earnings call transcripts, and DEF 14A are essential documents for understanding a company's strategy, performance, and governance.
*   NotebookLM is a powerful tool for organizing, analyzing, and extracting insights from these documents.
*   A structured research workflow helps you navigate the sea of information effectively and efficiently.
*   Building a baseline understanding of your chosen company is crucial before diving into deeper analysis.

**Next Steps:**

In the upcoming lessons, we'll delve into the three core phases of your company analysis project:

*   **Industry Analysis:**  We'll explore Porter's Five Forces and other frameworks to analyze the competitive dynamics of your company's industry.
*   **Business Strategy Analysis:**  We'll examine how your company creates and captures value, differentiates itself from competitors, and sustains its competitive advantage.
*   **Corporate Strategy Analysis:**  We'll investigate how your company manages its portfolio of businesses (if applicable) and makes strategic choices to achieve its goals.

With your NotebookLM project set up and your research workflow in place, you're ready to tackle these challenges and unlock the strategic secrets of your chosen company.  Onward to industry analysis!

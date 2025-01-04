---
title: Chat with Sources
layout: default
parent: NotebookLM Guide
nav_order: 3
---
# Chatting with Sources
{: no_toc}


This section will teach you how to use NotebookLM's chat feature to get the most out of your source documents.

## How it Works

NotebookLM uses advanced AI to understand the content of your sources. When you ask a question, it doesn't just look for matching keywords like a typical search engine. Instead, it performs *semantic search*, which means it actually understands the meaning and context of your words. This allows it to find the most relevant information and provide you with a concise answer, even if your question doesn't use the exact same words as your sources.

**Think of it this way:**

Imagine you're asking a friend who has read all your source documents. You wouldn't need to use perfectly precise keywords; your friend would understand what you mean and give you a helpful answer based on their understanding of the material. That's kind of how NotebookLM works!

**Why this matters:**

Semantic search makes NotebookLM much more powerful than a simple keyword search. It can help you:

* **Find answers even if you don't know the exact terms:**  You can ask questions in your own words, and NotebookLM will figure out what you're looking for.
* **Get more comprehensive answers:**  It can combine information from different parts of your sources to give you a complete picture.
* **Discover insights you might have missed:**  By understanding the context of your sources, it can uncover connections and patterns you might not have noticed on your own.


## Chatting with Sources: Selecting Sources and Configuring Chat

To make the most of your chat sessions, you can customize how NotebookLM analyzes your sources and generates responses.

### Selecting Sources

By default, NotebookLM analyzes all the sources in your notebook when answering your questions. However, you can choose to focus its attention on specific sources. This is helpful when you want to get answers from a particular document or group of documents.

**To select sources:**

1. In the **Sources** panel on the left side of the screen, you'll see a list of all the sources you've added to your notebook.
2. Each source has a checkbox next to it.
3. **To include a source in the analysis**, make sure its checkbox is selected.
4. **To exclude a source**, uncheck its box.
5. AI may automatically create and list prompts based on the content of the sources you chose in the chat panel.

![screenshot showing source selection](/assets/images/source-selection.png)

{: .note}
> If you're familiar with the structure of a source document, you can direct the AI assistant to focus on specific sections.  See the sample prompts for examples of how to do this.

### Configuring Chat

You can also customize how NotebookLM responds to your questions by configuring the chat settings. This allows you to tailor the AI's output to your specific needs.

**To configure chat:**

1. Click the **Configure Chat** button in the chat panel.
2. You'll see options to customize the **conversational style** and **response length**.

**Conversational Styles**

* **Default:** Best for general-purpose research and brainstorming.
* **Analyst:** Best for business-oriented strategy and decision-making.
* **Guide:** Best for sharing your notebook as a group knowledge base or help center.
* **Custom:** Write your own prompt to customize the style and suggest a role. Examples: "respond at a PhD student level," "pretend to be a financial analyst."

**Response Length**

* **Default:**  Provides a balanced response length.
* **Longer:**  Generates more detailed and comprehensive answers.
* **Shorter:**  Provides concise and to-the-point answers.

![Screenshot showing chat configuration](/assets/images/select-source-configure-chat.png)

## Saving to Notes

When you get a helpful response from NotebookLM, you'll probably want to save it for later. That's where notes come in!

**Saving Responses as Notes**

1. **Find the Pin Icon:** Under each chat response, you'll see a button with a pin icon. Click this to save the response as a note. 

2. **Access Your Notes:**  Your saved notes are available in the **Studio** panel on the right-hand side of the screen.

**Turning Notes into Sources**

Here's where things get really interesting: You can actually turn your saved notes *into* sources! This means you can use your own insights and summaries as part of your research.

1. **Open a Note:** Click on a note in the Studio panel to open it.
2. **Convert to Source:** At the bottom of the note, you'll see a button that allows you to convert the note into a source.

   ![screenshot of NotebookLM](/assets/images/convert-to-source.png)

**Why This is Powerful**

This feature allows for a really cool workflow:

1. **Query:** Ask a question about your initial set of sources.
2. **Save:** Save the insightful response as a note.
3. **Convert:** Turn that note into a source.
4. **Query Again:** Ask a new question that includes your converted note *and* other sources.

This is kind of like a "join" query in SQL, where you combine information from different tables. It lets you chain together insights from different sets of sources, building on your previous analysis.




## Let's Chat!

Now it's time to put your chat skills to the test! For this exercise, make sure your chat is configured with the **Analyst** conversational style and **Default** response length. We'll stick with this configuration for the rest of the lab.

**Here's a challenge:**

Work through the prompts in the table below. For each prompt:

1. **Select the Source(s):**  Choose the source(s) indicated in the first column.
2. **Ask the Question:** Copy and paste the prompt into the chat box.
3. **Observe:** Pay attention to how NotebookLM responds, and consider how its answers could be useful for your company analysis projects.
4. **Keyword Search:** After getting the answer from NotebookLM, try searching for some of the keywords from the prompt within the source documents.  Compare this experience to how NotebookLM found and presented the information.

| Sources to Select                                     | Prompt                                                                                                                                                                                                                                                                                         |
| :--------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Form 10-k Business Description (Google Docs)         | How would you describe the business model of the company's advertising business based on the source?                                                                                                                                                                                                 |
| Form 10-k Business Description (Google Docs)         | I want to do a Porter's five forces analysis on industries relevant to the company. What industries should I look at?                                                                                                                                                                               |
| Form 10-k Business Description (Google Docs)         | Can you do a BCG matrix analysis on the company's portfolio of businesses?                                                                                                                                                                                                                      |
| Form 10-k Business Description (Google Docs)         | Give me a summary of "wubba wubba" section.                                                                                                                                                                                                                                                       |
| YouTube videos                                       | Analyze the videos and help me understand the CEO's approach to competition, innovation, and market dominance.                                                                                                                                                                                     |
| YouTube videos                                       | What are interviewers curious about? Compare and contrast interviewers' interests, willingness to challenge the CEO, and approach to shaping the conversation.                                                                                                                                    |
| YouTube videos                                       | I think the media interviews are an avenue to reach specific constituencies such as enterprise customers, activist shareholders, pension fund managers, regulators, and so on. Do you get that sense from the conversations?                                                                         |
| Proxy statements (web URLs)                          | How is the skill composition of the company's board evolving over the years?                                                                                                                                                                                                                        |
| Proxy statements (web URLs)                          | The company is expected to experience significant regulatory action from FTC and DOJ. Which director can provide what assistance to the company and its executive leadership team? Let's think it through.                                                                                        |
| Proxy statements (web URLs)                          | Let's say the company wants to reshape its organizational culture and reporting structure. Let me remind you that the company is a large multinational organization with complex products and operations with significant interdependence. Who among the directors can mentor the CEO in strategic decisions? Explain your answer. |
| Earnings Call Transcripts (pdf sources)              | What are Alphabet's key growth drivers and competitive advantages?                                                                                                                                                                                                                                   |
| Earnings Call Transcripts (pdf sources)              | What business units, initiatives, or issues attracted a lot of analyst questions each year? Based on question and answer interaction, evaluate if the analyst view is positive, neutral, or negative. Explain your reasoning.                                                                              |
| Earnings Call Transcripts (pdf sources)              | Ignore the analyst questions. Focus only on prepared remarks made by company executives before analyst questions. What are some key commonalities and differences across years?                                                                                                                  |
| Earnings Call Transcripts (pdf sources)              | What are the important value chain activities for this company? Do you get a sense it changed over the years?                                                                                                                                                                                     |
| Earnings Call Transcripts (pdf sources)              | Tell me more about partnerships. Who are the partners? Give me a summary of the discussion about alliances and partnerships.                                                                                                                                                                      |
| Item 1A Risk Factors (Copied text)                   | Your task is to create a priority list for the CEO for the new year. Carefully review Item 1A and identify a short list of strategic priorities. Limit the list to 5 and explain your thinking.                                                                                                      |
| Saved Note + Earnings call transcript (pdf source) | Given the CEO's strategic priorities and information from the earnings call transcript, what initiatives do you see in motion that aim to address the top issues?                                                                                                                                 |


**Reflect and Discuss:**

After trying these prompts, take a moment to reflect on your experience. How does using NotebookLM for research compare to your previous methods (e.g., keyword searches, reading through documents)?  Be prepared to share your thoughts in class.
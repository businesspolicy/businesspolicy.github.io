---
title: Working with Sources
layout: default
parent: NotebookLM Guide
nav_order: 2
---
# Working with Sources
{:no_toc}

### Adding and Managing Source Documents

Now that you have your NotebookLM notebook set up, it's time to add the information you'll be working with. NotebookLM lets you add various types of sources to your notebook.

**Adding Sources**

You can add sources to your NotebookLM notebook in a few ways:

* **From a link:** Paste the URL of a webpage, article, or document.
* **From YouTube:** Paste the URL of a YouTube video.
* **From your computer:** Upload pdf, markdown, text, or audio files from your computer.
* **From Google Drive:** Connect your Google Drive to easily import Google Docs and Google Slides files.
* **From copy-pasted text:** Paste copied text in a text box to create a note.
* **Create a blank note:** Start with a blank note to jot down your own ideas or summarize information from other sources.

**Before we dive in, here are a few important things to keep in mind:**

* **Source Names:** You might need to rename sources after adding them to keep your notebook organized.
* **Paywalled Content:**  NotebookLM doesn't support URLs behind paywalls. 
* **URL Content:** Only the text content of a URL will be available in your notebook.
* **YouTube Transcripts:** YouTube videos without API-accessible transcripts aren't fully supported yet. You might be able to copy and paste transcripts for some videos, even if NotebookLM can't add them directly.
* **Google Docs/Slides Updates:** If a Google Doc or Slides file changes after you've added it to your notebook, you'll need to resync it to get the new content.
* **Source Limits:** There's a limit of 300 sources per notebook.
* **Source Size:** Each source can be up to 500,000 words or 200MB for uploaded files.

For more details, check out the [official documentation](https://support.google.com/notebooklm/answer/14276468).

**Let's Add Some Sources!**

To get a taste of company analysis using NotebookLM, let's add some sources for a specific company and try "chatting with the sources".  This lab uses sources for Alphabet Inc. (Google's parent company), but you can choose a different company if you prefer. The sources listed below span the different formats that NotebookLM supports.

| Source Document                     | Years  | Format             |
| :---------------------------------- | :---- | :----------------- |
| End-of-year (Q4) earnings call transcripts | 2023, 2022, 2021 | PDF               |
| Form 10-K Item 1 Business Description   | 2023, 2022, 2021 | Google Docs (links) |
| Form 10-K Item 1A Risk Factors        | 2023, 2022, 2021 | Copied text (.txt)  |
| Proxy statement (DEF 14A)            | 2023, 2022, 2021 | Web URL            |
| CEO Interviews                       | 2024   | YouTube videos     |







<details open markdown="block">
<summary>Source Links</summary>

**Add as PDFs**

<a href="/assets/files/2023-q4-earnings-transcript.pdf" download="2023-q4-earnings-transcript.pdf" target="_blank">Alphabet Earnings Call Transcript 2023 Q4</a>

<a href="/assets/files/2022_Q4_Earnings_Transcript.pdf" download="2022-q4-earnings-transcript.pdf" target="_blank">Alphabet Earnings Call Transcript 2022 Q4</a>

<a href="/assets/files/2021_Q4_Earnings_Transcript.pdf" download="2021-q4-earnings-transcript.pdf" target="_blank">Alphabet Earnings Call Transcript 2021 Q4</a>

**Add as Google Docs**


```
https://docs.google.com/document/d/19TiZiJhSFw5RFQ7tXmOwo5cBjNzTinsQUd0tw0fjqv0/edit?usp=sharing
```

```
https://docs.google.com/document/d/1L6hVPMn5tzfvXzHC8G1xt5gzQa9qwWJZPcmwG0dogoo/edit?usp=sharing
```

```
https://docs.google.com/document/d/1ICchcF-2iHQNp-Yid7SOWsXiY-WHKwaIRs1zVWmJnQs/edit?usp=sharing
```

**Add as copied text**

<a href="/assets/files/form10k-item1a-2023.txt" download="form10k-item1a-2023.txt" target="_blank">Alphabet Form 10-K Item 1A 2023</a>

<a href="/assets/files/form10k-item1a-2022.txt" download="form10k-item1a-2022.txt" target="_blank">Alphabet Form 10-K Item 1A 2022</a>

<a href="/assets/files/form10k-item1a-2021.txt" download="form10k-item1a-2021.txt" target="_blank">Alphabet Form 10-K Item 1A 2021</a>

**Add as links**


```
https://abc.xyz/assets/e0/41/5972aa12b89a8e1954900055b3df/0c9934bb7f7fde636dc0366589df5ca0.html
```

```
https://abc.xyz/assets/12/e0/b30cbbc2e5cf7ca8952690d9c123/0e73ce27bbcd63b1fd01ba95425d55ea.html
```

```
https://abc.xyz/assets/99/13/6c33e12465662b6e5dfdaf7629e1/cc2227c186c921826062580d4bbd819b.html
```

**Add as YouTube videos**


```
https://www.youtube.com/watch?v=OsxwBmp3iFU
```

```
https://www.youtube.com/watch?v=5puu3kN9l7c
```

</details>


**Next Steps**

Now that you know how to add and manage sources, let's move on to the exciting part: chatting with your source documents! In the [next section](/tutorials/notebooklm-guide/chat), we'll learn how to ask questions and get information from your sources using NotebookLM's AI capabilities.



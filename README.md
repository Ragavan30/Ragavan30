<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E1B4B,50:4F46E5,100:14B8A6&height=200&section=header&text=Ragavan%20R&fontSize=52&fontColor=ffffff&fontAlignY=42&desc=AI%20Engineer%20—%20RAG%20Systems%20%26%20Agentic%20AI&descAlignY=62&descSize=16&animation=fadeIn&fontFamily=JetBrains%20Mono"/>

<sub>Chennai, India · Available for full-time roles</sub>

</div>

<br/>

<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=500&size=22&duration=3200&pause=1400&color=4F46E5&center=true&vCenter=true&width=680&lines=I+ground+language+models+in+real+data.;I+turn+unstructured+documents+into+structured+truth.;I+build+agents+that+act%2C+not+just+answer." alt="headline"/>
</div>

<br/>

<p align="center">
<a href="https://www.linkedin.com/in/ragavan-r-aa8a032b3/"><strong>LinkedIn</strong></a> &nbsp;·&nbsp;
<a href="https://portfolio-ro7s.vercel.app/"><strong>Portfolio</strong></a> &nbsp;·&nbsp;
<a href="mailto:ragavannnn1@gmail.com"><strong>Email</strong></a> &nbsp;·&nbsp;
<a href="https://github.com/Ragavan30"><strong>GitHub</strong></a>
</p>

<div align="center">

—

</div>

<br/>

## Who I am

Most of what gets called "AI engineering" is really data engineering with a language model bolted on. That's the part I like — the unglamorous work of taking a pile of real, messy documents and turning them into something a model can reason over correctly. I'm currently building that at **Aieton Labs**, where insurance policy documents go in as scanned PDFs and come out as grounded, structured answers.

I came into AI through full-stack development, not around it, which shapes how I build: I care as much about the pipeline shipping to production as I do about the model inside it. Four years of Computer Science at Anna University, a CGPA of 8.1, and a habit of finishing what I start.

<br/>

## What I solve

Three problems keep showing up in my work, in different clothes each time:

**Grounding.** Language models are fluent and frequently wrong. My job is closing that gap — retrieval pipelines that hand the model the right five paragraphs instead of hoping it remembers something similar from training.

**Extraction.** Businesses run on documents that were never meant to be read by software — policy forms, claim reports, scanned contracts. I write the prompts and pipelines that pull structured fields out of that chaos reliably enough to trust in production.

**Autonomy.** Some workflows shouldn't need a human in the loop for every step. I design agents that can decide which tool to call and when, so a multi-step query resolves on its own.

<br/>

<div align="center">

—

</div>

<br/>

## How I build

A RAG system is only as good as its weakest stage. This is the shape I default to, and the one currently running in production at Aieton Labs:

```
01  INGEST     raw PDFs, forms, scanned policy documents
02  CHUNK      context-aware splitting, not fixed-size guessing
03  EMBED      vectorized representations for semantic search
04  RETRIEVE   top-k relevant context, ranked and filtered
05  GENERATE   LLM response grounded in retrieved source, not memory
```

Every stage above has failed silently on me at least once — a bad chunking strategy or an ungrounded prompt will still produce a confident-sounding answer. I'd rather spend time on evaluation and validation at each step than trust the output at the end.

The same discipline carries into the agent work: an agent that calls the wrong tool is worse than no agent at all, so tool-routing gets tested like code, not vibes.

<br/>

## Projects

<br/>

**FixiFox — a multi-model AI debugger**

*Problem.* Developers lose time bouncing between tools — a linter here, a security scanner there, a separate window for an explanation of *why* the bug happened.

*Approach.* One interface, seven LLMs. FixiFox routes a given piece of code to the model best suited for the task — bug detection, generation, security analysis, or language conversion — inside a Monaco-powered editor with session history and authenticated user state.

*Outcome.* 80% bug-identification accuracy, and a 60% cut in debugging time in testing.

`Python` `Streamlit` `Groq API` `Monaco Editor` `SQLite`
&nbsp;·&nbsp; [Repository](https://github.com/Ragavan30)

<br/>

**Real-time drowsiness detection**

*Problem.* Driver fatigue is hard to self-report and easy to miss until it's dangerous.

*Approach.* Facial landmark tracking via OpenCV and Dlib, running continuously and unattended, triggering an audio alert and an emailed snapshot the moment drowsiness patterns appear — no dashboard required, no human watching a screen.

*Outcome.* 90% detection accuracy in real-time testing conditions.

`Python` `OpenCV` `Dlib` `SMTP`
&nbsp;·&nbsp; [Repository](https://github.com/Ragavan30)

<br/>

**Earthquake prediction from seismic data**

*Problem.* Early warning systems are only useful if the pattern recognition behind them is trustworthy.

*Approach.* Applied classical ML — pandas-driven feature analysis and scikit-learn models — to seismic datasets, treating the data-analysis phase as its own deliverable rather than rushing to a model.

*Status.* Phase one complete; model optimization ongoing.

`Python` `Pandas` `Scikit-learn`
&nbsp;·&nbsp; [Repository](https://github.com/Ragavan30/AI-BASED-EARTHQUAKE-PREDICTION-MODEL)

<br/>

<div align="center">

—

</div>

<br/>

## Technical expertise

<table>
<tr>
<td valign="top" width="50%">

**Artificial Intelligence**
RAG pipeline design · LLM integration · Prompt engineering · Agentic AI (Microsoft Agentic Framework) · Semantic search · Vector databases

**Backend & Data**
Python · Flask · SQL · MongoDB · SQLite · NumPy · Pandas

</td>
<td valign="top" width="50%">

**Frontend**
JavaScript · HTML5 · CSS3 · Bootstrap · Material UI · Streamlit

**Tooling & Delivery**
Git · GitHub · Vercel · Render · n8n · Postman · Figma · Linux

</td>
</tr>
</table>

<br/>

## Engineering philosophy

I optimize for the version that ships, then improve it — a working pipeline with rough edges beats a perfect design still in a document. I default to the simplest architecture that satisfies the requirement, and add complexity only when the simple version demonstrably fails. And I treat evaluation as part of the build, not a step after it: an AI feature without a way to measure whether it's actually working isn't finished, it's a demo.

<br/>

<div align="center">

—

</div>

<br/>

## Currently

<table>
<tr>
<td width="33%" valign="top"><strong>Building</strong><br/>Production RAG and document-extraction systems for insurance workflows at Aieton Labs</td>
<td width="33%" valign="top"><strong>Learning</strong><br/>Deeper evaluation methodology for agentic systems — where autonomy tends to break</td>
<td width="33%" valign="top"><strong>Open to</strong><br/>Full-time AI Engineer and Software Engineer roles</td>
</tr>
</table>

<br/>

## GitHub activity

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ragavan30&layout=compact&hide_border=true&bg_color=00000000&title_color=4F46E5&text_color=64748B&langs_count=6" height="150"/>
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ragavan30&hide_border=true&bg_color=00000000&color=4F46E5&line=14B8A6&point=64748B" width="90%"/>
</div>

<br/>

<div align="center">

—

### Let's talk

If you're solving a problem where the data is messy, the stakes are real, and "it works on the demo" isn't good enough — I'd like to hear about it.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-4F46E5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ragavan-r-aa8a032b3/)
[![Portfolio](https://img.shields.io/badge/Portfolio-14B8A6?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-ro7s.vercel.app/)
[![Email](https://img.shields.io/badge/ragavannnn1%40gmail.com-64748B?style=flat-square&logo=gmail&logoColor=white)](mailto:ragavannnn1@gmail.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14B8A6,100:1E1B4B&height=120&section=footer"/>

</div>

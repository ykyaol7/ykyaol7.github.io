---
layout: plain
title: "Reasoning with LLMs (UdS; Summer25/26)"

---

[//]: # (Course Title: Reasoning with LLMs: Techniques, Capabilities and Beyond)

### Course Description

Large Language Models (LLMs) have become powerful tools capable of performing
a wide range of human-like tasks, from translation to complex problem-solving.
However, reasoning, the ability to logically infer, plan, 
and generalize, remains a fundamental challenge that distinguishes them 
from human intelligence. While techniques like Chain-of-Thought prompting
and specialized training methods have significantly improved reasoning, 
the question of whether they can truly replicate human-like reasoning 
and how to approach it remains open.
In this seminar, we will explore recent advancements in reasoning with LLMs,
including techniques for improving their performance, 
analyses of how these models reason, and discussions on how to move
beyond current approaches.



### Prerequisites

Students should have a solid background in NLP and machine learning. 
Prior familiarity with language models, particularly transformer-based architectures like GPT-2, and common usage paradigms such as in-context learning and supervised fine-tuning will be assumed.



### Registration

Please send an email to ykyao@lst.uni-saarland.de to indicate top-3 preferences of papers you are willing to present. The papers should be selected from the **Reading** column in the schedule section below. Please use the subject [LLM reasoning seminar] for your email and preferably send before April 21st.

If you’d like to propose an alternative reading that fits the week’s topic, reach out early. Substitutions are welcome as long as they align with the topic and we have time to read them.



### Information

**Instructor:** [Yuekun Yao](https://ykyaol7.github.io/)



### Course Format & Expectations

This seminar is built around group discussion of recent research. Each week, we’ll focus on one or more papers related to the topic of the week. While you're not expected to read every paper in depth, you should be familiar with the main ideas and come prepared to listen actively, ask questions, and contribute to the conversation.

Each student will take the lead for one session during the semester. As session leader, you’ll guide our discussion of the assigned paper and help the group unpack its contributions, assumptions, and implications. Your responsibilities include:

- **Presenting the paper**: What is the paper’s goal? How does it approach the problem? What are the main contributions? Making slides is welcome but entirely optional.
- **Raising discussion points**: Highlight the paper’s strengths, limitations, potential impact, and what it leaves open for future work.
- **Engaging with the discussion**: Be ready to answer questions.  You don’t need to have all the answers, but you should know the paper well.

All participants are also expected to engage actively in the discussion. You should come to each session with some interesting questions or comments to contribute.



### Evaluation

For students taking the seminar for 4 credits:

```
Presentation: 60%
Participation in discussion: 40%
```

For students taking the seminar for 7 credits:

```
Presentation: 30%
Participation in discussion: 20%
Term paper: 50%
```



### Term paper

There are two options for the term paper. If you are not sure about your topic, feel free to reach out and ask. 

- A survey paper focusing on a relevant topic.
- A replication paper that reproduces an existing paper and explores research questions not covered in the original work.

Note that a survey paper does **not** mean simply summarizing several existing papers. You are expected to include your own insights. For example, you can propose a taxonomy to organize relevant works, highlight research questions that are important but understudied, or suggest novel research ideas. Running experiments to support your points can be very useful, but it is not required. Including figures to provide overviews or illustrate methods is recommended to make your paper easier to follow.

For the replication option, you should reproduce the method or experiments of an existing paper and investigate new research questions that were not addressed in the original work. For example, you could extend the method, design new experiments, or adapt it to a different scenario or domain. As long as you ask interesting questions and make reasonable decisions to approach them, it will be a strong term paper. This means that you are not expected to always produce positive results. Negative results can also be insightful.

A typical structure for the paper may include (but is not limited to):

- **Introduction**: Define the scope of your paper, the motivation to study it and the key research questions or challenges.
- **Background**: Provide a brief literature review or background knowledge the readers need to know before diving into the main body.
- **Main body of your survey or replication**: For the survey paper, you do not need to cover all relevant works on the topic, but you should include at least 2 or 3 important ones. You are also responsible for searching and selecting relevant papers on your own. For the replication paper, introduce what you did and report results.
- **Discussion**: Compare methods and results (for survey papers), or analyze your findings (for replication papers). Discuss what has been addressed and what remains open.
- **Conclusion**: Summarize the key takeaways and include potential future directions in your mind.

**Format:** The term paper should be at most 8 pages, with no minimum page limit. The format can be [ACL](https://www.overleaf.com/latex/templates/acl-2023-proceedings-template/qjdgcrdwcnwp), [ICLR](https://www.overleaf.com/latex/templates/template-for-iclr-2025-conference-submission/gqzkdyycxtvt), or [NeurIPS](https://www.overleaf.com/latex/templates/neurips-2024/tpsbbrdqcmsh). Reference pages are not counted.

**Slides:** Here are the [slides](../../slides/Course_Logistics.pdf) of the course logistics. 

<!--**Note: Another option for the term paper is to reproduce existing methods on some reasoning tasks and play around with aspects of the method or tasks.**-->

  

### Schedule

Below is the schedule for the course. The readings are subject to change. 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
<div class="container mt-4">
  <table class="table table-striped table-bordered">
    <thead class="table-dark">
      <tr>
        <th>Topic</th>
        <th>Subtopic</th>
        <th>Reading</th>
        <th>Optional</th>
        <th>Date</th>
        <th>Discussion Leader</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2">Introduction</td>
        <td>Course Logistics</td>
        <td></td>
        <td></td>
        <td>2025-04-15</td>
        <td>Yuekun</td>
      </tr>
      <tr>
        <td>Overview</td>
        <td></td>
        <td></td>
        <td>2025-04-22</td>
        <td>Yuekun</td>
      </tr>
      <tr>
        <td rowspan="6">Inference</td>
        <td>chain-of-thought</td>
        <td>
          <a href="https://arxiv.org/abs/2201.11903" target="_blank">Chain-of-Thought Prompting Elicits Reasoning in Large Language Models</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2211.12588" target="_blank">Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks</a>
        </td>
        <td>2025-04-29</td>
        <td>Alexander Wehner</td>
      </tr>
      <tr>
        <td>rationale exploration</td>
        <td>
          <a href="https://arxiv.org/abs/2203.11171" target="_blank">Self-Consistency Improves Chain of Thought Reasoning in Language Models</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2305.10601" target="_blank">Tree of Thoughts: Deliberate Problem Solving with Large Language Models</a>
        </td>
        <td>2025-05-06</td>
        <td>Zhenyu Feng</td>
      </tr>
      <tr>
        <td>task decomposition</td>
        <td>
          <a href="https://arxiv.org/abs/2205.10625" target="_blank">Least-to-Most Prompting Enables Complex Reasoning in Large Language Models</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2209.15003" target="_blank">Compositional Semantic Parsing with Large Language Models</a>
        </td>
        <td rowspan="2">2025-05-13</td>
        <td>Franka Beyer
        </td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/pdf/2402.10200" target="_blank">Chain-of-Thought Reasoning without Prompting</a>
        </td>
        <td></td>
        <td>Eva Gavaller
        </td>
      </tr>
      <tr>
        <td>verification</td>
        <td>
          <a href="https://arxiv.org/abs/2110.14168" target="_blank">Training Verifiers to Solve Math Word Problems</a>
        </td>
        <td></td>
        <td>2025-05-20</td>
        <td>Sree Harsha Sunaye</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/pdf/2305.20050" target="_blank">Let’s Verify Step by Step</a>
        </td>
        <td></td>
        <td>2025-05-27</td>
        <td>Ümit Altar Binici</td>
      </tr>
      <tr>
        <td rowspan="5">Learning</td>
        <td>SFT</td>
        <td>
          <a href="https://arxiv.org/abs/2112.00114" target="_blank">Show Your Work: Scratchpads for Intermediate Computation with Language Models</a>
        </td>
        <td></td>
        <td>2025-06-03</td>
        <td>Pranav Kushare</td>
      </tr>
      <tr>
        <td>bootstrapping</td>
        <td>
          <a href="https://arxiv.org/abs/2203.14465" target="_blank">STaR: Bootstrapping Reasoning With Reasoning</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2403.09629" target="_blank">Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking</a>
        </td>
        <td>2025-06-10</td>
        <td>Yu Yamashita</td>
      </tr>
      <tr>
        <td>reinforcement tuning</td>
        <td><a href="https://arxiv.org/abs/2501.12948" target="_blank">DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning</a></td>
        <td><a href="https://arxiv.org/abs/2411.15124" target="_blank">Tulu 3: Pushing Frontiers in Open Language Model Post-Training (Section 6)</a></td>
        <td>2025-06-17</td>
        <td>Nadia Asmi</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2501.19393" target="_blank">s1: Simple test-time scaling</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2501.17161v1" target="_blank">SFT Memorizes, RL Generalizes: A Comparative Study of Foundation Model Post-training</a>
        </td>
        <td>2025-06-24</td>
        <td>Aravind Krishnan</td>
      </tr>
      <tr>
        <td>latent reasoning</td>
        <td><a href="https://arxiv.org/abs/2412.06769" target="_blank">Training Large Language Models to Reason in a Continuous Latent Space</a></td>
        <td></td>
        <td>2025-07-01</td>
        <td>Shane John Paul</td>
      </tr>
      <tr>
        <td rowspan="2">Analysis</td>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2304.03843" target="_blank">Do Large Language Models Latently Perform Multi-Hop Reasoning?</a>
        </td>
        <td></td>
        <td>2025-07-08</td>
        <td>Antonia</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2307.02477" target="_blank">Reasoning or Reciting? Exploring the Capabilities and Limitations of Language Models Through Counterfactual Tasks</a>
        </td>
        <td></td>
        <td>2025-07-15</td>
        <td>Fedor Sizov</td>
      </tr>
    </tbody>
  </table>
</div>
</body>
</html> 

### Contact

Please contact Yuekun (ykyao@lst.uni-saarland.de)  for any questions.

Office: Building C7 2, R. 2.04

Office hour: Wednesday 4-5pm

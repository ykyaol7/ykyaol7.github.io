---
layout: plain
title: "Reasoning with LLMs (UdS; Summer25/26)"

---

[//]: # (Course Title: Reasoning with LLMs: Techniques, Capabilities and Beyond)

### Course Description

Large Language Models (LLMs) have become powerful tools capable of performing
a wide range of human-like tasks, from translation to complex problem-solving.
However, reasoning—the ability to logically infer, plan, 
and generalize—remains a fundamental challenge that distinguishes them 
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



### Information

**Instructor:** [Yuekun Yao](https://ykyaol7.github.io/)



### Course Format & Expectations

This seminar is built around group discussion of recent research. Each week, we’ll focus on one or more papers related to the topic of the week. While you're not expected to read every paper in depth, you should be familiar with the main ideas and come prepared to listen actively, ask questions, and contribute to the conversation.

Each student will take the lead for one session during the semester. As session leader, you’ll guide our discussion of the assigned paper and help the group unpack its contributions, assumptions, and implications. Your responsibilities include:

- **Presenting the paper**: What is the paper’s goal? How does it approach the problem? What are the main results?
- **Raising discussion points**: Highlight the paper’s strengths, limitations, potential impact, and what it leaves open for future work.
- **Engaging with the discussion**: Be ready to answer questions.  You don’t need to have all the answers, but you should know the paper well.

Making slides is welcome but entirely optional.

If you’d like to propose an alternative reading that fits the week’s theme, reach out early. Substitutions are welcome as long as they align with the topic and we have time to review them.



## Schedule & Reading List

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
        <th>Date</th>
        <th>Reading</th>
        <th>Optional</th>
        <th>Discussion Leader</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2">Introduction</td>
        <td></td>
        <td></td>
        <td></td>
        <td>Yuekun</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td></td>
        <td>Yuekun</td>
      </tr>
      <tr>
        <td rowspan="6">Inference</td>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2201.11903" target="_blank">Chain-of-Thought Prompting Elicits Reasoning in Large Language Models</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2211.12588" target="_blank">Program of Thoughts Prompting</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2203.11171" target="_blank">Self-Consistency Improves Chain of Thought Reasoning in Language Models</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2305.10601" target="_blank">Tree of Thoughts</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2303.17651" target="_blank">Self-Refine: Iterative Refinement with Self-Feedback</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2310.01798" target="_blank">LLMs Cannot Self-Correct Reasoning Yet</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2205.10625" target="_blank">Least-to-Most Prompting Enables Complex Reasoning</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2209.15003" target="_blank">Compositional Semantic Parsing</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2110.14168" target="_blank">Training Verifiers to Solve Math Word Problems</a>
        </td>
        <td></td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/pdf/2305.20050" target="_blank">Let’s Verify Step by Step</a>
        </td>
        <td></td>
        <td>TBD</td>
      </tr>
      <tr>
        <td rowspan="2">Post-train</td>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2112.00114" target="_blank">Show Your Work: Scratchpads for Intermediate Computation</a>
        </td>
        <td></td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2203.14465" target="_blank">STaR: Bootstrapping Reasoning With Reasoning</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2501.04519" target="_blank">rStar-Math</a><br>
          <a href="https://arxiv.org/abs/2403.09629" target="_blank">Quiet-STaR</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td rowspan="2">Test-time Scaling</td>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2501.12948" target="_blank">DeepSeek-R1</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2411.15124" target="_blank">Tulu 3 (Section 6)</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2501.19393" target="_blank">s1: Simple Test-time Scaling</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2501.17161v1" target="_blank">SFT Memorizes, RL Generalizes</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td rowspan="2">Analysis</td>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2304.03843" target="_blank">Why Think Step by Step?</a>
        </td>
        <td></td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2307.02477" target="_blank">Reasoning or Reciting?</a>
        </td>
        <td></td>
        <td>TBD</td>
      </tr>
      <tr>
        <td rowspan="2">Limitations & Beyond</td>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2402.16837" target="_blank">Do LLMs Latently Perform Multi-Hop Reasoning?</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2405.15071" target="_blank">Grokking of Implicit Reasoning</a>
        </td>
        <td>TBD</td>
      </tr>
      <tr>
        <td></td>
        <td>
          <a href="https://arxiv.org/abs/2412.06769" target="_blank">Training LLMs to Reason in a Continuous Latent Space</a>
        </td>
        <td>
          <a href="https://arxiv.org/abs/2405.14838" target="_blank">From Explicit CoT to Implicit CoT</a>
        </td>
        <td>TBD</td>
      </tr>
    </tbody>
  </table>
</div>



</body>
</html>
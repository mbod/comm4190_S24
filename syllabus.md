

# "Talking with AI" - Computational and Communication Approaches


## Spring 2024


### Tue/Thur 3.30-5.00pm (Room: ASC 109)


### Professor: Matt O'Donnell (he/him/his)

-   Email: mbod@asc.upenn.edu
-   Office Hours: via Zoom (see link in Canvas)
    -   Specfic times TBA
        -   But this may vary and I will always try and be available for
            appointments outside these times if you email with sufficient
            notice.

---


# IMPORTANT NOTICES


## 1. HEALTH AND WELLNESS

-   Covid-19 and other respiratory viruses are continuing to evolve and
    infection and hospitalization rates continue to show depressing
    cycles of surge and fall, at both a local and national level&#x2013;long
    beyond what was hoped almost four years ago.

-   To reduce the risk of infection and increase the possibility of
    wellness allowing us to focus on learning and working together,
    please be monitor your health and be mindful of others around
    you. You are always welcome to wear a mask in class for whatever
    reason and the professor will frequently do so.

-   This is a request for us to think socially about how our choices
    impact others and how we can maximize learning opportunities.
    **Please respect each other's choices on this issue**.


## 2. ATTENDANCE, ZOOM AND CLASS RECORDINGS

-   **ZOOM AND CLASS ATTENDANCE WHEN UNWELL** - If you feel sick or are
    showing symptoms of Covid-19, flu or cold then **PLEASE BE
    CONSIDERATE** of your classmates and attend the class remotely
    through Zoom. All class sessions will be available live through Zoom
    (see links in Canvas) and as recordings.

-   Please make use of ****absence notices**** in `Path@Penn` to inform the
    professor if you need to miss class due to extenuating
    circumstances. Submitting an absence notice does not excuse students
    from their course obligations. But you can view missed class session
    in class recordings in Canvas.

---


# Course Description Goals and Objectives

Increasingly, our daily communications involve responding to and
interacting with language produced by artificial intelligence
models. On the surface, large language models (LLMs) and generative AI
tools (e.g ChatGPT, Bard, etc.) appear to have crossed a milestone in
terms of their human-like ability to generate coherent and idiomatic
texts. This has significant implications (both positive and negative)
for human communication systems and their products, from creative
fiction to news, from academic texts to social media content. It also
raises many questions around whether we can identify, trust, learn
from and use AI generated language.

In this course, we will begin to answer these questions in two
ways:

1.  Analyzing Key Issues: Drawing upon relevant frameworks in
    communication and language theory we will explore the
    transformative nature of AI-generated communication and its impact
    on individuals and society.
2.  Hands-on Application: In parallel, students will acquire skills
    using Python in implementing machine and deep learning models to
    better understand how they work and explore their abilities and
    limitations. We will code various AI models, such as a simple voice
    assistant, image classifier, misinformation identifier, and a basic
    text generative application.

Through this course students will be equipped for a range of contexts
impacted by developments in AI. The course requires students to have a
basic experience in Python coding and using Jupyter notebooks.


## Objectives

Through this course students will:

-   Develop an understanding of how LLMs work at various conceptual
    levels (above the low-level technical/mathematical), including the
    three stages of training (pre-training, fine-tuning and RLHF) and
    the key component of these models, namely the `Transformer`

-   Consider questions of:
    -   `how` and `what` LLMs learn during training and ongoing usage
    -   what level and kind of (if any) understanding and representation of meaning do LLMs exhibit and actually have
    -   to what extent are LLMs able to reason, plan, create models of the world and others (e.g. Theory of Mind)
    -   what kinds of `emergent` knowledge and behaviors LLMs seem to
        exhibit as they increase in size (of both data and parameters) and the implications of these phenomena

-   Learn the basic theoretical framework and concepts from pragmatics
    (the theory of `meaning in context` in language use) and consider and test `if` and `how` LLMs are able to


# Assessment


## Overview of assignments

-   Prompt/response and readings blogging (30%)

-   Coding assignments (15%)

-   Research project (20%)

-   Final Project (35%)


## Details

1.  Prompt/response blog (30%)
    -   Over the course of the semester you will create 2 or 3 blog posts
        a week using the notebook blogging system setup to generate a
        github pages blog
    -   Each blog post should be a short and engaging analysis exploring topics such as:
        -   how LLMs respond to specific prompts
        -   whether they are are able or unable to mirror certain human
            communicative behaviors (e.g. recognize and use idioms)
        -   demonstrate the use of an LLM for a specific task
            (e.g. generating product names, descriptions and branding)
    -   Students are engaged to follow each others blogging

2.  Coding Assignments (15%)
    -   There will be a small number of coding assignments to help
        practice the use of LLMs through APIs, do batch processing of
        prompts, evaluate responses and models, creating a RAG LLM system
        and simple finetuning
    -   Assignments will be released as Jupyter notebooks and submitted through JupyterHub

3.  Research Project (20%)
    -   The focus of this project is to either:
        1.  Select a theoretical communication framework
            (e.g. Accomodation Theory) developed to explain human
            communication behavior and explore its implications for
            communicating with (in both senses) an LLM.
        2.  Examine a specific communicative context or example
            (e.g. political debate, interaction between customer and
            service representive, a messaging campaign in health
            communication, etc.) and explore whether and how LLMs might be
            used and the associated implications.
    -   Write a paper/report in Markdown using Zotero citations.

4.  Final Project (35%)


# Textbooks and recommended readings


## Textbooks

Mitchell, M. (2019) *Artificial Intelligence: A Guide for Thinking
Humans*.

-   This book is referenced as `AITH` in the schedule below.

Phoenix, J. & Taylor, M.(2024) *Prompt Engineering for Generative AI*. O'Reilly Media, Inc.

-   This book is referenced as `PEGAI` in the schedule below.


## Other readings

Wolfram, S. (2023) *What Is ChatGPT Doing … and Why Does It Work?*. Blog post February 14, 2023

-   <https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/>


# Schedule


## **NOTE** This is a tentative schedule is will be updated as the course progresses


## Class structure

-   Usually each class session will be divided into two parts:

-   **Content and Discussion** - This part of the class will introduce
    and review the key topics onlined in the schedule. It is important
    that you read the assigned material BEFORE the class as you'll be
    expected to engage in discussion and other activities based on this
    content.
-   **Lab activities** - The second part will be focused on pratical
    exercises to put into practice what we have been learning about
    thinking about, collecting, analyzing, interpreting and
    communicating data. This will include learning some basic steps
    using Python and R scripts and some other tools for data analysis
    and visualization.


## Week 1 - Introduction and Setup


### Thursday 18 January

-   Introduction to and overview of the class
-   Setup and testing of JupyterHub
    -   ****IMPORTANT**** Make sure you have completedd initial survey quiz in Canvas to get
        your github userid setup on the class server.


## Week 2 - Introduction and Setup

READINGS: Wolfram 2023 Blog post *What is ChatGPT Doing*


### Tuesday 23 January

-   Understanding what LLMs are doing - next word prediction
-   Some challenges for LLMs
    -   spatial logic
    -   theory of mind (ToM) scenarios


### Thursday 25 January

-   Language as interaction and exchange
    -   Turn types in conversation
        -   Statements & Questions
        -   Offers & Demands
    -   Responses: Compilance vs Challenge
-   Looking at GPT2
    -   Word embeddings


## Week 3 - Prompting and How LLms are trained (Part 1)

READINGS:

-   `PEGAI` Ch. 1

(<https://learning.oreilly.com/library/view/prompt-engineering-for/9781098153427/ch01.html>)


### Tuesday 30 January

-   Overview of Prompt Engineering
-   Overview of how LLMs are built
    1.  Pretraining
        -   Self-supervised
        -   Next word prediction
    2.  Finetuning
        -   Domain
        -   Task
        -   Instruction
    3.  Reinforcement Learning
        -   RLHF: Reinforcement Learning from Human Feedback
-   How LLMs work (continued)
    -   Embeddings


### Thursday 01 February

-   Exercise: Using LLMs to create a branding for a product
-   Tool: <https://chat.lmsys.org>
    -   Comparing responses from multiple LLMs


## Week 4 - Prompting and How LLMs are trained (Part 2)

READINGS:

-   `PEGAI` Ch. 2 (<https://learning.oreilly.com/library/view/prompt-engineering-for/9781098153427/ch02.html>)


### Tuesday 06 February

-   Setting up blogging platform for Prompt/Response Logbook Assignment


### Thursday 08 February

-   Watch this video: <https://www.youtube.com/watch?v=OFS90-FX6pg>

-   How do LLMs work
    -   Dealing with context
    -   Transformer and self-attention
-   How LLMs are trained
    -   Stage 1: Pretraining

-   Open vs Closed (Proprietory) models
-   Running local LLMs


## Week 5 - How LLMs are trained and does conversation work?

READINGS: 

-   `PEGAI` Ch. 3 (<https://learning.oreilly.com/library/view/prompt-engineering-for/9781098153427/ch03.html>)


### Tuesday 13 February

-   How LLMs are trained
    -   Stage 2: Fine Tuning
        1.  Domain
        2.  Task
        3.  Instruction
-   From next word prediction tool to chatbot


### Thursday 15 February


## Week 6 -

READINGS: 


### Tuesday 20 February


### Thursday 22 February


## Week 7 -

READINGS: 


### Tuesday 27 February


### Thursday 29 February


## SPRING BREAK (2-10 March)


### NO CLASSES


## Week 8 -

READINGS: 


### Tuesday 12 March


### Thursday 14 March


## Week 9 -

READINGS: 


### Tuesday 19 March


### Thursday 21 March


## Week 10 -

READINGS: 


### Tuesday 26 March


### Thursday 28 March


## Week 11 -

READINGS: 


### Tuesday 02 April


### Thursday 04 April


## Week 12 -

READINGS: 


### Tuesday 09 April


### Thursday 11 April


## Week 13 -

READINGS: 


### Tuesday 16 April


### Thursday 18 April


## Week 14 -

READINGS: 


### Tuesday 23 April


### Thursday 25 April


## Week 15 -

READINGS: 


### Tuesday 30 April


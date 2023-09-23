# Instructions to write a literature review
The purpose of these instructions is to help you write a literature review for your research
project. The main objective of a literature review is two-fold. First, it identifies knowledge
gaps in the current literature that you can address. This allows you to use the current
knowledge and avoid redoing existing work. Second, when included in a publication (as it is
often the case), the literature review's main objective is to clearly explain the differences
between the publication and previous works. This shows the readers (and reviewers) that the
publication is presenting novel contributions. 

One more thing before we start. These guidelines are not absolute, so you can adjust as you see
fit. However, I recommend you follow them at first and then try to adjust if needed. 

## Define the research topic
The research topic will guide your search for related papers. Usually, the research topic
is formed by three parts: a problem, a solution, and a methodology. For example,
consider the research topic: "Preventing impersonation attacks in Low Earth Orbit Satellite networks
using deep learning-based physical-layer authentication". In this case, the problem is
"impersonation attacks in low earth orbit satellite networks" the solution is, "physical layer
authentication", and the methodology is "deep learning".

You may already have a research topic that you can directly use. You may also use the research topic of
an existing paper (or unpublished project) that you are interested in investigating further.

### Task
Before going to the next step, write your research topic and identify the problem, the solution, and the
methodology. We will use it to determine the keywords in our search for related papers.

## Search for papers
To find papers, you will use an academic paper search engine. Semantic
Scholar is a good option as it provides a TLDR for each paper, which is a one or two sentence
summary of the paper. This is usually more useful than the abstract when first looking for
papers. It also provides an API, which can allow you to automate the literature review process. Google
Scholar is a popular choice but does not provide a TLDR nor an API. 

The search process usually involves three steps. 

1. Collect the papers referenced by the paper from which you derived your research topic. 
    - If your research topic comes from an existing paper, the authors have already done a lot of the
      work for you! The easiest way to get a list of references in this papers is to use the
      references feature of the search engine. Simply find your paper in the search engine and there
      should be a link to a list of references already collected for you. 
2. Collect the papers that reference your reference point paper. 
    - If the paper that you use to define your research topic has been around for a year or more, there
      may be other papers that cite it. Again, the easiest way to find them is to use the search engine.
      These papers can usually be found under "cited by" or "citations" buttons. 
3. Search for additional papers using the words in your research topic. 
    - The references collected by the paper's authors may be incomplete. They may have had to remove a
      few to meet page limits, other authors may have reached similar conclusions independently, or they
      simply missed them. It is important that you run your own searches using different keyword
      combinations.
4. Visualize the references.
    - Visualizing how papers reference each other can help you better understand the evolution of a topic.
    - [Litmaps](https://www.litmaps.com/) provides a graph visualization of the refences and cited by paper for a
      given publication.
    - SemanticScholar also provides a graph functinality through its API. 

There are several ways to keep track of the papers at this point. The easiest way is to keep different
browser tabs. This is OK since we still do not know which papers we want to keep so no need to spend time
adding papers to lists, reference managers, etc. We will determine which papers we want to keep in the
next step. 

### Task
Run the searches for the three steps above. 

## Classify the papers according to their relevance.
Once you have found a list of potentially relevant papers, you need to (roughly) divide them
into the categories below. Reading the title and TLDR/abstract should be enough in most cases
for you to classify a paper.  Sometimes, you will need to dive into the introduction and/or
conclusions sections. If you are reading beyond these sections to do the classification in this
step, take a step back and critically analyze what you have already read. In this step, we are
doing a high-level reading of the papers.

1. Papers that address the same problem using the same solution and (same type of) methodology as your
   research topic. 
    - These papers should definitely be included in your literature review. The reason is
      that the contributions of your own research will need to be explained with respect to the
      contributions of these papers. That is, how is your research advancing knowledge with respect to
      these papers? 

2. Papers that address the same problem with a different solution. 
    - These papers should also be included in your literature review. The reason is that you
    will need to justify why the particular solution in your research topic is worthy of being used or
    investigated. That is, you should have a good answer to the question: why not use the
    solutions in these papers?

3. Papers that address the same problem using the same solution but a different methodology. 
    - These papers should also be included in your literature review. You will also need to justify why
      you are using a different methodology with respect to these papers.  

4. Papers that address a different problem with the same solution. 
    - These papers may or may not need to be included. There are two reasons you may need to include
      papers in this category. First, they can help you justify the use of the particular solution in
      your research topic, i.e., if this solution worked for a different problem, then it is likely to
      also work for your problem. The second reason is that the problem may be very closely related to
      the problem in your research topic and your research will need to explain its own contribution
      according to these papers. If you feel a paper needs to be included because the problem is very
      similar to the one in your research topic, you can choose to move it to the first or second
      category. 

5. Papers that address a different problem with the same methodology.  
    - These papers may or may not be included. There are two main reasons you would include a paper in
      this category. First, it can help you justify the use of the methodology in your own research.
      Second, the paper explains the methodology. This is important to include since
      you most likely will not be proposing your own methodology. If you are, then the research topic
      needs to be revised with the shortcoming of the existing methodology as the problem to be solved. 

6. Papers that are not related to your paper
    - Ignore these papers. 

To keep track of the papers you can build lists within Semantic Scholar or Google Scholar. This will
allow you to then export formatted references. It is never a good idea to format or keep track of the references
manually. 

### Task
1. Write a specific description for each category. For example, category 2 could be: "Papers that
   detect impersonation attacks in low earth orbit satellites without using physical layer authentication" 
2. Create a list of papers for each category using the search engine. 
3. Write a 1-2 sentence note that justifies why the paper is included in the list. The note should
   include the paper's main contribution (what is new in this paper with respect to earlier
   publications?) as well as the paper's problem, solution, and/or methodology.

### Note 
1. The number of papers in each category will depend on how many papers you find. For category 1, you
   will want to include all papers. For category 2 and 3, also try to include all papers. If you find
   more than 5 for either one of the categories, discard papers that are older than 5 years. For
   categories 4 and 5, limit each category to 2 papers.

2. One good way to know that you have all relevant papers is if you are confident that someone else
   (e.g., your research supervisor) cannot find additional relevant papers by running a quick keyword
   search and looking at the first page or results.  

## Identify paper categories. 

One of the main criterion that top journals and conferences use to determine if a paper should be published is
the novelty of its contributions. Therefore, every published paper explains how its contributions are
novel with respect to previously published papers. Therefore, from the point of view of a literature
review writer, a logical way to present papers is chronological order, explaining how each paper improves
on the previous one. However, papers will make contributions to different (possibly overlapping) topics.
Therefore, we usually first group the papers according to their contribution's topic and then order them
in chronological order. Note that their contribution can be in the problem, solution, or methodology of
the research topic. The following are possible ways to organize papers according to their
contribution. 

- The problem that the paper address. You can group the papers according to the problem that
  they address. Noting the difference in their assumptions about the problem or simply
  explaining the different problems. 

- Methodological approach. You can also group the papers according to the approach they take to
  solve a specific problem. For example, intrusion detection methods can be divided into machine learning and deep learning. The narrative should note the similarities as well as the advantages of one method over the other. 

Practically, however, the literature review will use a combination of categories. 

For example, papers can be grouped according to the problem they address.  Within the problem
groups, they can be further categorized according to their methodological approach. Each paper
can then be described in chronological order starting with the oldest one noting the improvements. 

### Tasks
1. Group the papers into categories. One paper may appear in more than one category. Some papers may end
   up in their own category. 
2. Write 1-2 sentences describing each category.

## Write the literature review!
By grouping the papers and having brief descriptions, you have already done all the hard work. The last
step is to put it all together. That is transform what you already have into a set of logically ordered
paragraphs.  

### Task 
The literature review should follow these guidelines.

- Roughly speaking, you should have one paragraph for each subgroup. If you do not have
  subgroups, then you should have a paragraph for each group. 

- The beginning of the paragraph should summarize the papers that you discuss in that
  paragraph. This can be directly taken from your group titles. Basically, this sentence should
  answer the question: Why are these papers together?  The last sentence of each paragraph should
  summarize how the papers in the paragraph are similar (or different) from the chosen paper. Why
  is your chosen paper better (or worse) than these papers. 


## Example
We present an example for the paper "Platforms in Everything: Analyzing Ground-Truth Data on
the Anatomy and Economics of Bullet-Proof Hosting". The paper can be found 
[here](https://www.usenix.org/system/files/sec19-noroozian.pdf)

To better understand the example, first read the Related Works section of the paper.  Then,
read the annotated related works section document attached to this repo. The comments in
the annotated document walk you through the information in the related works' section used to
form the groups below.  

    Group 1: Underground Ecosystems: 

        Group 1.1 includes references: 29, 14, 34, 31, 32, 33 (in your case you can either use your own numbering)

        Group 1.1: Description: Several ecosystems and market places of a malicious nature have been studied in the literature via captured datasets. 

        Group 1.2 includes references: 15, 35, 16, 

        Group 1.2.: Description: Datasets on the underground can also be leaked by criminal competitors

    Group 2:  Bullet Proof hosting

        Group 2 includes references 9, 36, 11, 37, 38, 39, 5

        Group 2 description: Earlier efforts on detecting BPH have relied heavily on identifying autonomous systems.

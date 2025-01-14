Project guidelines
==================

A big part of this course is for you to do a project. 
This is your opportunity to take what you learned in IMSE 440 for a spin and try to work on a real-world problem. 

Team forming
------------

* At the beginning of the semester, you will fill out a course survey in which you are asked to indicate your project topic interests (e.g., transportation, healthcare.)
* You will then be assigned to a multi-disciplinary team of three with similar project topic interests (when possible). 

General requirements
--------------------

- For the project you should use Python and JupyterLab (the same tools that we use in the class).
- You are free to include data analysis, visualization, and modeling methods that we do not cover in the class However, they should only serve as supplementary components of your project.
- You need to submit the PDF files generated from Overleaf (see below) to the Canvas assignments.

Important dates
---------------

- **March 8 (Wed) at 6:11 PM**: Project proposal (team)
- **April 5 (Wed) at 6:11 PM**: Project poster (team)
- **April 18 (Tue) at 6:11 PM**: Final poster (team), Jupyter notebook and data (team)
- **Date TBA**: Project poster presentation (team)
- **Date TBA**: Project peer review form (individual)

Project proposal 
----------------

Your team will decide on our own project topic and find the data that you wish to use.
Your team will submit a project proposal (10% of project grade), so we can make sure your selected topic and data set(s) are suitable for the project and you are on the right track.

Your project needs to be

- authentic (i.e., it comes from a *real-world* problem.)
- meaningful (i.e., the outcomes would provide values to others or are something you care deeply about.)
- reasonably complex (so that you can try a variety of things you learned from this course with reasonable depth.) As a rule of thumb, your project should be significantly more complex than a typical homework problem.
- feasible given the project timeline. 


Proposal requirements
^^^^^^^^^^^^^^^^^^^^^

- **Proposal template**: You should use the proposal template on Overleaf which will be provided.

    - `Overleaf <https://overleaf.com/>`__ is an online collaborative `LaTeX <https://en.wikipedia.org/wiki/LaTeX>`__ editor for scientific writing. 
    - If you do not already have an Overleaf account, you will need to register for one. The *free* plan is good enough. When register, use your UMICH email. 
    - You will need to learn some basic LaTeX using online resources. You are encourage to teach each other. Below are two good starting points:

        - `The Overleaf LaTex Tutorials <https://www.overleaf.com/learn/latex/Tutorials>`__
        - `How to write a thesis using LaTeX full tutorial (YouTube video) <https://www.youtube.com/watch?v=zqQM66uAig0>`__

    .. tip::
        - You just need a few basic things to get started. Learn more as you go. 
        - **Recompile** often in Overleaf, so that if an error occurs, it's easier to track it down. 

    .. note::
        We expect *all* team members to use Overleaf as a collaberative tool (think of a Google Docs) when drafting the proposal (and the poster in the next section).

- The proposal should be no more than two pages (not including the cover page or the references). It should include the following

    - **Project tentative title**
    - **Background**: A brief description of the background of the problem
    - **Research questions**: What do you want to figure out?
    - **Literature review**: What has been done by others regarding the research questions? 
      Report on at least two relevant scientific articles.
    - **Data set(s)**: Briefly describe the data set(s) you plan to use. 
      Include the URLs to access the data. 
      Typically a single data set is sufficient for this project. 
      It is recommended to use publicly-available data. 
      See the Data Sources section below (near the bottom of this document) for starting places to look for data. 
    - **Method description**: what are the technical plans on how the research questions will be answered 
      (e.g., how you plan to analyze the data? what modeling work to conduct? how to address the research questions based on the results?) 
      Note I understand that we have not covered some of the modeling methods. 
      See the [scheduled course topics](../) for more information. 
      Describe your methods as best as you can.   
    - (Optional) A brief description of what you have done so far.

- One submission per team.

.. attention::
    Regression models are mostly suited for `cross-sectional data <https://en.wikipedia.org/wiki/Cross-sectional_data>`__
    (Think of the data sets we used in the lectures and homework.)
    Do *not* use `time-series data <https://en.wikipedia.org/wiki/Time_series>`__ (e.g., temperature by dates), as the independence assumption in regression models is likely violated.
    .. For example, today's temperature is highly correlated with (thus not independent to) yesterday's temperature.

Proposal grading rubric
^^^^^^^^^^^^^^^^^^^^^^^

Your proposal will be graded based on each of the following components. 
Under each component are the descriptions for three levels of "Excellent", "Good", and "Poor".

- **Background & data description**
    - **Background and data clearly described**
    - Background and data described but lacking clarity
    - Background and data not described
- **Research questions**
    - **Defined clear and meaningful research questions**
    - Research questions are present but not articulated clearly
    - Did not define any research questions
- **Literature review**
    - **Identified 2+ relevant scientific work and extensive discussion of at least two**
    - Identified and discussed at least two relevant scientific works
    - Did not look into the literature
- **Methods description**
    - **Clear plan on how analysis and modeling would be used to answer research questions**
    - Plan on how to answer question described but lacking clarity
    - No discussion of how analysis and modeling may be used to answer research questions
- **Composition**
    - **The proposal was clearly written, coherent, and well organized.**
    - Writing and organization needs improvement
    - Not clear, coherent, or lacks overall organization.


Research poster
---------------

Your team will submit a research poster at the end of the project.
There will be two rounds of submission: Round 1 (20% of project grade), final poster (30% of project grade)

Poster requirements
^^^^^^^^^^^^^^^^^^^

- **Poster template**: You should use the poster template on Overleaf which will be provided.
- See the template for all the required sections. 
- One submission per team.
- Your poster should be different from your JupyterLab in some major ways:

    - The audience of the poster is someone who have general knowledge about statistics, but may not necessarily be familair with either Python or the data sets you are using.
    - Thus, your poster should not include any codes (leave them in the notebook). Rather, describe things in plain English.
    - You should also avoid using programing jargons (e.g., function names such as ``groupby``), or anything specific to the data set (e.g., variable names such as "co2_level_mi").

Poster grading rubric
^^^^^^^^^^^^^^^^^^^^^

Your poster will be graded based on each of the following components. 
Under each component are the descriptions for three levels of "Excellent", "Good", and "Poor".

- **Subject knowledge**
    - **The poster demonstrated excellent knowledge of the course content and skills by integrating major and minor concepts and methods into the work;
      It also demonstrated evidence of extensive research effort and a depth of thinking about the topic.**
    - The poster demonstrated good knowledge of the course content and skills by integrating major concepts and methods into the work;
      It also demonstrated evidence of limited research effort and/or initial of thinking about the topic.
    - The poster did not demonstrate sufficient knowledge of the course content, skills, evidence of the research effort or depth of thinking about the topic;
- **Correctness**
    - **The methods and discussions (e.g., data analysis, modeling, interpretations of results) were correct and appropriate to answer the research questions.**
    - The methods and discussions were mostly correct with some minor errors.
    - The methods or discussions have major errors.
- **Composition**
    - **The poster was clearly written and well organized;
      The contents are easy to follow and the viewer can easily understand order without narration;
      Sentences were grammatical and free from errors.**
    - The poster was organized and clearly written for the most part;
      Content arrangement is somewhat confusing and does not adequately assist the viewer in understanding order without narration.
      Sentences were mostly grammatical and/or only a few spelling errors were present but they did not hinder the viewer.
    - The poster lacked overall organization;
      Content arrangement is confusing and the viewer has to make considerable effort to understand the order without narration.
      Grammatical and spelling errors made it difficult for the viwer to interpret the text in places.
- **Visual presentation**
    - **Overall visually appealing; not cluttered; 
      Colors and patterns enhance readability; 
      Uses font sizes/variations which facilitate the organization, presentation, and readability of the research;
      Graphics (e.g., tables, figures, etc.) are easy to read and enhance the text.**
    - Visual appeal is adequate; somewhat cluttered; colors and patterns detract from readability;
      Use of font sizes/variations to facilitate the organization, presentation, and readability of the research is somewhat inconsistent/distractions;
      Graphics (e.g., tables, figures, etc.) are somewhat difficult to read or do not adequately enhance the text.
    - Not very visually appealing; 
      Cluttered; 
      Colors and patterns hinder readability;
      Use of font sizes/variations to facilitate the organization, presentation, and readability of the research is inconsistent/distracting;
      Graphics (e.g., tables, figures, etc.) are difficult to read or do not enhance the text.
- **Contribution**
    - **The project offered some new or interesting insights to the topic under discussion;
      Study limitations were discussed in detail.**
    - The methods and discussion were mostly correct with some minor errors;
      Study limitations were briefly discussed.
    - The project offered no insights to the topic under discussion;
      No study limitations were discussed.

Poster checklist
^^^^^^^^^^^^^^^^

Use this checklist to help you to avoid common mistakes when preparing for your poster. 
Note it is not a complete list. 

- **Are the texts in the figures or tables too small to read?** All text should be reasonably legible. 
- **Are the figure axis clearly labled and with units?**
- **Does the poster include dataset specific names (e.g., "co2_level_mi") or domain/programming-specific jargons?** 
  They should be avoided as general audiance may not know what they mean.
- **Does the poster comply with the Honor Code, including avoiding plagiarism?** Have you cited all the work (e.g., text, images) in the poster that were not created by you? 
- **Are all the numbers have clear units?** This is important for the viewer to be able to understand the results. E.g., The RMSE from the model is $123.4 US Dollars. 
- **Are there in-depth discussions on the study limitations?** They should be included.
- **Are the citations correctly used?**. Check the template for an example.

Jupyter notebook & data
-----------------------

Your team will submit all the jupyter notebook(s) and data used for the project (30% of project grade). 

Notebook/data requirements
^^^^^^^^^^^^^^^^^^^^^^^^^^

- You will submit a single ZIP file. 
  When I extract the file, the result should be a directory containing your Jupyter notebook(s) and all other files (e.g., data). 
  The bottom line is I should have all the files needed to reproduce all your results by running your code on my machine.
- Similar to the homework, before submission, make sure that *Kernel* --> *Restart and Run All* runs without errors.
- If your data files are large, it may take time to upload them to Canvas. 
  It is advised to submit the ZIP file at least one hours before the deadline, so you have some buffer time.
- If your data files are larger than 1 GB, contact the instructor at least two academic calendar day before the deadline to arrange alternative ways to submit the data.

Notebook grading rubric
^^^^^^^^^^^^^^^^^^^^^^^

- **Correctness**
    - **The implementations of the methods in the codes were correct and appropriate.**
    - The codes were mostly correct with some minor errors.
    - The codes contain major errors or were mostly not appropriate.
- **Research reproducibility**
    - **Complete code, data, and other necessary files were provided so that the instructors are able to reproduce all your work. 
      The codes in the Jupyter notebook were well organized and easy to read. 
      An abundance of clear and informative Markdown cells as well as code comments were used to enhance the notebook's readability**
      (see `Markdown for Jupyter notebooks cheatsheet <https://medium.com/ibm-data-science-experience/markdown-for-jupyter-notebooks-cheatsheet-386c05aeebed>`__).
    - Complete code, data, and other necessary files were provided to reproduce all your work. 
      The codes in the Jupyter notebook were somewhat easy to read. 
      A few Markdown cells and code comments were used with mostly clear information.
    - The submission did not include all files needed to reproduce your work.
      The codes in the Jupyter notebook were difficult to read or lack organization. 
      Almost no Markdown cells or code comments were used to enhance the notebook's readability. 


Project poster presentation
---------------------------

Your team will present your research poster at the project showcase event (10% of the project grade).
The showcase will be an in-person event on campus. The date and venue are to be announced. 

Presentation grading rubric
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Your poster presentation will be graded based on each of the following components. 
Under each component are the descriptions for three levels of "Excellent", "Good", and "Poor".

- **Knowledge**
    - **The presenters demonstrated sufficient knowledge of the material.**
    - The presenters demonstrated sufficient knowledge of most of the material but struggled with some.
    - The presenters struggled with most of the material.
- **Presentation**
    - **The presenters spoke well and established rapport with the audience.**
    - The presenters spoke well only some of the time. Established limited rapport with the audience.
    - The presenters did not speak well most of the time and established little rapport with the audience.
- **Questions and answers**
    - **Narration and answering of questions are engaging, thorough, and adds greatly to the presentation.**
    - Narration and/or answering of questions is somewhat lacking.
    - Narration and/or answering of questions is lacking.

Peer evaluation form
--------------------

A peer evaluation form will be provided for you to evaluate your peer team members with structured questions (0% of project grade). 
Your response will not be shared with other students. 

*For each person in your team (other than yourself), indicate the extent to which you agree with each of the statements below, using a scale of 1-5 (1=strongly disagree; 2=disagree; 3=neutral; 4=agree; 5=strongly agree).*

- Attended group meetings regularly and contributed meaningfully to group discussions. 				
- Completed group tasks on time and in a quality manner.				
- Demonstrated a cooperative and supportive attitude.				
- Overall, this member contributed significantly to the project.				

Project policies
----------------

Project Honor Code
^^^^^^^^^^^^^^^^^^

Before working on your project, make sure to understand the :ref:`Honor Code policies` in the Syllabys on what you are and are not allowed to do. 


Lateness policies
^^^^^^^^^^^^^^^^^

- For *all* project submissions a late submission (within 24 hours) will receive an automatic 30% point deduction.
- Late submission for more than 24 hours will receive 0 points.
- The late penalties will by default apply to all team members and, in rare cases, may be adjusted at the instructor's discretion.

Data sources
------------

You can use any data sets of your interest. 
Below are some good starting places to look for data.

- https://datasetsearch.research.google.com
- https://www.data.gov
- https://data.detroitmi.gov
- https://archive.ics.uci.edu/ml/index.php
- http://www.kaggle.com
- Google search "open data portal" + some keywords of your interest. 
  `Click here <https://www.google.com/search?q=%22open+data+portal%22+bicycle>`__ for an example.

Practical advice
----------------

- If you are thinking about including this project to your résumé, keep this in mind from the start (e.g., when selecting the topic and data sets, preparing for the video). 
  We recommend writing down a list of things that you would like to achieve at the end of the project, and working towards them intentionally while doing the project.
- Start early!
- Document as you go the things that you think you would want to include in the deliverables.
- Keep versions of things around: your Jupyter Notebook
    - Explains how you got there
    - In case you have to "go backwards"
    - In case you accidentally delete tons of work
- *Move fast and break things.* 
  `Don't be afraid to make mistakes <https://twitter.com/ThePracticalDev/status/720257210161311744>`__
- *Stay focused and keep shipping.* Build a little, test a little.
- *Done is better than perfect.*

FAQ
---

- Can we change the project topic or data sets after the proposal?
    - Yes. However, please contact the instructors for a discussion before doing so. 


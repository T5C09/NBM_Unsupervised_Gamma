# Natural Language Processing and Unsupervised Learning Project Introduction

## Summary:

Using data with **primarily textual information**, build **unsupervised learning models** that address a useful structure finding, topic modeling, and/or recommendation system problem in any domain of interest such as social media/online discussion, news media, product reviews, literature, or television writing. Communicate your process and findings in a 5 minute presentation (to the entire class at the end of week 2) and a short written description. 

Metis projects are broken down into 5 component parts -- **design**, **data**, **algorithms**, **tools**, and **communication** -- that correspond to the grading rubric and [project success guide](./project_success_guide.md). Below is a description of each component as it relates to this project. For more detail on how these components are graded and how extra points are rewarded, refer to the success guide.  

### Design:

*  The project should be centered around a **well-posed unsupervised learning problem** in a domain of interest that can be reasonably addressed by available text-based data
*  All **deliverable deadlines should be met**, reflecting **professionalism** and **effective scoping and workflow**

### Data:

*  The **primary data must consist of written text documents**, from any data source of interest. Acquisition options include straightforward downloads, web scraping, use of APIs, [BigQuery public data](https://cloud.google.com/bigquery/public-data) etc.
*  Supplemental data (e.g. supporting numerical information like year of publication used to add layers of analysis) is always welcome, but not required
*  Aim to have at least **1000 distinct documents of roughly 100+ words**. Exceptions to this guideline may be appropriate, especially in cases of fewer, longer documents like books (that can also often be appropriately subdivided into more documents) or high quantity but shorter documents like individual tweets. If in doubt, consult with an instructor to ensure that your data supports sufficient depth in modeling 
*  Examples of usable data sources include newspaper articles, reddit, craigslist, twitter, github, and stackexchange posts (see **example projects** below for more) 
 
### Algorithms

*  Building an **unsupervised learning model** including dimensionality reduction/topic modeling and/or clustering in python is required. These methods may be integrated into a complete recommendation system. Methods should be carefully selected via a combination of use case analysis and empirical feedback (e.g. quality of topics produced) 
*  Unsupervised modeling methods beyond those covered in the course are optional 
*  Supervised modeling methods (not covered in the course) are also optional, and should not replace unsupervised methods as the primary focus of the project (consult with an instructor if in doubt)

### Tools

* **Python text processing libraries/tools** (such as NLTK, spaCy, gensim, 
scikit-learn) are required for data handling. 
- Other tools not covered in the course are optional but welcome
  - *Acquisition* tools could include web scraping libraries or use of APIs
  - *Storage* tools could include SQL or noSQL (e.g. MongoDB) databases
  - *Processing* tools could include Google Cloud or Amazon Web Services for cloud computing resources
  - *Visualization* tools could include python libraries such as Bokeh and Plotly or resources outside of python such as Tableau
  - *Production* tools could include Flask or other web app libraries/technologies

### Communication:
 
* Students will deliver a **5 minute slide presentation** at the end of the course. These should be given in a compelling, clear manner and include effective visuals for communicating your objectives and findings
* You will also submit a **~1 page written description** summarizing your work: it should begin with a **~100 word abstract** to be followed by a breakdown of your project along the 5 major components


## Deliverables:

**Please submit all project deliverables through the [Student Submissions Form](https://docs.google.com/forms/d/e/1FAIpQLSeM7MPx5r_FaX6ordJGkG1ObLh94GEE8qzlvEFxfvmWsKmXNA/viewform)**. All project deliverables and code should be uploaded to a personal, project-specific GitHub repository. Click [here](https://github.com/thisismetis/Metis_Fundamentals/tree/main/git_and_github) for instructions on how to set up a personal repo. 

**For exact deliverable dates, refer to the main schedule [here](/README.md).**
  
**For exact deliverable details, refer to the (linked) Metis Fundamentals project deliverable templates**.

 * [Project proposal](https://github.com/thisismetis/NBM_Metis_Fundamentals/tree/master/project_deliverable_templates/project_proposal.md): short description shared with instructors
    - Additionally, students may meet with an instructor for a scope meeting
 * [Minimum Viable Product (MVP)](https://github.com/thisismetis/NBM_Metis_Fundamentals/tree/master/project_deliverable_templates/mvp.md) submission  
 * [Written description, presentation slides PDF, and project code](https://github.com/thisismetis/NBM_Metis_Fundamentals/tree/master/project_deliverable_templates/final_deliverable.md) 
 * Project presentation


## Example Projects
- [Content Based Twitter Recommendation Engine](https://github.com/igabr/Metis_Projects_Chicago_2017/tree/master/04-Project-Fletcher)
- [Predict a company’s operational status using NLP](https://ccronin51.github.io/Metis%20-%20Project%20Fletcher.html)
- [Identify DonorsChoose asks by need groups and type of asks per need group](http://jessicafreaner.github.io/Fletcher/)
- [Tweets about Yoga](https://lucdemortier.github.io/projects/4_fletcher)
- [Joke Analysis](https://github.com/kpuryear/Puryear_Metis/tree/master/Project4)
- [Exploring Craigslist Musicians Communities](https://rjh336.github.io/projects/craigslist/)
- [How to simplify your holiday festive meal planning](https://hengrumay.github.io/MenuPlannerHelper/)
- [More than a Million Pro-Repeal Net Neutrality Comments were Likely Faked](https://hackernoon.com/more-than-a-million-pro-repeal-net-neutrality-comments-were-likely-faked-e9f0e3ed36a6)
- [Promoting Positive Climate Change Conversations via Twitter](https://zeromh.github.io/climate_change_conversations/)
- [Made at Metis Showcase](https://www.thisismetis.com/made-at-metis)

# NLP and Unsupervised Learning Course Project Success Guide

Metis projects are graded by point assignments for five component parts, each on a scale of 1 to 5.
A score of 3 on a component indicates that the project requirements for that component have been well met,
while scores below and above 3 respectively indicate that requirements are not met or are significantly exceeded. 
The components are: **design**, **data**, **algorithms**, **tools**, and **communication**. A total score of 15 (average of 3 per component) is required to successfully pass the course.

For specific instructions on this project's requirements, refer to the [project introduction](./project_intro.md). 
Below are guidelines mapping out the typical project factors in each component that lead to a score of 3, as well as those that help contribute to being below or above a 3. 
**Note that these factors are guidelines and are not prescriptive**; instructors will ultimately grade based on their careful judgement in conjunction with these guidelines, 
so it is not a good idea to try to "game" these guidelines. 

If in doubt about expectations or a score received, you may always consult the instructional team.

**Important note on deliverable deadlines**: Refer to the [daily schedule](../../README.md) for all project deliverables and their deadlines, both intermediate (project proposal, MVP) and final (slides, writeup and code). If you submit your final deliverable later than 11 am ET on presentation day, you will receive a 1 point penalty under the Design category. If you don't submit by 3 pm ET on that day, **we will not be able to grade your project and you will not pass the course**. Any exceptional circumstances should be discussed with your instructors and program manager as soon as possible. You should also meet the intermediate deliverable deadlines  -- your ability to keep to deadlines and display professionalism in your project work will be scored under the design category.

### Design:

*  **Satisfactory**: Includes a properly framed, useful unsupervised learning problem addressable with primarily textual data. All deliverable deadlines are met.  

*  **Below**: Project choice is not appropriate for unsupervised learning methods, text data is not adequately incorporated, deliverable deadlines are not met.
*  **Above**: Demonstrates exceptional creativity and proficiency in leveraging unsupervised learning techniques to address a complex, useful question involving textual data. 

### Data:

*  **Satisfactory**: Primary data is text-based and includes 1000+ documents with roughly 100 words each, or 
contains sufficient complexity for interesting modeling challenges (consult with an instructor if in doubt).

*  **Below**: Primary data is not text-based. Data set is small or overly simple. 
*  **Above**: Data is large in scale (~50,000+ documents).
Data has significant formatting/handling complexities
such as requiring specialized language processing or extensive preprocessing overall. 
Multiple datasets (potentially including supplementary numerical data) are leveraged via merging disparate sources.  
 
### Algorithms

Note that students **are not graded based on evaluation metric scores**, overall topic or cluster quality, etc: we are looking for soundness in approach and rigor in exploring the problem you've chosen as thoroughly as possible. Unsupervised problems will vary widely in the challenge they pose, and the "success" of a model is contextualized by this level of challenge, not by absolute metric numbers or results. Sometimes in unsupervised learning, the data structure that is hoped for simply does not exist; disproving a hypothesis can also be a valuable and important project. 

*  **Satisfactory**: An unsupervised learning model is successfully built and tuned using a rigorous selection/evaluation framework (e.g. with proper cluster evaluation techniques or analysis of topic findings). The correct topic modeling, clustering, and/or recommendation technique for the problem is selected and model results are interpreted correctly and applied in a useful manner. 

*  **Below**: No unsupervised learning model is built, or the model built is deficient in approach -- e.g., the model is poorly tuned or an inappropriate fit for the problem being addressed.      
*  **Above**: A carefully curated unsupervised learning model is built: rigorous model selection and hyperparameter tuning beyond the basics of model choices are performed, with the model's end application always clearly in mind. Meticulous attention is paid to model selection methodology, to the point of considering model scalability and complexity/interpretation tradeoffs. Models are used and analyzed with finesse, their results cross-referenced with supplementary categorical or numerical data to build layers of insight. Models beyond the scope of the course are built, their use understood and well-justified by the student.  

### Tools

*  **Satisfactory**: Python text processing libraries are adequately used to handle the text data.

*  **Below**: Text processing libraries are not used, or are used in a trivial manner to process supplemental instead of primary data.
*  **Above**: Advanced text processing libraries (e.g. spaCy, gensim, CorEx) are used to handle significant preprocessing challenges.
Advanced tools not covered in the course are used as a significant component of the project.

- Major examples of applicable tools not covered in the course:
  - *Acquisition* tools could include web scraping libraries or use of APIs
  - *Storage* tools could include SQL or noSQL (e.g. MongoDB) databases
  - *Processing* tools could include Google Cloud or Amazon Web Services for cloud computing resources
  - *Visualization* tools could include python libraries such as Bokeh and Plotly or resources outside of python such as Tableau
  - *Production* tools could include Flask or other web app libraries/technologies

### Communication:
 
*  **Satisfactory**: Presentation is in line with time requirements, clear in structure and delivery, and includes reasonable visualizations. 
Written description is similarly clear and in line with length expectations.

*  **Below**: Presentation is well out of line with time requirements, delivered poorly, confusing, or lacking in visualizations. 
Written description is unclear and poorly structured.
*  **Above**: Presentation has exceptional delivery, extremely clear structure, compelling narrative and selection/construction of visualizations throughout. Slides are beautiful in style and design, carefully curated to draw attention to key information and complement the verbal delivery.  


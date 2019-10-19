Slides from Alex’s talk "Practical reproducibility of analyses"

In the pursuit of robust, reproducible, and extendable analyses, one key aspect frequently gets overlooked: practicality. Reproducible analyses with a potential for good review are often cumbersome to write: they may require branches to be pulled, environments to be built, and variables to be changed in a well-hidden file. I will propose a step towards greater practicality with an example using three technologies many data scientists know to some extent:

- RMarkdown  
- R shiny server  
- Docker  

By presenting this concept I hope to demonstrate that it is possible for:

- data scientists to review the live code with one link to a shiny-rendered page  
- non-data-scientists to rerun and extend the analysis through an intuitive GUI  
- the data scientist doing the task to achieve this only writing one file in their preferred coding language  

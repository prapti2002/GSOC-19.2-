## INCF 19.2  A natural language interface for querying federated research data.
## Contact details

Full name: Prapti Takawale

Email: praptitakawale@gmail.com

Neurostars ID: Prapti.dt

Location : Pune, India

Github : [https://github.com/prapti2002](https://github.com/prapti2002)

## Project details

**The Project**
**What is the project about?**

This project aims to enhance the Neurobagel data ecosystem by creating a chatbot interface using large language models (LLMs). The chatbot will parse natural language queries, initiate API calls, interpret results, and convey information effectively, making the search process more accessible and user-friendly.

**Why is it important?**

This project, centered on developing a natural language interface for querying federated research data within the Neurobagel ecosystem, holds profound significance in several key aspects.

Firstly, by introducing a natural language interface, it aims to simplify the process of querying research data. This approach eliminates the need for users to have prior knowledge of complex query languages or data structures, thereby lowering the barrier to entry for accessing and utilizing research data. Such simplification can democratize access to valuable research resources, making them more readily available to a broader audience of researchers and data users.

Secondly, the project's focus on natural language interaction promotes intuitive communication between users and the Neurobagel ecosystem. By allowing users to express their queries in everyday language, it enhances the user experience, making the process more engaging, efficient, and user-friendly. This aspect not only facilitates quicker data retrieval but also encourages more extensive exploration and utilization of the available research data.

Moreover, the implementation of a natural language interface fosters greater collaboration and contribution within the Neurobagel community. By providing a more accessible and conversational means of interacting with the data ecosystem, the project encourages active engagement from users across diverse domains and expertise levels. This collaborative environment can stimulate knowledge sharing, interdisciplinary research, and the emergence of innovative ideas and insights.

Furthermore, the project aligns with the broader trend of advancing natural language processing (NLP) technologies in research and academia. By leveraging state-of-the-art NLP techniques, it contributes to the ongoing evolution of data querying methodologies, paving the way for more intelligent and intuitive systems for accessing and analyzing research data.

In conclusion, the development of a natural language interface for querying federated research data within the Neurobagel ecosystem represents a significant advancement in enhancing accessibility, usability, and collaboration in research. By simplifying the querying process, promoting intuitive interaction, and fostering community engagement, this project has the potential to revolutionize the way researchers and data users access and utilize research data resources.

  

**Project in detail**

**Specifications**

In this section I will detail my vision for how I will be working on this project. I expect this to be considerably enhanced under the guidance of my mentor.

**How will you handle the Project?**

My approach would be first to understand the basics of langchain and ollama and understand how they make use of LLMs. From my understanding as of now from the readings, I am aware of LLMs and have ideas about basic RAG applications using OpenAI API’s and langchain.

In a nutshell the architecture will be the LLM receives the Natural Language query, which it parses for getting relevant fields and generates a query which runs on the database and we get the desired data back. The results will be given to LLM to generate and convey the desired results back to the user.

  

**Detailed Description**

I plan to build this project in three stages.

  

**Stage 1**

I plan to go through the ways we can achieve the parsing using LLM and query generation to communicate with databases. I see some possible approaches are prompt, fine tuning but will be going through them in depth and testing them on the data, would give a better understanding and to make necessary changes to adapt it to the use case.

![](https://lh7-us.googleusercontent.com/tmaAIFo4jk-RnZGJCyDjDjr8bOc4nlHlgbhmKb7-FUnoHUqCel39D6Tm6kcAKCimf2vDRtqElYl21UMk2yA2XXeD8BkWt55NyJ1pYoVho2zbf8JYt3QFvQXstQWHfyo6QIR-XZyMMkgJN3Pn9Js2UuM)

  

**Stage 2**

After achieving the parsing and the query generation, I would integrate these results and this will be able to fetch the desired data. After fetching this data, I would try to incorporate it in the LLM(same or different) to generate the desired results in a concise and clear way for the user to understand.

![](https://lh7-us.googleusercontent.com/WfkevlcsliVQ6QGbSDOiZa5V7rKSie3FmsIfyDL0_ce-Ld5M7fPiEkkuNPJh1109o-4ZHFsFUyVfTm4JTD5efSKiL7fqcpxgg3kZjS5ivsLj_7J6mxWma4j3WRUcdtPpMBa49FnrycQ1AIOgX4pTfW4)

  
  

**Stage 3**

After I have built this pipeline, I would move on to ways to improve it with some ideas from mentors and research.

  **Minimal Set of Deliverables:**

1.  Integration of LLM-driven chatbot-style interface into the Neurobagel cohort query workflow.
    
2.  Development of core logic for parsing user-provided text into accurate queries and summarizing results.
    
3.  Testing and debugging to ensure the reliability and accuracy of the chatbot.
    
4.  Documentation of the development process, including design decisions and implementation details.
    
5.  Creation of user documentation and guidelines for utilizing the chatbot interface.
    

**If Time Allows:**

1.  Optimization of performance and efficiency of the chatbot.
    
2.  Further refinement of the chatbot based on user feedback and testing results.
    
3.  Implementation of additional features for enhanced user experience, such as improved natural language understanding and response generation.
    
4.  Exploration of potential extensions or integrations with other tools or platforms for broader usability.
    

**Detailed Timeline:**

**Week 1-2 (May 1 - May 26): Familiarization and Setup**
    

-   Acquainted with Neurobagel’s codebase, including the API and cohort query tool.
    
-   Explore existing functionalities and workflows.
    
-   Research LLM libraries and their applications.
    

  **Week 3-4 (May 27 - May 31): Research and Exploration**
    

-   Investigate LLM applications in natural language processing and query generation.
    
-   Analyze requirements for LLM-driven chatbot interface.
    
-   Review relevant literature and works in the field.
    

  **Week 5-6 (June 01 - June 03): Design and Planning**
    

-   Develop a strategy for integrating LLM-driven chatbot into the Neurobagel cohort query workflow.
    
-   Design core logic and tools for parsing user-provided text and summarizing query results.
    
-   Plan the implementation process, including timeline and milestones.
    

   **Week 7-8 (June 04 - June 17): Implementation and Testing**
    

-   Implement the LLM-driven chatbot interface.
    
-   Conduct preliminary testing and debugging to ensure functionality and accuracy.
    

  **Week 9-10 (June 18 - July 01): Refinement and Optimization**
    

-   Refine the chatbot based on feedback from initial testing.
    
-   Optimize performance and efficiency of the chatbot.
    

  **Week 11-12 (July 02 - July 08): Finalization and Documentation**
    

-   Finalize implementation of the chatbot.
    
-   Document the development process, including design decisions and implementation details.
    
-   Prepare user documentation and guidelines for utilizing the chatbot interface.
    
**Your plan for communication with mentors:**

I propose to maintain regular communication with my mentor through weekly email updates and scheduled GMeets. These channels will facilitate ongoing discussions about project progress, addressing any issues promptly. Additionally, the frequency of GMeet calls may increase as needed to ensure alignment and timely resolution of challenges.

**You can apply for up to three projects. Is this the only project that you will apply for?**  

No, this is Not the only project I am applying for.

**Working time - how many hours per week do you plan to work, and how will you divide your time?**  

40 hours / week rounding to about 6 to 8 hours on a daily basis.

**Do you have any other plans for the work period (school work, another job, planned vacation)? If so, how do you plan to combine them with your work?**  

My 12-week summer vacation begins from 10th May. I don’t have any major commitments in the GSoC Period, thus, this project will be my top priority. My next semester starts around the last week of August. The academic pressure isn’t heavy in this time-frame, Thus, I would be able to devote my time in the last few weeks of the coding period as well.

**References**

https://aws.amazon.com/blogs/machine-learning/generating-value-from-enterprise-data-best-practices-for-text2sql-and-generative-ai/

https://arxiv.org/abs/2403.08291

https://techcommunity.microsoft.com/t5/fasttrack-for-azure/grounding-llms/ba-p/3843857

https://dspace.mit.edu/bitstream/handle/1721.1/119708/1078222310-MIT.pdf?fterence=1

https://aclanthology.org/2022.findings-naacl.13/

https://ceur-ws.org/Vol-1597/PROFILES2016_paper6.pdf




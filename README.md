# Learn AI: Designing and Architecting Intelligent Agents + Cognitive Search

Welcome to this 2-day bootcamp focused on designing and architecting intelligent agents (chatbots), as well as Cognitive Search. In these two days, we will focus on discussion-based activities that develop proficiency for designing, architecting, and implementing AI-oriented solutions using services such as Azure Bot Services, Azure Search (and the new additions to create Cognitive Search), and Cognitive Services. These labs assume an introductory to intermediate knowledge of various services, and if this is not the case, then you should spend the time working through the prerequisites (below).


# Abstract
This highly interactive 2-day course covers how to deal with complexities during bot design, specifically with regards to capabilities, natural language understanding (NLU), architectures, and intelligence. You will participate in deep dive discussions and cases around the principles of good bot design and LUIS schema design. You will also become familiar with the recommended reference architectures and customer case studies from the Product Group, and you'll learn when and how to use and integrate various services (e.g. Cognitive Services and Azure Search) to make bots smarter. From there, we’ll get into Cognitive Search (went private preview at //build in May 2018), which is a new enrichment pipeline within Azure Search. You’ll learn the motivation and use cases for Cognitive Search, and then you’ll dive into several hands-on labs. By the end of the course, as proven by the final case, you should be able to design and architect intelligent agents and implement Cognitive Search.  

# Prerequisites
Before arriving at the bootcamp, you should meet the following prerequisites:
* For the intelligent agent pieces, if you don’t have the following skills prior to the bootcamp, we recommend completing the original [Learn-AI Bootcamp for Emerging AI Developers](https://github.com/Azure/LearnAI-Bootcamp/blob/master/emergingaidev_bootcamp.md):
    * Experience and expertise architecting solutions or building applications on Azure and with Microsoft's AI Stack
    * Experience with Microsoft LUIS
    * Familiarity with Azure Bot Services/Microsoft Bot Framework
    * Understanding of the various Cognitive Services and Capabilities
* For the Cognitive Search pieces, be sure you satisfy the following:
    * We will use Visual Studio for some activities. Read [this link](https://docs.microsoft.com/en-us/visualstudio/ide/visual-studio-ide) to gain the knowledge you need to do this workshop.
    * We will create small C# applications. If you haven't worked with C#, we recommend watching these [short videos](https://mva.microsoft.com/en-us/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949) from Microsoft Virtual Academy.
    * You need a Microsoft Azure account to create the services we use in our solution. You can create a [free account](https://azure.microsoft.com/en-us/free/), use your [MSDN account](https://azure.microsoft.com/en-us/pricing/member-offers/credit-for-visual-studio-subscribers/), or use any other subscription where you have permission to create services.
    * Install [Visual Studio 2017 version 15.5](https://www.visualstudio.com/vs/) or later, including the Azure development workload.
    * You need a computer with [Postman](https://www.getpostman.com/) or [Fiddler](https://www.telerik.com/download/fiddler) installed to test the APIs we will interact with, so come to the training with one installed. We will use this software to make REST calls to Azure Search and complete many of the labs. If these tools are new to you, you need to carefully read how to [explore Azure Search REST APIs using Fiddler or Postman](https://docs.microsoft.com/en-us/azure/search/search-fiddler) before the course. If you're new to Postman/Fiddler, we recommend using Postman, as many of the screenshots and instructions are geared specifically for Postman. That being said, if Fiddler is your tool of choice or you are more comfortable with it, you shouldn't have any problems completing the lab.
    * You should have some understanding and, preferably, some experience with Azure Functions and Azure Search. Review the documentation and complete the quickstart trainings before starting this training: [Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/) and [Azure Search](https://docs.microsoft.com/en-us/azure/search/).

# Agenda
Please note: This is a tentative and flexible agenda, and the schedule is subject to change pending class activities and interactions.

Day 1
* 8-9: Arrive/Sign in
* 9-9:15: 1: Introduction to the course
* 9:15-10: [2.1: Bot Design Principles](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/02-bot_design/readme.md)
* 10-10:45: [2.2: Activity - Bot Design](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/02-bot_design/2_activity.md)
* 10:45-11: Break
* 11-11:45: [3.1: LUIS Design Principles](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/03-luis/readme.md)
* 11:45-12:30: [3.2: Activity - LUIS Design](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/03-luis/2_activity.md)
* 12:30-1:30: Lunch
* 1:30-2:15: [4.1: Reference Architectures and Common Patterns](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/04-architectures/readme.md)
* 2:15-3: [4.2: Activity - Architectures](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/04-architectures/2_activity.md)
* 3-3:15: Break
* 3:15-4: [5.1: Making Bots Smarter (Cognitive Services and more)](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/05-cognitive_services/readme.md)
* 4-4:45: [5.2: Activity - Making Bots Smarter](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents/blob/master/05-cognitive_services/2_activity.md)

 
Day 2
* 8-9: Arrive/Sign in 
* 9-9:15: Recap and overview for the day
* 9:15-10: [Introduction to Azure Search](https://github.com/Azure/LearnAI-Bootcamp/blob/master/lab02.1-azure_search/1_AzureSearch.md)
* 10-10:30: [6.1: Cognitive Search: Motivation, context and key concepts](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/01-Introduction.md)
* 10:30-10:45: Break
* 10:45-11:15: [6.2: Solution Architecture](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/02-Solution-Architecture.md)
* 11:15-11:30: [6.3: Environment Creation](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/03-Environment-Creation.md)
* 11:30-12:30: [6.4 Cognitive Search Lab 1: Text Skills](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/04-Lab-1-Text-Skills.md)
* 12:30-1:30: Lunch
* 1:30-2:30: [6.5 Cognitive Search Lab 2: Image Skills](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/05-Lab-2-Image-Skills.md) (and [6.6 Lab 3: Custom Skills](https://github.com/Azure/LearnAI-Cognitive-Search/blob/master/06-Lab-3-Custom-Skills.md) if you finish early)
* 2:30-2:45: Break
* 2:45-3:45: [Final Case](./final_case.md)
* 3:45-4: Break
* 4-4:30: Presentations, Discussion, Feedback
* 4:30-5: Q&A and Course Feedback

# Additional Resources  
This bootcamp is a selective combination of two courses. You can access the required materials for this course by following the links above. You can access the full courses at the following locations: 
 * [Designing and Architecting Intelligent Agents](https://github.com/Azure/LearnAI-DesigningandArchitectingIntelligentAgents)
 * [Building an Enterprise Cognitive Search Solution](https://github.com/Azure/LearnAI-Cognitive-Search/)  

You can also check out [all the courses available from the LearnAI team](https://azure.github.io/learnAnalytics-public/).


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

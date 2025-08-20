# SoftwareTesting-Automation-Quality-Assurance

This repository contains my coding assignments, projects, and written work for the software testing, automation, and quality assurance course at Southern New Hampshire University.

# How can I ensure that my code, program, or software is functional and secure?

To ensure my code is functional, I start by carefully following all technical requirements and breaking the problem down into smaller, manageable tasks. I write classes and methods that perform a single function to keep the code simple, straightforward, and easy to test. In-line comments explain the logic behind each technique, and I include header descriptions for each class to enhance readability and maintainability. I apply static testing techniques to evaluate future functionality and anticipate potential issues before they arise.

Throughout development, I rely on JUnit5, a robust testing framework, to create unit test cases that validate the behavior of each method, ensuring accuracy and consistency. Security is a critical part of the development process. I avoid unnecessary data exposure and design my methods with secure input handling in mind, reducing risks such as injection attacks or invalid data errors. Whenever I discover bugs or inconsistencies during testing, I revise the corresponding classes or test cases and retest to confirm the fixes. I document all results and revisions, which not only supports future improvements but also helps track progress over time. This structured and iterative approach ensures that the final product is both functional and secure, meeting the project's objectives and user expectations.

# How do I interpret user needs and incorporate them into a program?

I start by analyzing user requirements and translating them into technical tasks that can be implemented through code. This involves identifying the functionalities that users expect from the program and respecting any constraints. For example, in the contact service project, users needed to add, update, or delete contact information. I implemented these features while ensuring data integrity, which means maintaining and assuring the accuracy and consistency of data over its entire life cycle. 

I also design my methods to be specific and focused, with each one directly supporting a user need or functional requirement. Using in-line documentation helps clarify the logic behind each decision and trace it back to the original requirements.

Additionally, I write JUnit5 test cases to validate whether the implemented features perform correctly in various scenarios based on realistic user interactions. If the results do not align with expectations, I revise either the code or the tests as necessary. Documenting these revisions enables me to track the software's evolution to meet better user needs, a testament to the progress and evolution in software development that keeps me engaged and motivated. 

This process ensures that the final product reflects both the explicit requirements and the real-world context in which the software will be used. My focus is always on maintaining a strong connection between what users expect and how the program actually performs, a responsibility I take seriously and a commitment I uphold in every project.

# How do I approach designing software?

My approach to software design begins with breaking down the overall project requirements into small, single-purpose methods and classes. I follow a modular design structure, ensuring that each class is responsible for a specific aspect of the functionality. For example, in the contact service project, I created separate classes for the contact model and the service logic, which makes the program easier to manage and update. I also include descriptions at the top of each class and in-line comments throughout the code to clarify the intent and behavior of each section. This clear documentation supports both current development and future revisions.

Testing is integrated into my design process. I start with static testing to identify potential issues and ensure my logic is sound before running the program. After that, I write JUnit5 unit tests to validate each function. Whenever I encounter an issue, I revise the relevant code and retest it, documenting the results and decisions made. This continuous feedback loop between design, testing, and revision ensures that the final software is reliable, easy to understand, and capable of evolving. My design process prioritizes clarity, maintainability, and alignment with both user needs and technical requirements.

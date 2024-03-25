# The Importance of Continuous Integration and Continuous Deployment (CI/CD)

In the IT world, code reviews are very important for improving code quality and encouraging collaboration between developers. Code review is the practice of going back over one's code to try to find bugs or problems in order to improve or correct it. Within a team, the person carrying out the code review is often not the author of the code, to enable him or her to have an external opinion and for the code to be validated by several people. As this article shows, code reviews are essential in companies where teams work together.

![Continuous Integration / Continuous Deployment](image.png)

"[Code reviews play a pivotal role in ensuring the quality, reliability, and maintainability of software projects. By fostering a culture of collaboration, sharing knowledge, and maintaining coding standards, teams can harness the full potential of code reviews to deliver high-quality software products.](https://codeinstitute.net/global/blog/the-importance-of-code-reviews/#:~:text=Code%20reviews%20play%20a%20pivotal,deliver%20high%2Dquality%20software%20products.)"

A study shows that when developers know their code will be reviewed by a teammate, they produce more thorough work and ensure that their code passes all the automatic tests. As this article shows, "[When developers know their code will be reviewed by a teammate, they make an extra effort to ensure that all tests are passing and the code is as well-designed as they can make it so the review will go smoothly.](https://www.atlassian.com/agile/software-development/code-reviews#:~:text=Code%20reviews%20should%20integrate%20with,the%20code%20is%20merged%20upstream.)"

In the software development process, code reviews are very important for producing clean code that is understood by the whole team. To ensure that the process is as clear as possible, the simplest way is to assign the people who will review each person's code in advance when planning the tasks. As soon as a task has been completed, the person responsible for reviewing the code can then get to work, as this article suggests: "[after all the code has been written and automated tests have been run and passed-but before the code is merged upstream.](https://www.atlassian.com/agile/software-development/code-reviews#:~:text=Code%20reviews%20should%20integrate%20with,the%20code%20is%20merged%20upstream.)"

During a code review, the simplest thing to do is to create a code standard within the team beforehand so that the person reviewing the code can easily understand it. If the code is still technical and complicated to understand despite the existence of a code standard, the author can add comments. Firstly, this will speed up the code review, and secondly, if another developer has to work on this part of the code in the future, it will be easier for them to understand it.

During a code review, it is still important to offer constructive criticism of the code. Never offer personal criticism or anything else, as this would damage group cohesion and therefore the team's performance, which is not the desired aim. Feedback must be clear, constructive and specific. This will enable everyone to improve and thus increase the team's overall productivity in developing an application. To back up my comments, we can look at the practices recommended by github: "[In general, it is important to be courteous and respectful while also being very clear and helpful to the developer whose code you are reviewing. One way to do this is to be sure that you are always making comments about the code and never making comments about the developer.](https://google.github.io/eng-practices/review/reviewer/comments.html.)"

---

# Introduction to Continuous Integration/Continuous Deployment (CI/CD)

The principle of CI/CD is to ensure that there is continuous development in order to accelerate the software development life cycle. It also avoids all the deployment headaches of the usual large deployments - all the problems are smaller and simpler to deal with.

[RedHat provides a comprehensive overview of CI/CD.](https://www.redhat.com/fr/topics/devops/what-is-ci-cd)

**Objectives of CI (Continuous Integration):**
- Regularly merge code modifications into a shared repository, such as a Git repository, several times a day.
- An automation process is triggered to compile the code and run automated tests.
- Rapidly detect and correct integration problems, thereby reducing the risks associated with code conflicts and ensuring high code quality.

**Objectives of CD (Continuous Deployment):**
- Automate the process of deploying applications to different environments.
- An automation process is started to build, test and deploy the application in a target environment.
- Reducing the time between development and production release, enabling teams to quickly deliver functionality to end users while maintaining a high level of quality and stability.

Several tools are available for CI/CD, including Jenkins and GitLab CI/CD. Jenkins is a free, open-source tool. It can work for both small and very large teams. The tool allows a great deal of flexibility and customization. The disadvantages are the complexity of setting up the tool and the difficulty of use for beginners. In comparison, GitLab CI/CD is easier to use but a little less customizable; the tool is directly integrated into the Github tool, which can make it easier to use if you already use this tool in your company.

---

# Creation of Continuous Integration/Continuous Deployment (CI/CD) Pipelines:

1. Compiling the code.
2. Test execution.
3. Building artifacts.
4. Deployment to test, pre-production, and production environments.
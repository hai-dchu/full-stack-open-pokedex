# 11.1 Warming up

Questions:
* Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by Google.
* What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask Google!
* Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

Answer:
1. Tools for linting, testing, and building:
* Linting: tools such as ESLint, JSLint, etc are commonly used to analyze code structure, which then will be turned into flags for programming errors, bugs, stylistic errors, etc.
* Testing: jest, supertest and playwright. Each of the aforementioned tools serve a different purpose. Jest is used in frontend testing, supertest for backend testing, and playwright for end to end testing. Together, they make that the app works as the developer wanted to.
* Building: serve is the most common tool for building a production-ready frontend. It turns all the jsx, tsx, Bootstrap, etc into common HTML, CSS and JS files - the only acceptable format when serving web app to users.

2. Alternatives to set up CI besides Jenkins and GitHub Actions:
* Some commonly used alternatives are: GitLab CI/CD, BitBucket Pipelines, Azure DevOps, etc

3. Given that this is a project worked on by 6 developers, it would be beneficial to host the application in a cloud-based environment. Some of the advantages are:
* cloud-based service allows the team to focus on development rather than infrastructure management
* cloud-based systems handle scaling automatically, ensuring pipelines remain performant without additional effort
* cloud-based CI/CD can be set up quickly, supporting the team's release timelines
* etc
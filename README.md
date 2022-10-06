# Hacktoberfest with Showwcase

This repository contains a record of all low-code and no-code contributions made during the Hacktoberfest event in the ReactPlay community.

# What is Hacktoberfest
Hacktoberfest is a virtual event organized by DigitalOcean and its partners throughout October. It is aimed toward open source and introducing it to as many developers as possible. Anyone regardless of their programming experience are encouraged to contribute to open-source.

## No-code/Low-code Contributions

Until last year, hacktoberfest contributions were only valid for coding or maintaining a project. Since this year, Hacktoberfest has also been allowing low-code and no-code contributions.  
Here's the table that explains some of the ways of no-code/low-code contributions.

| Contribution Type | Low-code                                            | No-code                                       |
| ----------------- | --------------------------------------------------- | --------------------------------------------- |
| Writing           | Technical Documentation                             | Translating, Copy editing                     |
| Design            | Testing                                             | UX Testing, Graphics design, video production |
| Advocacy          | Talks, presentations, blogs, podcasts, case studies | social media blog posts                       |

## Hacktoberfest with Showwcase

We are already having active code contributions in our [main project](https://github.com/reactplay/react-play). However, if you have contributed to us in some other way, you need to submit it in this repository.  
The valid contributions will be merged to the repository with `hacktoberfest-accepted` tag.

## What Are Valid Contributions

Anything that you have done that helps the ReactPlay community to grow, and improve in either low-code or no-code categories will be considered as a valid contribution. You need to provide detailed informaton about the contribution along with a URL that validates your contribution.

## How to Submit Your Contribution

1. Go to the [Issues](https://github.com/reactplay/hacktoberfest/issues/new/choose) section of the repository and add a new issue with **New Contribution** template

	
2. Fill in the required details with appropriate information. And then Submit the issue.
3. Wait until someone from the community assigns you to the issue.
4. Fork this repository in your own account once you are assigned to the issue.

  
5. Create a new branch with your github username.

  
6. Inside `/data` directory in the root folder, open the `json` file named with current year (eg: `2022-contributions.md`) .
7. Use your github username as a key and use the following template to add your data.
   
  ```md
  ---
    "name": "<Your name>"
    "username": "<Showwcase username>"
    "github": "<GitHub username>"  
    "category": "<no-code | low-code>"
    "topic": "<Web3 | JavaScript | Python | ReactJS | Machine Learning | DevOps>"
    "contribution": "<article | video | talk | presentation | workshop | case-studies>"
    "description": "<explain what you did within 280 characters>"
    "link": "<url to validate your contribution>"
  ---  
  ```
8. Once you are finished, commmit your changes.

  
9. Go to the `Code` section of the repository. You will see a yellow box asking you to compare & create a pull request, click it.

  
10. If the above step doesn't work, go to `Pull Request` section and createa a new request.
11. Select the `main` branch of `reactplay/hacktoberfest` repository, and solve merge conflicts if any.
12. Wait until someone from our team approves it.

## Example

```md
---
"name": "Tapas Adhikary"
"username": "atapas398"
"github": "atapas"  
"category": "no-code"
"topic": "JavaScript"
"contribution": "article"
"description": "Written an article on JavaScript Promises"
"link": "https://www.showwcase.com/show/16140/javascript-promises-quizzes-and-interview-questions"
---
```

## Get in Touch
If you are stuck somewhere, or have some doubts; join our [Discord server](https://discord.com/channels/982239924227031070/983209230729379901) and mention it there. 




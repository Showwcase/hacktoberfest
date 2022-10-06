# Hacktoberfest with Showwcase

This repository contains a record of all low-code and no-code contributions made during the Hacktoberfest event.

# What is Hacktoberfest
`Hacktoberfest` is a celebration of Open Source. It is a virtual event organized by DigitalOcean and its partners throughout October. It is aimed toward open source and introducing it to as many developers as possible.

## No-code/Low-code Contributions

Until last year, hacktoberfest contributions were only valid for coding or maintaining a project. Since this year, Hacktoberfest has also been allowing `low-code` and `no-code` contributions.

The table below explains the types of no-code/low-code contributions that are accepted:

| Contribution Type | Low-code                                            | No-code                                       |
| ----------------- | --------------------------------------------------- | --------------------------------------------- |
| Writing           | Technical Documentation                             | Translating, Copy editing                     |
| Design            | Testing                                             | UX Testing, Graphics design, video production |
| Advocacy          | Talks, presentations, blogs, podcasts, case studies | social media blog posts                       |

## Hacktoberfest with Showwcase

We at Showwcase encourage every developer to contribute to Open Source through Hacktoberfest. We are excited to participate in the event to encourage open-source enthusiasts to make `no-code` and `low-code` contributions. Showwcase is the platform for developers to learn, share, and grow. One of the prominent avenues for developers to learn and grow is with the `shows` in Showwcase. With shows, you can create blog articles, videos, podcasts, and many other content types that are free to consume.

In this Hactoberfest, you can create any type of show and make a `no-code` and `low-code` contribution to Hactoberfest. Read below to get started.


## How to Contribute?

Follow these steps to start your contributions:

- Sign Up with [Showwcase](https://showwcase.com) and log in to the application.
- Click on the `Create` button at the header of the page and then select the `New Show` option

![image](https://user-images.githubusercontent.com/3633137/194374689-5f165cc1-59ea-4929-839a-9f67284a3c22.png)

- Select a type of show you want to create. You can select a template to start with. For example, if you want to create an article, please select the `New Blog` template.

![image](https://user-images.githubusercontent.com/3633137/194375139-e0757f43-ff5e-4cc5-a190-33551da3d5cd.png)

- Create the content and publish it on the Showwcase platform.


## How to Submit the Contribution

Once you have created the content, it's time you submit the contribution for the Hactoberfest event. Follow these simple steps to get there.

1. Go to the [Issues](https://github.com/Showwcase/hacktoberfest/issues/new/choose) page and add a new issue for the **Hacktoberfest Contribution**

![image](https://user-images.githubusercontent.com/3633137/194370630-72dd971c-e22c-4a02-9804-15e08ce22797.png)

2. Fill in the information. And then Submit the issue. Your issue will be marked with the `hacktoberfest` event automatically.
3. One of us from the community will assign the issue to you.
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




# mock-exam
- This practice assessment is the same format as the final exam.
- It is an open book assessment adhering to the below academic integrity rules.
- Before the exam you will be invited to workspace on q-rap rstudio cloud where you must complete the exam in the allocated time.
- You must then clone your version of the exam (sufixed with your github username)
- This final exam is worth 50%, you will have two hours to answer a total of three questions. You must complete both questions in section 1 and choose one question from section 2.
- It is your responsibility to make sure the RMarkdown can knit to HTML appropriately, before you final commit and push back to github.
- For the mock exam you must have attempted the questions and pushed a new version of the repo to github to recieve the mock exam solutions


# Before you begin

>1. Create an R Project in the q-rap RS workspace called ‘Mockie McMockFace’. Follow this url [invite](https://sso.rstudio.cloud/q-rap?redirect=https%3A%2F%2Frstudio.cloud%2Fspaces%2F231405%2Fjoin%3Faccess_code%3D0ntLcVUJQ_orMd5eha1oL93Fac8RRrAhgBzT3_rQ)
>2. New Project > New Project from Git Repository
>3. Go to [https://github.com/Time-series-financial-econometrics](https://github.com/Time-series-financial-econometrics)
>4. Clone your version of the mock
>5. Make sure packages `ffp2,knitr,tsfe` are loaded by running `(.packages())` in console.


# If you get a git commit error

GitHub credentials are not persisted across projects. For each project that is created from a GitHub repository, you will need to supply your credentials to push and pull from that repository.

When creating a project from GitHub using the “New Project from Git Repository” command, you must supply the HTTPS URL from GitHub. You can then push / pull from within the project using HTTPS authentication, supplying your Personal Access Token (GitHub no longer supports password authentication). When creating a project from GitHub using the “New Project from Git Repository” command, you cannot use SSH Git authentication. Once a project is created, you can configure SSH authentication from within the IDE.

If you have a linked GitHub account, your identity has already been configured for you. If you would like to change the name or email being used, you can use the commands below:

```
git config —global user.email “you@example.com”
git config —global user.name “Your Name”
```
To prevent your credentials from expiring after 15 minutes, a cache has been configured for 12 hours. The cache duration can be modified through the cache credential helper bundled with git. The command below would set the timeout to an hour:

```
git config —global credential.helper ‘cache —timeout 3600’
```

From the git documentation: “this command caches credentials in memory for use by future git programs. The stored credentials never touch the disk, and are forgotten after a configurable timeout. The cache is accessible over a Unix domain socket, restricted to the current user by filesystem permissions.”


## STATEMENT OF INTEGRITY
By submitting the work, I declare that:

1. I have read and understood the University regulations relating to academic offences, including collusion and plagiarism: http://www.qub.ac.uk/directorates/AcademicStudentAffairs/AcademicAffairs/GeneralRegulations/Procedures/ProceduresforDealingwithAcademicOffences/

2. The submission is my own original work, and no part of it has been submitted for any other assignments, except as otherwise permitted;

4. All sources used, published or unpublished, have been acknowledged;

5. I give my consent for the work to be scanned using plagiarism detection software.

6. You agree to complete an oral assessment if requested to do so.

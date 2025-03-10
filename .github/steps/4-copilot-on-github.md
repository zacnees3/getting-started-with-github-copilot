## Step 4: Using GitHub Copilot within a pull request

Congratulations! You are finished with coding for this exercise. Now it's time to merge our work. :tada: To wrap up, let's learn about two limited-access Copilot features that can speed up our pull requests!

#### Copilot Pull Request Summaries

Typically, you would review your notes and commit messages then summarize them for your pull request description. This may take some time, especially if commit messages are inconsistent or code is not not documented well. Fortunately, Copilot can consider all changes in the pull request and provide the important highlights, and with references too!

Here is what that process looks like:

<!-- Add GIF image here -->

> [!NOTE]  
> This is a unavailable with the **Copilot Free** tier. [[docs]](https://docs.github.com/en/enterprise-cloud@latest/copilot/using-github-copilot/using-github-copilot-for-pull-requests/creating-a-pull-request-summary-with-github-copilot)

#### Copilot Review

More eyes on our work is always useful so let's ask Copilot to do a first pass before we do a normal peer review process. Copilot is great at catching common mistakes that can are fixed by simple adjustment, but please remember to use it responsibily.

Here is what that process looks like:

<!-- Add GIF image here -->

> [!IMPORTANT]  
> This is in **Public Preview** for organizations. [[docs]](https://docs.github.com/en/copilot/using-github-copilot/code-review/using-copilot-code-review)

### :keyboard: Activity: Summarize and review a PR with Copilot

Both **pull request summaries** and **copilot review** have limited access, so this activity is mostly optional. If you have access, Mona will gladly check your work though! If not, you can skip the optional steps.

1. In a web browser, open another tab and navigate to your exercise repository.

1. You might notice a **notification banner** suggesting to create a new pull request. Click that or use the **Pull Requests** tab at the top to create a new pull request. Please use the following details:

   - **base:** `main`
   - **compare:** `accelerate-with-copilot`
   - **title:** `Add registration validation and more activities`

1. (Optional) In the **Add a description** area, enter edit mode if needed, then click the **Copilot actions** icon and **Summary** action. After a moment, Copilot will add a description. :memo:

   <img alt="Copilot " width="400px" src="https://docs.github.com/assets/cb-42638/mw-1440/images/help/copilot/copilot-description-suggestion.webp">

1. (Optional) In the right side information panel at the top, locate the **Reviewers** section and click the **Request** button next to a **Copilot icon**. Wait a moment for Copilot to add a review comment to your pull request!

   > **Tip:** Notice a log entry was added to indicate a Copilot review was requested.

   <img alt="Copilot " height="230px" src="https://docs.github.com/assets/cb-68049/mw-1440/images/help/copilot/code-review/request-review@2x.webp">
   <img alt="Copilot " height="200px" src="https://docs.github.com/assets/cb-266339/mw-1440/images/help/copilot/code-review/review-comment@2x.webp">

1. At the bottom, press the **Merge pull request** button. Nice work! You are all done! :tada:

1. Wait a moment for Mona to check your work, provide feedback, and post a final review of this lesson!

<details>
<summary>Having trouble? 🤷</summary><br/>

If you don't get feedback, here are some things to check:

- Make sure Copilot generated a description.
- Make sure Copilot was requested to provide a review.

</details>

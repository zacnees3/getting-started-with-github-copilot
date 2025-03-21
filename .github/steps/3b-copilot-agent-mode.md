### :keyboard: Bonus Activity - Preview of GitHub Copilot Agent Mode

Nice! You found this hidden bonus level! 🎮 👾

If you have been keeping an eye on Github, you may have heard about **Agent** mode.
It's a public preview feature for GitHub Copilot.

But... it's only for _Insiders_! 😎🤫

But... good news. Anyone can access the Insiders version if they know the tricks. Yay! 🧐🎉

> [!IMPORTANT]
> This activity is optional and ungraded.

### :keyboard: Activity: Test out Copilot Agent mode! 🧑‍🚀

> [!IMPORTANT]
> Copilot Agent mode is only available when using the insiders version of VS Code and the pre-release version of the GitHub Copilot extension.

1. If needed, use the below steps to switch your VS Code and Copilot extension to the **Insiders** version.

   1. Ensure you are in a browser-based instance of VS Code (your Codespace).

      > **Tip:** This allows switching to **Insiders** mode without installing another version on your local computer.

   1. In the bottom left, click the **Manage** icon and select the **Switch to Insiders Version...** option.

      <img width="300" alt="image" src="https://github.com/user-attachments/assets/11580b67-9891-4aa9-9a7c-04aff1e7ef9c" />

   1. In the left navigation, select the **Extensions** tab.
      Find the **GitHub Copilot** entry, click the **Manage** icon, and select **Switch to Pre-Release Version**.

      <img width="300" alt="image" src="https://github.com/user-attachments/assets/39e1d9ae-ba50-4cd7-b6b6-eb51aa0a35aa" />

1. Open the **Copilot Edits** side panel. Use the new dropdown menu to switch to **Agent** mode.

   <img width="250" alt="image" src="https://github.com/user-attachments/assets/1849c14d-99f5-48f9-a7fb-8f623bb6837f" />

1. Time for a test! Let's ask Copilot to add functionality for removing participants.

   ```Prompt
   #codebase Please add a delete icon next to each participant and hide the bullet points.
   When clicked, it will unregister that participant from the activity.
   ```

   - If you try this prompt in **Edit** mode, you will find that the changes to the frontend and backend were made in a theoretical way. Although no syntax or runtime errors occurred, the changes were not compatible and didn't achieve the goal.
   - In **Agent** mode, Copilot reviewed its own work and refined it to ensure all changes were error free and coordinated together.

1. When Copilot is finished, restart the debugger and inspect the results. If you like the results, press the **Keep** button. If not, try providing Copilot some feedback.

1. Ask Copilot to fix a registration bug.

   ```Prompt
   #codebase I've noticed there seems to be a bug.
   When a participant is registered, the page must be refreshed to see the change on the activity.
   ```

   - If you try this prompt in **Edit** mode, it may or may not work.

1. When Copilot is finished, inspect the results. If you like the results, press the **Keep** button. If not, try providing Copilot some feedback.

1. That's your preview for now. We hope it was fun and please check back soon on the [Skills page](https://skills.github.com) for a dedicated exercise to explore even more of Agent Mode! 🧑‍🚀 🚀

### :keyboard: Activity: Test out Copilot Agent mode, _again_! 🧑‍🚀🚀

Just for fun, let's try something even more difficult and see what happens!

> [!IMPORTANT]
> The below request asks much more of Copilot.
> As such is more open-ended and may not work everytime.


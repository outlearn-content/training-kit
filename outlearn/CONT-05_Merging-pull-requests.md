<!--
{
"name" : "Merging-pull-requests",
"version" : "0.0.1",
"title" : "Merging Pull Requests",
"description" : "Merge the changes made on your feature branch into your master branch.",
"freshnessDate" : 2016-01-04,
"homepage" : "https://training.github.com/kit/modules/CONT-05_Merging-pull-requests.html",
"canonicalSource" : "https://training.github.com/kit/modules/CONT-05_Merging-pull-requests.html",
"license" : "CC BY 4.0 International"
}
-->


<!-- @section -->

# Presentation Slide Content

_Merge the changes made on your feature branch into your master branch._

<br>

# Merging Pull Requests

<br>

- At this point, your pull request should be approved and you are ready to merge it in to the `master` branch.
- When you merge your branch, you are taking the content and history from your feature branch and adding it to the content and history of the `master` branch.
- Many project teams have established rules about who should merge a pull request. Some say it should be the person who created the pull request since they will be the ones to deal with any issues resulting from the merge. Others say it should be a single person within the project team to ensure consistency. Still others say it can be anyone other than the person who created the pull request.
- There are also third party Continuous Integration (CI) tools you can integrate with GitHub to test the build before the merge is completed. There are pros and cons to each approach and we will not attempt to prescribe a solution here, but these are good conversations to have within your project team.
- Let's take a look at how you can merge the pull request and close the original issue at the same time.

![](https://training.github.com/kit/images/merge-logo.jpg)



<br>

# Merging Pull Requests

<!-- @resource, "url" : "http://youtu.be/3MUmLHHxSqE" -->


<br>

# Video Script

<br>

Do | Say
---|---
"Open the `pull request` to be merged" | "Visit your pull request now that it's ready to be merged"
"Show the `Conversation` view" | "You can merge a pull request at the bottom of the conversation view."
"Click `Merge pull request`" | "You simply click the Merge pull request button."
"Show the merge confirmation window" | "Now we want to include some special text that tells GitHub that this pull request should close the original issue."
Type `Fixes` | "Fixes is one of the special keywords that GitHub looks for in merge commits."
"Type `#`" | "We can use the # to auto-generate the link to the issue."
"Type a few letters from the issue name" | "Since the issue title contained your username, you can type the first few letters of your GitHub username to narrow down the list of possible issues."
"Select the correct issue from the drop down" | "Simply select your issue from the list."
"Click `Confirm merge`" | "And click confirm merge."
"Show confirmation message" | "A confirmation message will let you know that your pull request was merged and closed. It also let's you know that the branch we created can be safely deleted."
"Click `Delete branch`" | "Since we won't be using this branch anymore, you should go ahead and delete it now."
"Click `Issues` and then filter to see the `Closed` issues" | "You can now go back to the issues tab and you will see that your issue has been closed. Congratulations, you have completed your first contribution on GitHub."


<!-- @section -->

# Lab - Merging Pull Requests

Let's finish the workflow by merging our changes into master.

<!-- @task, "text" : "Merge the pull request you created, closing your original issue with the merge commit." -->

<!-- @section -->

# Additional Resources

<br>

# Special Keywords for Closing Issues

<!-- @resource, "url" : "https://help.github.com/articles/closing-issues-via-commit-messages/", "forceBasic" : true  -->

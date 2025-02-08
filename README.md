# Mark notifications for closed PRs as done

This is a template repository that can be used to create your own private repository with action which will 
mark all of your notifications related to closed pull requests as done.

## Setup

1. Use this template to create private repository
2. Create Github PAT with notitifications and repository access
3. Create actions secret named `GH_TOKEN` in your newly created repository (1) and fill it with value of
   your secret (2)
5. Go to actions, select `Mark notifications for closed PRs as done` and click on `Run workflow`
6. After action finishes you should see a summary with number of notifications marked as done



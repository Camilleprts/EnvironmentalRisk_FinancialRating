# Financial Rating Model with Environmental Risks

After doing some more research, it looks like having separate branches for different files doesn't really make sense, because in the end the point is to merge commits, and by having separate branches for separate files we'll always have different commits for each branch. I think the better way to organise the branches is to have one branch for each person instead, and we each push our individual changes to our own branch. And whenever we have a significant change, we can update each other on slack/whatsapp and then merge our commits from our individual branch to the main branch, and then others can do a pull request for the latest updates.



### whiteboard / todo:
 * user should specify type of model being run: qualitative, financial industrie or financial conseil.
    * load relevant model in each case.



### Covariates to add
 * factor variable for location?
 * amount of carbon use

#Unit 7 Project 1: Mr. Potato Head

![Imgur](http://i.imgur.com/Vy06FW3.gif)

Together we can create a Mr. Potato Head using GitHub! 


###Directions
1. You are on github.com and this is Venkat's `Mr_Potato_Head` repository:
2. Fork the Repo
3. Create a new workspace for this repository using the clone from Git URL from your repository.
4. Add your assigned body part to `potatohead.html`. Body parts can be found in the `assets` folder
5. Add the necessary CSS to your body part in the `potato.css` file.
6. Push your changes to your GitHub repo
7. Create a Pull request to your teacher's repo


##Remember: **Fork, Change, Push, Pull**
In Cloud 9 terminal:

```
 git status
```

You should see that potatohead.html and potato.css are modified, like this:

```
	modified:   potatohead.html
  modified:   potato.css
```

### Make a commit
Stage your changes in the index with `git add .`, then commit them.  The string after `-m` in `git commit` is the commit message. Don't use "Commit message" as your message!
Instead, say what you did, for example "added body part [your assigned body part]"

```
 git add .
 git commit -m "Commit message"  <<< but change the message!
```


### Send this commit up to github
Push your local commit up to github

```
 git push origin master
```

look at your github: You should see the commit you just made!  If you click "Commits" you can see the all of the work that has been put into Mr Potato Head, and you are at the top!

### Make a pull request

From your GitHub create a "New Pull Request" (the green button) to send your changes to the instructor.  The instructor will merge all of the changes (everyone's body parts), and at the end hopefully we'll have a whole Mr. Potato Head.

### Bonus

1. Create a button that sits below Mr. Potato Head that when it is clicked your body part will show or hide.

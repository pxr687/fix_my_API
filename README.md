# fix_my_API

When you run your app, after you register and login, you probably see this fallback error when you try to get a random quote:

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/8e749a743aa3fd5021724d7d767f0bf6a8278ec9/fallback.jpg" />

At the moment, our app is "talking" to the `quotable` API:

<img width="800" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/823fcda9cae4fe08786684d1ccffcafe346cd027/quotable.jpg" />

That API is hosted on Github, you can look at the code on this link: https://github.com/lukepeavey/quotable 

When you are looking at the `quotable` Github, click on the `Issues` tab - this is where users/developers can say "there is a problem with this code..."

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/78659fc625c3f509259aae1efcca6e44e144606e/quotable_issues.jpg" />

Can you see what the problem is?:

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/96d046a2a7898ce6c8998ad463978d163e4cc462/quotable_issues_2.jpg" />

To fix this, you may want to look for another API which can get a random quote. 

To fix your app - so that it displays a random quote - you will need to alter your code so that the app uses your new API... **DO THIS WITHOUT USING AI**...

Let me know if you get it working - if you cannot, then I will show you the solution at the end of the session:

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/d3fea776d5493a3b5426e30988f101da57869a2f/working.jpg" />

**HINT 1**:
You can call an API from your terminal to check what your app will "see" when it calls the API. If using a `bash` terminal, you can use:
`curl`:

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/dee7997c15eff6fa76240f2ee2d1063c4d606954/curl.jpg" />

Windows Powershell also has a `curl` command...

**HINT 2**:
There is a clue somewhere in this Github repository which tells you which APzi you can use to fix your app...

# fix_my_API

When you run your app, after you register and login, you probably see this fallback error when you try to get a random quote:

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/8e749a743aa3fd5021724d7d767f0bf6a8278ec9/fallback.jpg" />

At the moment, our app is "talking" to the `quotable` API:

<img width="800" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/823fcda9cae4fe08786684d1ccffcafe346cd027/quotable.jpg" />

That API is hosted on Github, you can look at the code on this link: https://github.com/lukepeavey/quotable 

When you are looking at the `quotable` Github, click on the `Issues` tab - this is where users/develops can say "there is a problem with this code..."

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/78659fc625c3f509259aae1efcca6e44e144606e/quotable_issues.jpg" />

Can you see what the problem is?:

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/96d046a2a7898ce6c8998ad463978d163e4cc462/quotable_issues_2.jpg" />

To fix this, you may want to look at: https://zenquotes.io 

...this is another API which can get a random quote. 

To fix your app, you will need to change some code to use the new API... **DO THIS WITHOUT USING AN AI**...

Let me know if you get it working - if you cannot, then I will show you the solution at the end of the session:

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/d3fea776d5493a3b5426e30988f101da57869a2f/working.jpg" />

**HINT 1**:
You can call an API from your terminal to check what your app will "see" when it calls the API. If using a `bash` terminal, you can use:
`curl -v https://api.quotable.io/`

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/dee7997c15eff6fa76240f2ee2d1063c4d606954/curl.jpg" />

<img width="600" height="800" alt="image" src="https://github.com/pxr687/fix_my_API/blob/3409e0915bd083cec820eefd1f38ba6a3c255bc4/curl_2.jpg" />

**HINT 2**:
You can also look at what your app will "see" after it sends the API call to `zenquotes`, using this link: https://zenquotes.io/api/random

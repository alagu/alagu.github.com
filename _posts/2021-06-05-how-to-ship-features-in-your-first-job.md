---
layout: post
title: How to ship features in your first job
---

I wrote this how-to for the new-hires and interns who joined [Peoplebox](https://www.peoplebox.ai/) recently. It might seem obvious for folks who have been doing this for long, but not for first-timers. 

1. **Understand the feature**
    - Understand the feature, design, see what is there current experience. If new, understand the current code.
    - Find out broken flows in the feature shared by the product/design person.
    - Find out which customer needs it and why. See if this is the best solution. Wear your product manager hat.
    - Understand how this helps the business. Your change does bring in $$
2. **Break into smaller releases/versions**
    - If the feature seems really large, break it down into multiple small, meaningful releases.
    - This might be harder at first, but you could figure out what features to remove from scope from first release, but still be valuable for the customer.
    - Benefits - faster release, less code changes to review, easier to test.
3. **Do the task breakdown**
    1. Break the tasks down to minimum one day or half day. 
    2. If something takes more than 1 day, break it further to achievable goals for each day. 
    3. You’ll have a rough estimate of your dev complete. Accurate estimation is a myth. 
    4. Add testing time to your estimation as well - this can give you task estimation.
4. **Build clarity in the tech implementation**
    1. If there is a necessary technical architecture change required - plan for it 
    2. For Backend folks - plan your models, important logic flows, service objects.
    3. For Frontend folks - Redux stores, Component Breakdown, Reuse of design systems
    4. Find better libraries, gems that can help you to solve this problem easier. No code is better than elegant code. Elegant code is better than shitty code.
5. **Start writing code**
    1. This is when you should actually start write code. 
    2. If you were fresh out of college, you would have started here earlier. So hi 👋 . Just acknowledge there are enough things to do before writing code.
    3. Update progress in the daily standup, if you foresee any delays - share in the standup. 
    4. Keep back merging regularly. And keep pushing code to github as frequent as possible. Data losses happen.
6. **Test the feature**
    1. Start with testing your code and components.
    2. Then move on to integration testing. If you are a backend person, test along with the frontend person.
    3. Find out edge cases - no one would know edge cases better than you.
7. **Code review**
    1. Give it for code-review, don't always request from the most common person. Find someone else in the team who can code review. 
    2. Make changes based on what they suggest. You'll learn, they'll learn.
8. **Give it to test**
    1. If all good, push code to staging environment to be given for testing. 
    2. Help the Test team understand the edge cases.
    3. If any test data creation is required, help them to set it up.
9. **Release it to production**
    1. Merge your code with master
    2. Release to production with senior engineers.
    3. Watch Luckyorange, metrics after the release - see if users are using your features.


If you read this, also read [20 tips for your first job](http://atulchitnis.net/2011/first-job/)
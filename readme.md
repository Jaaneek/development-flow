## Branch Naming Convention:

If there is no task on linear for what you are doing consider:
1. Creating it yourself
2. Quick urgent fix? Feel free to push it without following the convention, try to make sure the branch name is understandable.
>we should have some type of prefix for this, so we know not to go looking for an issue in linear

**Instructions:**
>I am trying to determine if we can do this with linear issue templates
Just copy from linear, click on **Copy git branch name**:
<img width="682" alt="image" src="https://github.com/Jaaneek/development-flow/assets/25470423/2297a41e-6876-4c67-a7c3-b067526428b3">


**Example:**
>I would like to understand why we need to designate something as a fix/feature/bug/whatever

fix/try-22-cant-unvote-a-proposal

feature/try-45-display-subscription-popup-instead-of-no-subscription-toast

**Explanation:**

fix - bugs, something that didn't work before, typos

feature - new things, improvements

try-45 - task number from linear

# Pull requests
>I believe there may be a way to do this automatically. 
Should we force folks to do this from linear?
I set up "autolink" with GitHub custom-pages - used LIN- as a prefix - https://linear.app/docs/github#enable-autolink
Also can create issues from VS -  https://marketplace.visualstudio.com/items?itemName=gauravp123.linear-create-branch&ssr=false#overview
1.  Always branch out of Master/Main
2.  Include task number in pull request so linear will start tracking it. Feel free to include more than one task if you were working on few things at the same time.
3.  Feel free to either copy description from linear title or write it yourself if you want to.

Example:
<img width="547" alt="image" src="https://github.com/Jaaneek/development-flow/assets/25470423/cff33893-2e33-4acd-8666-bca3383d39e7">


You should see info from linear, it means the linear is tracking it so you don't have to :)
<img width="1004" alt="image" src="https://github.com/Jaaneek/development-flow/assets/25470423/4a1de6f3-f083-4d7c-a7fc-3f270a719dc2">


# Code review
>I would like to try no code reviews - for the short term focus on hiring developers that do not need supervision. This does not mean they should not ask for preview, etc. This could considerably slow down the development
1.  At least 1 approve before merging
2.  Quick urgent fix - feel free to merge it without code review

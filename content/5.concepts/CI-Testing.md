---
title : CI Testing
status: draft
---

...

**Topics to cover and ideas**

 - CI - Continuous Integration
 - if you make changes and a test doesn't break, you are making random changes (and have no way to know if those changes are still active tomorrow)
 - Pushing security to the left
 - Test your pipeline
 - "config changes can be more dangerous than code changes"
    - find source (quote from [AWS re:Invent 2017: Performing Chaos at Netflix Scale (DEV334)](https://www.youtube.com/watch?v=LaKGx0dAUlo) )
    - the reason this is true is because we don't test out config changes (at least the same way we test our code)
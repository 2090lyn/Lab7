Cathlyn Goldberg

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   
   Within a Github action that runs whenever code is pushed because this helps find bugs early and makes sure the project works after changes are made. And it also reduces the chance of forgetting to run tests locally. It's also better than waiting until everything is finished because bugs can build up and become harder to fix later.

2) Would you use an end to end test to check if a function is returning the correct output?

   No


4) What is the difference between navigation and snapshot mode?

    Navigation mode analyzes a page while it is loading or reloading, so it is best for measuring load performance and page timing. Snapshot mode analyzes the page in its current state after it has loaded, making it useful for checking accessibility and the final rendered UI, but it does not measure load performance.

5) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
    1. Add a metadata description
    2. Add a lang attribute to the html tag
    3. Reduce critical request chains by deferring or minimizing unnecessary resources to improve page load.




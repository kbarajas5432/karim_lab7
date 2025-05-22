Karim Barajas
I am working on this lab myself

Check Your Understanding Questions:

1. I would fit my automated tests within a Github action that runs whenever code is pushed. I would do this because whenever new code is pushed to a remote repository, the automated end-to-end tests would run. These tests are extremely important because it helps ensure that your code's bugs or regressions are quickly caught. Not only that, but this setup helps prevent broken code from being merged into the main branch.
2. I would not use an end to end test to check if a function is returning the correct output.
3. You can analyze a page right after it loads, which gives the overall performance metric in navigation mode. However, in this mode you can't nalyze interactions or changes in content. Basically, this mode is useful for evaluating load speed. Whereas snapchot mode, it only analyzes a page in its current state or at a specific moment. This method is best for finding accessibility issues, but it can't analyze JS performance or changes to the DOM tree.
4. Based on the Lighthouse results, the 3 things to change are providing a `[lang]` attribute for the `<html>` element, including a `<meta name="viewport">` tag with width or initial-scale, and also providing a meta description of the document.






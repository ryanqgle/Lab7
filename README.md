# Lab 7
 Ryan Le
## 1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

I would use '1. Within a GitHub action that runs whenever code is pushed' because it will test whether or not the code that is being pushed will result in any code conflicts or failures that may impact the project's functionality or uptime. This is better than running it locally because local testing may ensure the functionality on a single machine but may not for a different machine. Running all the tests after development does not even need explanation. Not testing for the entirety of the process may build up thousands of issues you don't notice until the end.

## 2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, because that's overkill to just test a single function. Unless the function is the entire project, unit tests will work fine. An E2E test would require there to be the rest of the project or some pipeline so that the function is used in the right context.

## 3. What is the difference between navigation and snapshot mode?

The navigation mode can analyze the performance of the webpage along with what the snapshot mode analyzes. The snapshot mode analyzes the current page and checks for accessibility, SEO, and practices. As a result, the navigation mode takes longer to run. 

## 4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. Improve accessibility by including a \[lang\] attribute to allow for interpretation of content for a larger user audience.
2. Add a meta description to improve search engine optimization.
3. Flatten the network dependency tree by reducing chain lengths, consider more inline css rather than a separate file to eliminate the need for a separate network request, and potentially reduce resource sizes (i.e. compress images and other similar files). This reduces the maximum latency and allows faster rendering. 






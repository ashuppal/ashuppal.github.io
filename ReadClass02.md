Read: Class 02

An introduction to NodeJS and Express

Explain middleware, answer as though I were a non-technical recruiter.
Middleware is software that different applications use to communicate with each other.

Express the most popular Node web framework.

Express is “unopinionated.” What does that mean?
Unopinionated frameworks like Express have far fewer restrictions on the best way to glue components together to achieve a goal, 
or even what components should be used. They make it easier for developers to use the most suitable tools to complete a particular task.

What is a module and why is modularity useful to us as developers?
A module is a piece of code that can be independently created and maintained to be used in different systems.
Modular programming usually makes your code easier to read because it means separating it into functions that each only deal with one aspect of the overall functionality.

What is NPM?
npm is the world's largest software registry. 

What version of npm are you running on your machine?
9.4.0

What command would you type to install a library/package called ‘jshint’ into your node project?
To install the JSHint tool, run the command npm install jshint 

What is TDD?
TDD refers to “Test-driven development”.

Explain why tests are important. Please explain as though I were your non technical elder.
Tests are important as they identify any issues and defects with the written code so they can be fixed before the software product is delivered. 
Tests also improves product quality.

What are three expected benefits of testing
many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort
the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases
although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
Individual pitfalls:
forgetting to run tests frequently
writing too many tests at once
Team pitfalls:
partial adoption – only a few developers on the team use TDD
poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time

CI/CD

What are three benefits of Continuous Integration?
1. Smaller Code Changes
2.  More Test Reliability
3.  Customer Satisfaction
 
What is the difference between Continuos Delivery and Continuous Deployment?
Continuous Integration is the automation of builds while Continuous Deployment focuses on the deployment that means the actual installation and distribution of the bits.

Explain how GitHub fits into this process.(ref: resources.github)
Continuous integration (CI) automatically builds, tests, and integrates code changes within a shared repository.
thenContinuous delivery (CD) automatically delivers code changes to production-ready environments for approval.








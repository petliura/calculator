Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

[![Build Status](https://dev.azure.com/petliura0962/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_apis/build/status/petliura.calculator?branchName=master)](https://dev.azure.com/petliura0962/Integrating%20External%20Source%20Control%20with%20Azure%20Pipelines/_build/latest?definitionId=10&branchName=master)

[![Naereen's top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Naereen&theme=blue-green)](https://github.com/anuraghazra/github-readme-stats)


The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.


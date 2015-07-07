SonarQube CSS Plugin
====================

This is the SonarQube CSS Plugin.

Project homepage:
https://github.com/SonarCommunity/sonar-css

Issue tracking:
https://github.com/SonarCommunity/sonar-css/issues

CI builds:
http://sonarplugins.ci.cloudbees.com/job/css

Download:
http://downloads.sonarsource.com/plugins/org/codehaus/sonar-plugins/css/sonar-css-plugin/

## Description / Features
The plugin enables analysis of CSS within SonarQube.

## Usage
### Run an Analysis with the SonarQube Runner (recommended method)
To run an analysis of your project with CSS files, use the SonarQube Runner.

A sample project is available on GitHub: https://github.com/SonarSource/sonar-examples/tree/master/projects/languages/css/css-sonar-runner

### Run an Analysis with the other Analyzers
Maven and Ant can also be used to launch analysis on CSS projects.

## Metrics
### Functions
Number of rules.

### Complexity
The following elements increment the complexity by one:

* Class selector
* ID selector
* Attribute selector
* Type selector
* Pseudo-class selector
* At-rule

### Complexity/function
It computes the complexity/rule, meaning the average number of selectors per rule.

It gives a measurement on how specific the selectors are.

As the computation of complexity in the CSS plugin is still in its early stage, it can be turned off if necessary at global and project levels.


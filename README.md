# Deploy a Node.js application to one or more machines

[![Run Status](https://api.shippable.com/projects/59023242cd25170600356e72/badge?branch=master)](https://app.shippable.com/github/devops-recipes/deploy-nodecluster-basic) [![Coverage Badge](https://api.shippable.com/projects/59023242cd25170600356e72/coverageBadge?branch=master)](https://app.shippable.com/github/devops-recipes/deploy-nodecluster-basic)

![AyeAye](https://github.com/devops-recipes/deploy-nodecluster-basic/blob/master/public/resources/images/captain.png)

A simple Node JS application with unit tests and coverage reports using mocha
and istanbul.

## Run CI for this repo on Shippable
* Fork this repo into your local repo
* Login into the [Continuous Integration Service](wwww.shippable.com)
* Create a generic [key/value integration](http://docs.shippable.com/reference/int-key-value) on shippable, containing your AWS credentials.
* All CI configuration is in `shippable.yml`
* Follow these [CI Setup Instructions](http://docs.shippable.com/ci/runFirstBuild/) if you have never used Shippable CI Service
* Update the integrationName in the `integrations` section if you used something other than `dr-aws-kv`
* You should be able to run a manual build or webhook build on commit

## CI Reports on Shippable

### CI Integration View
![CI Integration View](https://github.com/devops-recipes/deploy-nodecluster-basic/blob/master/public/resources/images/integration.png)

### CI Console Output
![CI Console Output](https://github.com/devops-recipes/deploy-nodecluster-basic/blob/master/public/resources/images/console.jpg)

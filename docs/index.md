# cork - the most reliable build tool ever conceived (probably)

cork is a tool to create build templates. Define a workflow once, reuse it everywhere.

cork utilizes containerization to achieve highly reliable and highly portable build workflows. 

cork is the tool you always wanted but didn't know how to describe.

Have you ever had to spin up a build agent for your CI tool and needed to
build node-v4 projects and node-v6? If so, you've run in to issues with tools
conflicting. It's possible to make it work, but why not save yourself the
headache of having to deal with build agents. Imagine if you could make it so
the exact same tool used in CI to build/test was the tool you used on your
local development machine.

Dream no more. Cork is here.

Cork is powered by docker and runs anywhere docker runs. If it works on
Linux, it will work on Windows and OS X.

## Key Use Cases

* Create templates for build workflows
* Create build workflows that work the same locally as the do in CI
* Access private repositories in a reliable build process
  * Protect your secrets from docker images

## Getting started

```eval_rst
.. toctree::
   :maxdepth: 2

   tutorial/installing
   tutorial/quick-start
   tutorial/advanced
   tutorial/dive-into-internals
```
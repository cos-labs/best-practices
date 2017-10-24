# Code Review Checklist
* Can you fully understand what every line of code does, and is it very simple (<10 lines touched)?
  * If so, go ahead and merge it.
  * If not, continue to next step.
* Is the PR well-named and does it include a description of everything changed?
  * If a change is not documented, do not merge it, and ask for a better PR name and summary.
  * If so, continue to next step.
* Does the code have tests associated with it?
  * If the tests look sound and offer full coverage, and they pass, go ahead and merge it.
  * If not, continue to the next step.
* Pull the code into a temp branch and test its described functionality, as well as any functionality that might be affected by the PR.
  * If it works, go ahead and pass it.
  * If something breaks, let the PR's author know and ask them to fix it. Repeat until everything looks good!

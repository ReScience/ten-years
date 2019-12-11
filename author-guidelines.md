# Author guidelines for reproducibility reports

The reproducibility reports written by participants in the ten-years challenge are sufficiently different from standard ReScience articles that our standard rules and guidelines make no sense for them. Please use the following guidelines in preparing your submissions!

## Article

Please address the following topics to the extent that they make sense for your particular case.

### Historical context

- Summarize the scientific question that your code was written to explore.
- Describe the computational context: Which hardware was used to run the code? Which software infrastructure? Which constraints existed on software development? Which technical choices (language, libraries, ...) were made? Were reproducibility and/or re-usability important criteria?
- Was the source code published? Was it archived somewhere?

Please provide only information you are certain about. It's OK to forget technical details after many years.

### Retrieval of the software

- Was it easy to find a copy of your source code?
- Was it easy to locate the dependencies?
- Provide a list of all dependencies (libraries but also tools such as compilers).

### Execution

Describe what you did in order to run the software today.

- Did you succeed in running the software in a modern computational environment? Or did you have to search for old versions of tools and libraries?
- Describe the computational environment of the reproduction: hardware, operating system, compiler versions etc.
- Did you have to modify the software in order to make it run today?
- Were the original instructions that came with the software sufficient, or did you have to modify or extend them?
- How close were the results you got to the originally published ones?

If you had to make any modifications to the software or to the instructions that were supplied with it, try to describe which competence someone else that you would have to have in order to do the same work. Would a general familiarity with your programming language and environment have been sufficient?

## Software

If the licenses applying to the original software allow, please make your old software available as a repository on GitHub or an equivalent site. Add your old software as a single commit (ideally the initial one), and then add commits containing modifications that you had to make, additional tools (scripts, makefiles, ...) that you wrote for re-running your software today, or additional instructions. Make sure your repository contains a license. Finaly, submit your repository to [Software Heritage](http://save.softwareheritage.org/) for archiving.

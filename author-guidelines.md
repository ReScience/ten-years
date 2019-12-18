# Author guidelines for reproducibility reports

The reproducibility reports written by participants in the ten-years challenge are sufficiently different from standard ReScience articles that our standard rules and guidelines make no sense for them. Please use the following guidelines in preparing your submissions!

## Article

Please address the following topics to the extent that they make sense for your particular case.

In addition to the content covered below, we are interested in the insight resulting from
the reproducibility experience in relation to the choice of technology, and in your opinion
on the original source code (clarity, documentation, etc).

### Historical context

- Summarize the scientific question that your code was written to explore.
- Describe the computational context: Which hardware was used to run the code? Which software infrastructure? Which constraints existed on software development? Which technical choices (language, libraries, ...) were made? Were reproducibility and/or re-usability important criteria?
- About the original source code: Was it published? Was it archived somewhere? Was there a license for it?

Please provide only information you are certain about. It's OK to forget technical details after many years.

### Retrieval of the software

- Was it easy to find a copy of your source code?
- Was it easy to locate and setup the dependencies?
- Provide a list of all dependencies (libraries but also tools such as compilers).

### Execution

Describe what you did in order to run the software today.

- Did you succeed in running the software in a modern computational environment? Or did you have to search for old versions of tools and libraries?
- Describe the computational environment of the reproduction: hardware, operating system, compiler versions etc.
- Did you have to modify the software in order to make it run today?
- Were the original instructions that came with the software sufficient, or did you have to modify or extend them?
- How close were the results you got to the originally published ones? Include the
  replicated data table and figure, as we do in other ReScience articles.

If you had to make any modifications to the software or to the instructions that were supplied with it, try to describe which competence another researcher would need in order to do the same work. Would a general familiarity with your programming language and environment have been sufficient?

## Software

If the licenses applying to the original software allow, please make your old software
available as a repository on GitHub or an equivalent site. In the best case scenario, in
which the old code is publishable, here is the procedure:

1. Add your old software as a single commit (ideally the initial one) of a new source
   repository.
2. Edit the code as necessary to reproduce the results in today's computational environment,
   committing the changes in logical units in the process. Include the additional tools
   (scripts, makefiles, ...) that you wrote for re-running your software and the additional
   instructions.
3. Make sure your repository contains a license.
4. Finaly, submit your repository to [Software Heritage](http://save.softwareheritage.org/)
   for archiving.

# m2e.wtp-resources-bug
This is a proof of concept for bug [538843](https://bugs.eclipse.org/bugs/show_bug.cgi?id=538843) of m2e-wtp

## Organization of the project

I made 2 branches:

- master: contains the code giving "Utility Facet configuration is aborted as the Java Configuration is inconsistent" as warning message on maven-m2e-jar
- example_workaround: contains the example workaround that I think is best practice to use as separation between source folders and manipulation of source files

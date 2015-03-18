# The DevMine project

Initially, DevMine is a project about creating a database of developers and
establishing developers profiles based on their open source contributions.

Since its inception, its goals have evolved into a broader vision. The DevMine
project crawls metadata from open source projects and gathers source code.

Along with crawling and fetching tools, software to analyze this data are
provided as well.

DevMine consist of a complete toolchain from which several tools can be combined
together to do analysis. The output of one tool is typically piped to the input
of another to produce the final data and all of the serialization works thanks
to JSON.

DevMine has its own AST that can be seen as a generic AST to provide an
abstraction over the various programming languages over which the analysis can
be performed.

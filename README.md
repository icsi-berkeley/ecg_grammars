# ecg-grammars

This repository is intended to be a base for ECG grammar development and distribution. At the moment - and in the foreseeable future - it contains only the grammar files themselves, associated ontologies, and preferences files. In other words, the tools to do something with the grammar (Workbench, Analyzer JAR file) are distributed separately.

To view and run the grammar in the ECG Workbench, clone <a href=https://github.com/icsi-berkeley/workbench-release>this repo</a> and open the version that corresponds to your operating system.

To run the grammar in Terminal to view resulting n-tuples from input utterances, see <a href=https://github.com/icsi-berkeley/framework-code>this repository</a>.

We recently updated the core grammar to clean it up and better organize it. Currently only compRobots and hesperian work with the updated core grammar. To use other grammars, please checkout the git commmit tag `old-core`. Also, the latest version of the hesperian grammar exists in its entirety on its own branch rather than the master branch because it require slight modifications to the core grammar.

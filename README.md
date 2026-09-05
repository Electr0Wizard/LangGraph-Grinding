**LangGraph Exercises and Workflows**

* **Introduction**: This repository features a collection of interactive exercises and workflows built using **LangGraph** and Python. It demonstrates how to set up stateful multi-agent graphs, conditional routing, and sequential execution flows.


* **Tasks Implemented**:
* **Basic State Graph (Processor)**: Initialized a simple `StateGraph` with a single node to process user values and format a greeting message with a sum total.


* **Multi-Step Greeting Workflow**: Built a sequential graph (`greeting` $\rightarrow$ `tell_age` $\rightarrow$ `tell_skills`) that sequentially updates an agent state dictionary with demographic and skill sets.


* **Conditional Calculator Router**: Implemented a dynamic routing system (`router`) that analyzes operation symbols (`+`, `-`, `*`, `/`) and directs data execution to specialized math nodes (`adder`, `subtracter`, `multiplier`, `divider`).


* **Multi-Stage Chain Calculator**: Extended the calculator graph to handle multi-step arithmetic workflows by saving intermediate results using a `saver` node and routing to secondary operations.


* **Automated Number Guessing Game**: Developed a stateful, loop-based guessing game where an agent iteratively simulates guesses, uses a referee node to provide high/low hints, updates boundaries, and tracks attempts until success or game loss.

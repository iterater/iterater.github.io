# ABM: Practice book on RL

## ToC
| |Chapter|Location|Status|
|-|-|-|-|
|0|Introduction|`intro.md`|TBD|
|1|Basic RL example with CartPole|`1_Basic_RL/1_RL_basics.ipynb`|✅ Done (possible update)|
|2|Inverse RL|`2_Inverse_RL/2_IRL.ipynb.ipynb`|✅Done - Ashish|
|3|MARL|`3_MARL/MARL.ipynb`|✅ Done - Chao|
|4|RLHF|-|TBD - Ekaterina|

## Chapter instruction

Each chapter is implemented in a form of single notebook (`.ipynb`) structured with the following sections in MarkDown. The notebook starts with chapter title (1st level header). Each section starts with 2nd level header. Sub-sections (3rd level headers) can be used for further structuring of sections.
- **Problem Definition.** Introduction of problem, basic knowledge, planned experiments, and applied methods. Diagrams, references, equations are good to illustrate this chapter.
- **Implementation.** Basic environment setup: code blocks with verbose explanation of what is done and obtained after cell's run.
- **Experiments.** Detailed implementation and run of experiments with explanation of the results.
- **Conclusion.** Summarization of the main observations and takeaways.
- **References.** References, if needed. Will be converted into complete book references.

## Building

The book is intent to be compiled using [JupyterBook](https://jupyterbook.org/en/stable/intro.html). The following command is used to run building
```bash
jupyter-book build . --builder pdflatex
```

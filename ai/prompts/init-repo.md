Please read (or create if not exists) AGENTS.md files and check if you think is it ok for your needs to work on this project.
Consider this things:
- ask me whatever you think it is necessary to better understand this project and als related project, infrastructure, etc..
- we ca have big task and small task so if you need create some agents you think are needed. Do not create agents speculatively
- For big task a planner is needed because i'd like to read how he think to work on the task.
- if you think it is better to work with test driven development (aka test-first) do it and use it as your standard way of work
- if you need, configure different agents with their configuration files and specify the preferred model for the agents. For example to run test the lower model is enough
- do not specify the antrophic model name because we can use other model, instead specify model type and which effert to use then you can choose based in the available models.
- if you need, write a documentation inside .md files in "docs" folder. As you know the more granular you write the documentation the better you can choose what file read for a single task. If you need create a table of contents with links to each documentation file.
- The goal is that agents config file / AGENTS.md files contain only the way of work and all the documentation is inside granular documentation files
- IMPORTANT: in the context only the required documentation should be included to not waste context/memory.
- remember: simple code is better code, write always in english, be concise in answer do not waste word since i do not have time to read papers of words
- i'd like that you keep documentation and agents files updated when this project changes, if you think it is needde create an apposite agent to do that
- create a tmp folder that should be .gitignored in which we can add .md files with task description
- when configuring agents create 2 files for agents: for example planner.md and planner-shared.md. planner.md contains the repo-specific information (if any), planner-shared.md contains all the informations that are not specific to a repository and that could be shared with other repositories. in planner.md create a link to the planner-shared.md. In the future planner-shared.md will be centralized in a helper repository.
- dependency versions (a rule for future changes, not a task to run now): when you add or bump a package, write the exact version in package.json (`1.2.3`, not `^1.2.3`). Do not mass-pin existing ranges unless asked.
- configure this project to operate in "agentic loop mode"
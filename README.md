# @code-with-von/templates

#templates

This repository was created with the main **intention** of sharing:

- templates created by **me** or **open-source** templates **I worked** into making adaptations to **my** needs

---

## Repository structure:

This is an **important** aspect regarding this aspect. Organizing repositories depends on the one(s) working on that. The initial plan is to share projects individually as in their own **Git** repository, either as a **submodule**[^0], but for that to happen, some considerations are to be **taken**:

1. each project **may or not** have their own **submodules/subprojects** (depends on the use-case)
1. regardless on how **deep** a submodule/project exists in the repository, each one of them has their individual **License**[^1] which should be followed by **the end user** (aka - YOU) for each **shared project**
1. this project provides both **educational information** and **possible technical resources** (when possible) that can help other fellow developers on their way into learning / creating / starting their own work (in case they have no starting point or references)
1. I am not not to **impose** rules, but to **provide** the rules **I** use on my *day-by-day* work as a developer, which a career that lasts for a bit more  **20years**
1. I vouch for **self-improvement** and this is why I am sharing this project as this will be a constant **WIP** (Work In Progress) project that will be updated with new resources and improvements over time as I continue to learn and grow as a developer

> [!important]
> #### Considerations about the use of AI:
> The **use of AI** in this project **was** (until now), **is** and **will always be** restricted to the **minimum as it can be** (remember that to the **current date**  are not anymore 100% free of AI interference, but with desire to learn we do our best to **use it as least as possible**)
> Rest assured that **Ai** was only used here as a **code-completion / code-suggestion** tool.
>
> The goal of this project is to **share the knowledge** and **usable resources**, in all possible levels, about everything I had gathered through years of experience, in a **way that the ones accessing this project can learn and grow from it** and not just **copy-paste code** or **create AI-generated content out of it**.

---

## List of Templates[^2]

### 1. License Templates:

<table>
  <tbody>
    <tr>
      <th>Repository URL</th>
      <td><a href='https://github.com/code-with-von/license-templates'>License Templates</a></td>
    </tr>
    <tr>
      <th>Version</th>
      <td>R 1.0.0</td>
    </tr>
    <tr>
      <th colspan="2">Additional Information</th>
    </tr>
    <tr>
      <th>License Template</th>
      <th>List of files provided</th>
    </tr>
    <tr>
      <td><a href='https://github.com/code-with-von/license-templates/tree/main/open-source-gnu'>Open Source</a></td>
      <td><ul><li>License.md (a customized EULA for open source specs)</li><li>GNU.md (original code, but reformatted to be readable without undesired line breaks)</li></ul></td>
    </tr>
    <tr>
      <td><a href='https://github.com/code-with-von/license-templates/tree/main/read-only'>Read Only</a></td>
      <td><ul><li>License.md (a customized EULA for read only specs)</li></ul></td>
    </tr>
    <tr>
      <td><a href='https://github.com/code-with-von/license-templates/tree/main/use-only'>Use Only</a></td>
      <td><ul><li>License.md (a customized EULA for use only specs)</li></ul></td>
    </tr>
  </tbody>
</table>

---

### 2. Documentation Strategies:

<table>
  <tbody>
    <tr>
      <th>Repository URL</th>
      <td colspan="2"><a href='https://github.com/code-with-von/codumentation-strategies'>Documentation Strategies</a></td>
    </tr>
    <tr>
      <th>Version</th>
      <td colspan="2">R 1.0.0</td>
    </tr>
    <tr>
      <th>Strategy</th>
      <th>Technology</th>
      <th>Preview URL</th>
    </tr>
    <tr>
      <th colspan="3">Additional Information</th>
    </tr>
    <tr>
      <td><a href='#'>Fumadocs</a></td>
      <td>NexJs, React, TailwindCss and MDX flavored syntax (uses Infisical for environment variables and Posthog for analytics) + features a set of additional plugins and custom components</td>
      <td><a href='#'>Deployed project</a></td>
    </tr>
    <!-- <tr>
      <td><a href='#'>GitWiki (planned</a></td>
      <td>Github Markdown flavored syntax for wiki pages</td>
      <td><a href='#'>Deployed project</a></td>
    </tr> -->
  </tbody>
</table>

---

### 3. Web development Starter Templates:

This section is still being created and as new templates are created, we'll add them here.

<!-- <table>
  <tbody>
    <tr>
      <th>Template</th>
      <th>Tech-stack</th>
    </tr>
    <tr>
      <td><a href='#'>"Vanilla" Web App</a></td>
      <td>HTML, CSS, JavaScript</td>
    </tr>
    <tr>
      <td><a href='#'>"Vanilla" Web App + TailwindCss</a></td>
      <td>HTML, TailwindCss, JavaScript (uses Node.js for building the CSS assets used)</td>
    </tr>
    <tr>
      <td><a href='#'>Pug Web App + CSS</a></td>
      <td>Pug, CSS, JavaScript (uses Node.js for building the project into a deployable format)</td>
    </tr>
    <tr>
      <td><a href='#'>Pug Web App + TailwindCss</a></td>
      <td>Pug, TailwindCss, JavaScript (uses Node.js for building the project into a deployable format)</td>
    </tr>
    <tr>
      <td><a href='#'>Pug Web App + TailwindCss</a></td>
      <td>Pug, TailwindCss, JavaScript (uses Node.js for building the CSS assets used)</td>
    </tr>
    <tr>
      <td><a href='#'>Vite + React + TailwindCss + Material UI</a></td>
      <td>Vite, React, TailwindCss, Material UI (uses Node.js for building the project into a deployable format)</td>
    </tr>
    <tr>
      <td><a href='#'>Vite + React + TailwindCss + Shadcn UI</a></td>
      <td>Vite, React, TailwindCss, Shadcn UI (uses Node.js for building the project into a deployable format)</td>
    </tr>
    <tr>
      <td><a href='#'>NextJs + React + TailwindCss + Material UI</a></td>
      <td>NextJs, React, TailwindCss, Material UI (uses Node.js for building the project into a deployable format)</td>
    </tr>
    <tr>
      <td><a href='#'>NextJs + React + TailwindCss + Shadcn UI</a></td>
      <td>NextJs, React, TailwindCss, Shadcn UI (uses Node.js for building the project into a deployable format)</td>
    </tr>
  </tbody>
</table> -->


[^0]: A Submodule is a Git repository that is embedded within another Git repository. It allows you to keep a Git repository as a subdirectory (child repository) of another Git repository (parent repository) and work on it independently of the parent repository. In other words, it's a self-contained project that can be included in other projects always making references (symlinks) to the last approved commit of that project

[^1]: The **License** attached to each project/submodule **provides** all necessary information how/when/where to really make use of each project provided by this repository and their subprojects

[^2]: This list will be constantly updated as new templates are being added to this project
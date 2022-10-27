---
title: "dbt Cloud features"
id: "dbt-cloud-features"
---


## dbt Cloud IDE

:::info 📌

The new and refreshed Cloud IDE will be open to General Availability by end of October 2022. The new Cloud IDE includes performance upgrades, ergonomics improvements, and some delightful enhancements!

Review the [new Cloud IDE features](#ide-features) for more info!

:::

The dbt Cloud [integrated development environment (IDE)](/docs/get-started/develop-in-the-cloud) allows you to build, test, run, and version control your dbt projects directly from your browser. The IDE is the fastest and most reliable way to deploy dbt, and provides a real-time editing and execution environment for your dbt project &mdash; no command line required.  Anyone can use the IDE, from new dbt developers to seasoned practitioners.

With the Cloud IDE, you can:

- Write modular SQL models with `select` statements and the [ref()](/reference/dbt-jinja-functions/ref) function
- Compile dbt code into SQL and execute it against your database directly
- Test every model before deploying them to production
- Generate and view documentation of your dbt project
- Leverage [git and version-control your code](/docs/collaborate/git/version-control-basics) from your browser with a couple of clicks
- Create and test Python models:
    * You can `compile` Python models to see the full function that gets executed in your data platform
    * You can see Python models in DAG in dbt version 1.3 and higher
    * You can't preview python models, currently
- Visualize a directed acyclic graph (DAG), [and more](/docs/get-started/dbt-cloud-tips)

## IDE features
The dbt Cloud IDE comes with features, including better performance and exciting enhancements, making it easier for you to develop, build, compile, run and test data models. Check out the some of the features below to learn more:


| Feature  |  Info | Available in the IDE  |
|---|---|:---:|
| **File state indicators**  |  Ability to see when changes or actions have been made to the file. The indicators **M, U,** and **•** appear to the right of your file or folder name and indicate the actions performed: <br /> <br /> - Unsaved **(•)** &mdash; The IDE detects unsaved changes to your file/folder<br /> - Modification **(M)** &mdash; The IDE detects a modification of existing files/folders<br /> - Untracked **(U)** &mdash; The IDE detects changes made to new files or renamed files | ✅ |
| **Build, test, and run code**  | Build, test, and run your project with a button click or by using the Cloud IDE command bar.  | ✅ |
| **Drag and drop**  | Drag and drop files located in the file explorer, and use the file breadcrumb on the top of the IDE for quick, linear navigation. Access adjacent files in the same file by right clicking on the breadcrumb file.  | ✅ |
| **Organize tabs**  | You can move your tabs around to reorganize your work in the IDE. You can also right click on a tab to view and select a list of actions to take.  | ✅  |
| **Multiple selections**  | You can make multiple selections for small and simultaneous edits. The below commands are a common way to add more cursors and allow you to insert cursors below or above with ease.<br /><br /> - Option-Command-Down arrow<br /> - Option-Command-Up arrow<br /> - Press Option and click on an area  |  ✅ |
| **Formatting** | Format your files with a click of a button, powered by [sqlfmt](http://sqlfmt.com/). | _Coming soon &mdash; November 2022_  |
| **Git diff view**  | Ability to see what has been changed in a file before you make a pull request.  | _Coming soon &mdash; November 2022_  |
| **dbt autocomplete**  |  There are four new types of autocomplete features to help you develop faster:<br />  - Use `ref` to autocomplete your model names<br /> - Use `source` to autocomplete your source name + table name<br /> - Use `macro` to autocomplete your arguments<br /> - Use `env var` to autocomplete env var  |  _Coming soon &mdash; November 2022_   |
| **Dark mode**  | Use dark mode in the Cloud IDE for a great viewing experience in low-light environments. | _Coming soon &mdash; November 2022_    |

**Note**: Cloud IDE beta users may have these features made available earlier.



## Related docs

- [dbt Cloud tips](/docs/get-started/dbt-cloud-tips)
- [Develop in the Cloud](docs/get-started/develop-in-the-cloud)
- [Guides](/docs/get-started/getting-started/overview)
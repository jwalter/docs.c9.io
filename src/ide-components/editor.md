Author: Daniela Gavidia

## The Editor

Cloud9 IDE can be thought of as being divided in the following components:

![IDE Components](./images/editorNaming.png)

Throughout the documentation, we'll refer to these sections by name. We can identify six distinct areas in the editor:

* The top menu bar is the uppermost area, with easy access to a variety of menus
* The project bar on the left lets you manipulate various aspects of your project, including its active files, preferences, and choices for deployment
* The panel displays views according to what's been selected in the project bar
* The toolbar is on the far right, where you can find tools to check the call stack, monitor variables, and breakpoints. This is only activated when [debugging your code](./running_and_debugging_your_code.html).
* The code editor is the main area where you write your code.
* The console is the bottom area of the window. It's an expandable area that can act like a desktop terminal to enter command line input (like `ls` or `mkdir`). It also displays output provided by your program's print statements (like `console.log()`), as well as providing an area for search results

The [Project Bar](./project_bar.html), [Tool Bar](./toolbar.html), and [Console](./console.html) are powerful features, so their documentation is provided separately. We'll talk about the rest of the editor below:

### The Top Menu Bar

![A screenshot of the top menu bar](./images/topMenuBar.png)

In this section, you can find the usual menus for creating and saving files, changing your view, [applying a new theme for the editor](./applying_themes.html), and switching between windows.

In the middle of the menu bar you'll find the **debug** button: ![The debug button](./icons/debugButton.png). For more information, see [the section on "Running and Debugging Your Code".](./running_and_debugging_your_code.html).

The preview button ![The preview button](./icons/previewButton.png) provides you with a look at what the currently active file would look like in the browser. For HTML files, it actual renders the markup into a real page. For mose other files, it provides plaintext view of the source code.

On the far right of the menu, near the Cloud9 IDE logo, there are two more icons: one to return to [the dashboard](./dashboard.html), and one to return to the Cloud9 IDE homepage.

### The Code Editor

This is where most of the action happens. Every file you open appears here as a tab. You can open a new file easily by clicking on the ![Tab add icon](./icons/tabPlusIcon.png) button to the right of the last tab. Cloud9 IDE offers syntax highlighting and basic code completion for most popular programming languages.

The code editor supports a large number of keyboard shortcuts to increase your productivity. For an up-to-date list of these within the IDE, simply go to **Help | Keyboard Shortcuts**.

If you hover over to the upper-right corner, you can [activate zen-mode](./zen_mode.html), which is a full screen coding environment. 

At the lower-right corner, you can find [the status bar](./status_bar.html).
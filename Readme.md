Angular - Front-end JavaScript Framework and Collection of tools(CLI, Debugging Tools, IDE Plugins).

Why framework?

- Simplifies the process of building complex, interactive web user interface
- Write Declarative code.
- Separation of concerns via components
- Object-oriented programming concepts & principles
- Uses Typescript

With JavaScript you write imperative code!

Imperative Code:

Step-by-step instructions(in code) that tell the browser what to do

Example:

1. Find the DOM element & store in variable
2. Add event listener to element
3. In triggered function: Find another element
4. Set CSS visibility of that element to 0
5. Create a new <p> DOM element
6. Set text content of <p> to "Hello World!"
7. Find element into which the <p> should be inserted
8. Insert <p> element

With Angular you write declarative code!

Define the target UI States & how they change and let Angular do the rest

Example:

1. Manage "activeTab" state property
2. Depending on "activeTab", show different content
3. Change "activeTab" upon click on tab element

Why Components?

- Modular Applications:

  - Break up complex applications into simple building blocks
  - Split up responsibilities & concerns
  - Build a component once and re-use it as often as needed

- Better Development Process
  - Assign different team members to different components
  - Share components & logic across the team
  - Reduce dependencies

Easier Development with TypeScript

- With Typescript, you can often catch errors early on during development

//Zone Js

- When evers events occurs like user clicks the button or timer expired, Zone js automatically checks the whole application from top to bottom, whether any changes occured. If any changes occured, It checks with template whether the different appropriate to the changed value, Angular will update the view.

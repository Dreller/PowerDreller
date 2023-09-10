# Power Dreller Component Library
> This is a Component Library for Power Apps Canvas Applications.

## Important references
[Code components for canvas apps](https://learn.microsoft.com/en-us/power-apps/developer/component-framework/component-framework-for-canvas-apps)<br>
[Use Git version control to edit canvas apps (__experimental__)](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/git-version-control)

## How to _install_ the Library
You can _install_ this Library in your own Power Platform environment with these simple steps.
1. In Power Apps, click on "Component libraries" tab and, in the top bar, "New component library".
2. Give a temporary name to the library (it doesn't matter, it will be overriden).  Click on Create.
3. In the App Settings, enable _Show the Git version control setting_, under _Experimental_ in the _Upcoming features_ blade.  A new _Git version control_ blade will be added.
4. In the _Git version control_ blade, click on Connect.
5. Fill the prompts anc click Apply.
    - Git repository URL: HTTPS Link to your own Git Repository,
    - Branch: Name of the branch you have set in your own Git Repository,
    - Directory name: "app"
6. Enter your credentials (Git User Name and Personal Access Token[^1]).  The code should be loaded as a Component Library within your Power Platform Environment.

[^1]: Personal Access Token (PAT) can be generated in your Git Settings, under the _Developer_ blade.

## How to _use_ the Library
1. In a Power Apps Application, in the most left panel, click on the "+" (Insert icon), right under the _Tree view_ icon.
2. At the bottom of the panel, click on "Get more components".
3. A panel open on the right side.  Click on "Select all" for "PowerDreller", or, expand the section and select Components you wish to add to your app.
4. Click Import.

Voilà, you can drag the Component on your screen and use it as explained in the component's section.

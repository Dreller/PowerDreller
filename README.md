# Power Dreller Component Library

Power Apps is an impressive platform, but let's be honest, it's not easy to make a good-looking application using ootb controls.
This [Component Library](https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/component-library) contains a set of components to help you, making nice applications, in no time.

## Color Palette
Build a tailored Color Palette from a single [Hex Color Code](https://www.w3schools.com/colors/colors_picker.asp).  
The Component generates a set of 4 standard colors: 
1. **Main**: Main (accent) color for your app; path: `Component.Colors.main`,
2. **Alternate**: (light) Subtle color, less bold than the Main color; path: `Component.Colors.alt`,
3. **Tertiary**: (dark) Strong and darker version of the Main color; path: `Component.Colors.ter`,
4. **Background**: (very light) Very faded version of the Main color, to use as backgrounds; path: `Component.Colors.back`.

Once you have called the Component's `Create()` Action, you can refer the color palette in two ways:
- For smaller apps, directly refer to the component: `Component.Colors.main.Color`,
- For bigger apps, you might want to store the palette in a static variable `Set( Palette, Component.Colors );`  and call that variable instead of calling the component itself.

[More details on the Wiki Page](https://github.com/Dreller/PowerDreller/wiki/Color-Palette)

---

### Wiki Articles
- [How to get the Library and use it in your apps](https://github.com/Dreller/PowerDreller/wiki/Get-the-Library)

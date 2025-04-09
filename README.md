# Learn more
[Introduction \| RimGui](https://gridrand.com/rimgui/docs/introduction)

# Introduction  
RimGui is a high-performance, lightweight GUI library that supports Built-in Render Pipeline, URP, and HDRP.

It enables easy creation of user interfaces, and can be integrated not only into debugging tools but also into actual gameplay.

To draw a button, all you need is the following code:
```csharp
if (Gui.Button())
{
    // Action when pressed
}
```

Unlike libraries such as uGUI or UI Toolkit, RimGui is an **Immediate Mode GUI** library.

To learn more about Immediate Mode GUI, refer to:  
[Unity - Manual: Immediate Mode GUI (IMGUI)](https://docs.unity3d.com/2021.3/Documentation/Manual/GUIScriptingGuide.html)  
While Unity IMGUI is mainly intended for *in-game debugging and tools*, RimGui is suitable for actual in-game use as well.

However, it’s not designed for GUIs with flashy visual effects — it’s best suited for games that require a clean and simple interface.  
If you need a simple GUI, RimGui can be used as an alternative to UI Toolkit or uGUI.

---

# Goals
- Easy-to-use GUI library
- Rapid UI creation
- Simplicity
- High performance
- Usable not only for debugging and tools but also in actual games
- Minimal dependencies

---

# Non-goals
- Support for GUIs with heavy visual effects  

---

# Features  
- Box  
- Button  
- ToggleButton  
- RadioButton  
- CheckBox  
- Color  
- Dropdown  
- Foldout  
- InputText  
- Label  
- ListView  
- Scroll  
- Separator  
- SlidePad  
- Slider  
- Sprite  
- Splitter  
- Tab  
- Text  
- Texture  
- Tree  
- Window  
- Drag and Drop  
...and many more.

# Support
If you have any bugs or feature requests, please submit them via [this page](https://github.com/Gridrand/RimGui/issues).
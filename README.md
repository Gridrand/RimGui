# Introduction  
**RimGui** is an easy-to-use code-driven GUI library designed for rapid iteration. 
Build user interfaces quickly and efficiently with minimal code. It's perfect not only for debugging tools but also for integrating smooth and responsive UI into actual gameplay.

Works with all Unity versions 2021+ including 2021, 2022, 2023 & Unity 6.

**Render Pipeline Support**  
- Supports Built-in Render Pipeline, URP, and HDRP.

**Customizable**  
- Easily tweak various parameters to fit your needs.  
- You can also create custom widgets from scratch.

**Cross-platform Support**  
- Works not only on PC but also on WebGL and mobile platforms.

**Font Support**  
- Supports custom fonts and texture atlas generation.

**High-Performance Immediate Mode GUI (ImGui)**
- Designed for high performance, with efforts to minimize GC (Garbage Collection) allocation.

**Targets both developers and end-users:**
- RimGui targets not only developers but also **user interfaces for players enjoying the game.**

**Flexible Scalability:**
- You can easily change the size and scale of UI widgets, making it **simple to support multiple resolutions.** This enables optimal UI display across various screen sizes.


It's not designed for GUIs that require flashy effects, but it's perfect if you need a simple and clean interface.
If you are seeking a simple GUI, RimGui could be a useful alternative to UI Toolkit or uGUI.

# Example Code

```csharp
Gui.Heading("Sample");
Gui.LabelSlider("Slider", ref value, 0, 100);
if (Gui.Button("Increment"))
    value++;
```
The following UI is displayed by the code above.

![sample-ui](sample-ui.png)


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
- ColorPicker
- Custom
- Dropdown  
- Foldout  
- Frame
- InputText  
- Label  
  - LabelText, LabelInput, LabelNumeric, and more
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

# Differences Between Unity IMGUI and RimGui

- **Targets both developers and end-users:** While Unity IMGUI is primarily for developer tools, RimGui targets not only developers but also **user interfaces for players enjoying the game.**
- **High-Performance Design:** RimGui is designed for high performance, including efforts to **minimize GC (Garbage Collection) allocation.**
- **Modern Rendering Pipeline Compatibility:** RimGui is compatible with the **URP (Universal Render Pipeline) and HDRP (High Definition Render Pipeline)**, enables seamless integration with the latest Unity projects.
- **Wide Platform Support:** RimGui supports a diverse range of platforms, including **PC, Mobile, and WebGL**, allowing you to **target your desired environments without limitations.**
- **Flexible Scalability:** With RimGui, you can easily change the size and scale of UI elements, making it **simple to support multiple resolutions.** This enables optimal UI display across various screen sizes.

# Links
[AssetStore Page](https://assetstore.unity.com/packages/slug/316805)
[Demo](https://gridrand.com/rimgui/WebGL)
[Github](https://github.com/Gridrand/RimGui)
[Introduction \| RimGui](https://gridrand.com/rimgui/docs/introduction)
[Unity Discussions](https://discussions.unity.com/t/released-rimgui-code-driven-gui/1637582)

# Support
If you have any bugs or feature requests, please submit them via [this page](https://github.com/Gridrand/RimGui/issues).
For direct support, you can reach us at **support [at] gridrand [dot] com**.
You are also welcome to post questions or feedback on the [Unity Discussions](https://discussions.unity.com/t/released-rimgui-code-driven-gui/1637582) thread.
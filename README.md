|  | Project |
| ------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- |
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.svg)](http://nuget.org/packages/Dirkster.AvalonDock)                                      | AvalonDock                        |
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.Expression.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Expression)  | AvalonDock.Themes.Expression      |
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.Metro.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.Metro)            | AvalonDock.Themes.Metro           |
| [![NuGet](https://img.shields.io/nuget/dt/Dirkster.AvalonDock.Themes.VS2013.svg)](http://nuget.org/packages/Dirkster.AvalonDock.Themes.VS2013)          | Dirkster.AvalonDock.Themes.VS2013 |

## Master Branch
[![Build status](https://ci.appveyor.com/api/projects/status/kq2wyupx5hm7fok2/branch/master?svg=true)](https://ci.appveyor.com/project/Dirkster99/avalondock/branch/master)[![Release](https://img.shields.io/github/release/Dirkster99/avalondock.svg)](https://github.com/Dirkster99/avalondock/releases/latest)&nbsp;[Continues Integration](https://ci.appveyor.com/project/Dirkster99/AvalonDock/build/artifacts)

# AvalonDock

Support this project with a :star: -report an issue, or even better, place a pull request :mailbox: :blush:

My IDE called <a href="https://dirkster99.github.io/Edi/">Edi</a> is powered by this project.

AvalonDock is a WPF Document and Tool Window layout container that is used to arrange documents
and tool windows in similar ways than many well known IDEs, such as, Eclipse, Visual Studio,
PhotoShop and so forth. Here are some CodeProject articles:

* [AvalonDock [2.0] Tutorial Part 1 - Adding a Tool Window](https://www.codeproject.com/Articles/483507/AvalonDock-Tutorial-Part-Adding-a-Tool-Windo)
* [AvalonDock [2.0] Tutorial Part 2 - Adding a Start Page](https://www.codeproject.com/Articles/483533/AvalonDock-Tutorial-Part-Adding-a-Start-Page)
* [AvalonDock [2.0] Tutorial Part 3 - AvalonEdit in AvalonDock](https://www.codeproject.com/Articles/570313/AvalonDock-Tutorial-Part-AvalonEdit-in-Avalo)
* [AvalonDock [2.0] Tutorial Part 4 - Integrating AvalonEdit Options](https://www.codeproject.com/Articles/570324/AvalonDock-Tutorial-Part-Integrating-AvalonE)
* [AvalonDock [2.0] Tutorial Part 5 - Load/Save Layout with De-Referenced DockingManager](https://www.codeproject.com/Articles/719143/AvalonDock-Tutorial-Part-Load-Save-Layout)

This repository contains **additional bug fixes and a feature added** fork from:
https://github.com/xceedsoftware/wpftoolkit

Be sure to checkout the <a href="https://github.com/Dirkster99/AvalonDock/wiki">Wiki for more details</a>. The repository also contains a Log4Net branch for debugging interactive issues with a close enough branch. There are also Log4Net demo executables in the 3.4.01 (or later) realease for additional debugging fun.

# Feature Added - Dark and Light VS 2013 Theme

Please review the <a href="https://github.com/Dirkster99/AvalonDock/wiki">Project Wiki</a> to see more demo screenshots.
All screenshots below are from the <a href="https://github.com/Dirkster99/MLib">MLib</a> based VS 2013 Dark (Accent Color Gold)/Light (Accent Color Blue) theme on Windows 10. Similar theming results should be possible with other theming libraries since the implementation follow these <a href="https://www.codeproject.com/Articles/1236588/File-System-Controls-in-WPF-Version-III">guidelines</a>.

The Docking Buttons are [defined in XAML](https://github.com/Dirkster99/AvalonDock/wiki/OverlayWindow), which ensures a good looking image on all resolutions, even 4K or 8K, and enables us to color theme consistently with the Window 10 <b>Accent Color</b>.

<table width="100%">
   <tr>
      <td>Description</td>
      <td>Dark</td>
      <td>Light</td>
   </tr>
   <tr>
      <td>Dock Document</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/DockDocument.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/DockDocument.png" width="400"></td>
   </tr>
   <tr>
      <td>Dock Document</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/DockDocument_1.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/DockDocument_1.png" width="400"></td>

   </tr>
   <tr>
      <td>Dock Tool Window</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/DockToolWindow.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/DockToolWindow.png" width="400"></td>
   </tr>
   <tr>
      <td>Document</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/Document.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/Document.png" width="400"></td>
   </tr>
   <tr>
      <td>Tool Window</td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Dark/ToolWindow.png" width="400"></td>
      <td><img src="https://raw.githubusercontent.com/Dirkster99/Docu/master/AvalonDock/VS2013/AD_MLib/Light/ToolWindow.png" width="400"></td>
   </tr>
</table>

## Theming

Using the *Xceed.Wpf.AvalonDock.Themes.VS2013* theme is very easy with *Dark* and *Light* themes.
Just load *Light* or *Dark* brush resources in you resource dictionary to take advantage of existing definitions.

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/Xceed.Wpf.AvalonDock.Themes.VS2013;component/DarkBrushs.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

```XAML
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="/Xceed.Wpf.AvalonDock.Themes.VS2013;component/LightBrushs.xaml" />
    </ResourceDictionary.MergedDictionaries>
```

These definitions do not theme all controls used within this library. You should use a standard theming library, such as:
- [MahApps.Metro](https://github.com/MahApps/MahApps.Metro),
- [MLib](https://github.com/Dirkster99/MLib), or
- [MUI](https://github.com/firstfloorsoftware/mui)

to also theme standard elements, such as, button and textblock etc.

# Mile Stone History

## Patch History for AvalonDock Version 3.5

### Fixed Issue about PanesTemplateSelector being ignored
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1440">#1440</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/fe18e81e9449962ce5e34e7b421f9f016eb4eb84">@Dirkster99</a>
Also Increased to Version 3.5.2.

### Increased to Version 3.5.1
- <a href="https://github.com/Dirkster99/AvalonDock/commit/8cb6565db294ed3fcb2ac502172f059d740f013d">@Dirkster99</a>

### Fixed Close Button Position in Generic Theme
- <a href="https://github.com/xceedsoftware/wpftoolkit/pull/1184/files">#1184</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/11709c6cbfc190e920fc62302b5922d666dbac29">@Dirkster99</a>

### DockingManager: ModelChange event happens before new LayoutDocumentItem is added
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1430">#1430</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/6d23da0ce95236ee77e53238cf60e679a3c8fb0e">@Dirkster99</a>

### Added resource file for AvalonDock for nl-BE
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1424">#1424</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/70995417714f37d84659854245f0caad8e3c6d39">@Dirkster99</a>

### Fixed Crash while loading FLOATING DOCUMENT

Fixed Crash while loading (Deserialize) a layout with FLOATING DOCUMENT window.

NullReferenceException in LayoutDocumentFloatingWindowControl.OnInitialized:
Initialization in 2nd constructor was missing:
   _model = model;
   UpdateThemeResources();
   
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1442">Issue/Resolution is similar to #1442</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/f966d6ced92e658cd50e5505c38f869ebae00fba">@Dirkster99</a>

### Removed unused private field in LayoutAutoHideWindowControl
- <a href="https://github.com/Dirkster99/AvalonDock/commit/c4b60646fc0e2beb166f682a1f0e9b8e0532ec8d">@Dirkster99</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/1304e0c4fad40f2d057858712c3c5be86bf46509">@Dirkster99</a>

### Prevent crash from setting negative size
- <a href="https://github.com/RecursiveNerd/wpftoolkit/commit/38d36f236727cf48ab0e82e9794e1f927d059695">RecursiveNerd/wpftoolkit</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/19a07008cfeb352bba8bf371305e6be83541806d">@Dirkster99</a>

### Fix for issue #1379 as suggested by RecursiveNerd
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1379">#1379</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/f8be3fa041904b2cb9e55299a4497b288b145d00">@Dirkster99</a>

### Update zh-Hans translation #1383
- <a href="https://github.com/xceedsoftware/wpftoolkit/pull/1383/files">#1383</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/f8167d3ab094f65454e702347d50ac5cd1427da2">@Dirkster99</a>

### AvalonDock czech localization #1396
- <a href="https://github.com/xceedsoftware/wpftoolkit/pull/1396/files">#1396</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/c67e8583b596d7deacd0bda79f2448a47b5fc6d7">@Dirkster99</a>

### AvalonDock fixed misspelling when serializing DockMinWidth/DockMinHeight
- <a href="https://github.com/xceedsoftware/wpftoolkit/pull/1212">#1212</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/9230aad671817ef6e48e6b5dc59a98a583fe1bed">@Dirkster99</a>

### Clear Bindings #1360
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1360">#1360</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/33655c686faeded1f4bef8d22da8960a2a101b50">@Dirkster99</a>

### Theming ContextMenuEx in Metro
Re-styling this in AvalonDock since the menu on the drop-down button for more documents is otherwise black
- <a href="http://avalondock.codeplex.com/workitem/15743">http://avalondock.codeplex.com/workitem/15743</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/fd2186e31e34fa2c62dee7d0bd356f86c8f4729a">@Dirkster99</a>

### Drag and Drop on (scaled) 4K display
Drag and Drop of Document or ToolWindow content does not always work on (scaled) 4K display
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1357">#1357</a>
- <a href="https://github.com/Dirkster99/AvalonDock/issues/6">#6</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/86edf83d4232638eb0f5827f4b554dca7990f914">@Dirkster99</a>

### Crash Loading (Deserialized) Floating Tool Window Layout

Fixed Crash while loading (Deserialize) a layout from FLOATING tool window.
NullReferenceException in LayoutAnchorableFloatingWindowControl.OnInitialized

- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1442">#1442</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/f966d6ced92e658cd50e5505c38f869ebae00fba">@Dirkster99</a>

### LayoutRoot doesn't notify change for Children or ChildrenCount #1313
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1313">#1313</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/d65e9a9019867b1019810329727c154cc20b4c90">@Dirkster99</a>

### Fixed height of titles of floating windows #1203
- <a href="https://github.com/xceedsoftware/wpftoolkit/issues/1203">#1203</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/5c22b1ea18a7b5b25b6a9cb328a1b4210474cbea">@Dirkster99</a>

### Initial AvalonDock Version 3.5
- <a href="https://github.com/xceedsoftware/wpftoolkit/tree/73b2e988dea6ea2e64bb11e8783b6bde66219ee1">Taken from this commit</a>
- <a href="https://github.com/Dirkster99/AvalonDock/commit/89823735ab60ab90a84c6cae7c594e9ee7fe858c">@Dirkster99</a>

Please review the <a href="https://github.com/Dirkster99/AvalonDock/wiki/Patch-History">Patch History</a> page for more information on patches for previously released versions of AvalonDock.

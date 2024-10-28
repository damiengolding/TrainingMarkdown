# Development Scaffolding with Code Snippets, Item Templates and Project Templates

## Directory and file locations for snippets and templates

[Designer widget plugins locations](https://doc.qt.io/qt-6/designer-creating-custom-widgets.html)

- Copy the designer widget plugin (usually qscintillaplugin.dll) 
  - For standalone designer, copy to: C:\Qt\Tools\QtCreator\bin\plugins\designer
  - For Qt Creator internal designer, copy to C:\Qt\<QT\_VERSION\>\<BUILD\_KIT\>\plugins\designer

- Copy dependencies to:
  - C:\Qt\<QT\_VERSION\>\<BUILD_KIT\>\bin
  - C:\Qt\Tools\QtCreator\bin
- KDAB instructional videos (playlist)
  - [Qt Designer Plugins](https://www.youtube.com/playlist?list=PL6CJYn40gN6iNg0nIYH4QLhYkfs5PslbA)


[Snippets location](https://doc.qt.io/qtcreator/creator-preferences-text-editor-shippets.html)

- snippets.xml C:\Users\<USER\_NAME\>\AppData\Roaming\QtProject\qtcreator\snippets\snippets.xml

[Custom templates](https://doc.qt.io/qtcreator/creator-project-wizards.html)

- Copy from: C:\Qt\Tools\QtCreator\share\qtcreator\templates\wizards
- Copy to: C:\Users\<USER_NAME\>\AppData\Roaming\QtProject\qtcreator\templates\wizards
- Add keyboard shortcuts for *Inspect* (typically META-'F11') and *Factory.Reset* (typically META-'F12')
- Use Creator with -customwizard-verbose on the command line


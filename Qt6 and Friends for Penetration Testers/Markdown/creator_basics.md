# Qt Creator fundamentals

[(see here for the official manual)](https://doc.qt.io/qtcreator/index.html)

## [Useful Qt Creator keyboard shortcuts](https://doc.qt.io/qtcreator/creator-keyboard-shortcuts.html)
CTRL-'DEL' - toggle code folding

CTRL-'/' - toggle comment

CTRL-'A'-'I' - auto-indent selected text

CTRL-'TAB' - go to previously selected file

F4 - switch from hpp to cpp or back

SHIFT-'F4' - switch to UI file and back

SHIFT-'F2' - switch  between function declaration/definition

CTRL-SHIFT-[UP/DOWN ARROW] - move a selected block of text

CTRL-SHIFT-'B' - build all

CTRL-ALT-'B' - compile current file

ALT-'G'-'C' - git commit

ALT-'ENTER' - list quick fixes

ALT-'ENTER' - list quick fixes; when inheriting abstract base class place cursor next to class name (e.g. class MyClass : public AbstractClass), then select 'Insert Virtual Functions of Base Class'

CTRL-SHIFT-'R' - rename symbol under cursor

ALT-'0' - toggle left pane (usually includes the project explorer)

ALT-SHIFT-'0' - toggle right pane

ALT-'1..9' - toggle tabs on the bottom pane

F1 - context sensitive help; ESC twice to close

CTRL-SHIFT-'V' - shows clipboard stack

CTRL-'M' - toggle bookmark

Use capitals to abbreviate class names and get a list, e.g. QSI gives a drop down including QStandardItem
- Then ALT-'ENTER' for a quick fix to #include the header if not already included

Default quick fix for change to parameter list

## Other Qt Creator features

- Command line options - [See also](https://doc.qt.io/qtcreator/creator-cli.html)
- Sessions
- Plugins

  - Welcome
  - Todo
  - Git
  - clangd

- Window split
- External tools and shortcuts
- Creator variables [See here for a general discussion](https://doc.qt.io/qtcreator/creator-how-to-use-qtc-variables.html)

  - Most useful/most often used:

    - ​    %{ActiveProject:Path} - root path (where your .pro file lives)

    - ​    %{ActiveProjectBuildConfig:Path} - output path for build operations

    - ​    %{ActiveProjectBuildConfig:Type} - e.g. release | debug | profile

    - ​    %{ActiveProject:Name} - name of the current ActiveProject

    - ​    %{UUID} - generate a new UUID

    - ​    %{CPP:LicenceTemplate} - licences template from 'Preferences'

    - ​    %{CurrentDate:Locale} - date in locale specific format (e.g. 04/04/2024)

    - ​    %{CurrentDate:ISO} - date in ISO format (e.g. 2024-04-04)

    - ​    %{CurrentDate:RFC} - date in RFC format (e.g. 04 Apr 2024)

    - ​    %{CurrentTime:Locale} - time in locale specific format (e.g. 12:12)

    - ​    %{CurrentTime:ISO} - time in ISO format (e.g. 12:12:12)

    - ​    %{CurrentTime:RFC} - time in RFC format (same as above)


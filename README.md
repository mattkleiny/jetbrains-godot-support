[![Build Status](https://teamcity.jetbrains.com/app/rest/builds/buildType:(id:NetProductsExtensions_GodotSupport_Build)/statusIcon.svg?guest=1)](https://teamcity.jetbrains.com/viewType.html?buildTypeId=NetProductsExtensions_GodotSupport_Build&guest=1)
 
# Godot Support for IntelliJ

The "Godot Support" plugin adds specific functionality for the [Godot game engine](https://godotengine.org/) to [IntelliJ](https://www.jetbrains.com/intellij/) and other JetBrains IDEs.

# Features

| Feature                                                                | GDScript | C#  | Details                                                                                                                                                                                                                  |
|------------------------------------------------------------------------|----------|-----|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Godot 4.x                                                              | ✔        | ✔   | design ready for future updates                                                                                                                                                                                          |
| Syntax Highlighting                                                    | ✔        | *   | GDScript, scenes, shaders, & resources.                                                                                                                                                                                  |
| Godot GDScript LSP                                                     | ✔        | n/a | LSP from current editor or from headless editor                                                                                                                                                                          |
| Run Configurations                                                     | ✔        | ✔   | Run/Debug, launch editor, and context menu on a scene file allows running game directly to that scene                                                                                                                    |
| Input Action and NodePath completions                                  | ✔        | ✔   | completion in string literals and [more](https://github.com/JetBrains/godot-support/pull/102)                                                                                                                            |
| Godot warnings and quick fixes                                         | ✔        | ✔   | Godot specific warnings and quick fixes, integrated with Roslyn provided ones.                                                                                                                                           |
| External Annotations for Godot Attributes                              | n/a      | ✔   | C# Warning suppression for known Godot idioms                                                                                                                                                                            |
| and More...                                                            |          |     |                                                                                                                                                                                                                          | 

# Recommendations

Add `.idea` to [.gitignore](https://github.com/van800/godot-demo-projects/pull/2/files#diff-a084b794bc0759e7a6b77810e01874f2R22) 

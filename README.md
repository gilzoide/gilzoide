### Hi everybody! =D
I'm Gil and I develop free software with a focus on usability.

<details>
<summary><b>Godot addons</b></summary>

- [Lua GDExtension](https://github.com/gilzoide/lua-gdextension): A native extension for using the Lua language in Godot 4.1.2+
- [Lua PluginScript](https://github.com/gilzoide/godot-lua-pluginscript): a PluginScript for using Lua as a scripting language in Godot 3.X based on LuaJIT
- [Dockable Container](https://github.com/gilzoide/godot-dockable-container): dockable/tiling UI panels Container addon
- [Dispatch Queue](https://github.com/gilzoide/godot-dispatch-queue): threaded and synchronous Dispatch Queues
- [CFFI GDExtension](https://github.com/gilzoide/cffi-gdextension): native extension for calling C functions via libffi in Godot 4.1+
- [Objective-C GDExtension](https://github.com/gilzoide/objectivec-gdextension): experimental native extension for calling Object-C methods at runtime in Godot 4.1+
- [InputKeyEvent Grabber](https://github.com/gilzoide/godot-input-key-event-grabber): editor plugin with a button that grabs key events and populates an `InputEventKey` instance, great for creating `ShortCut` resources
- [FixedCellGridContainer](https://github.com/gilzoide/godot-fixed-cell-grid-container): simple grid Container with fixed size cells
- [Cubic Bézier Controls](https://github.com/gilzoide/godot-cubic-bezier-controls): bubic Bézier curve Resource and Controls for visualizing and editing them
</details>

<details>
<summary><b>Unity packages</b></summary>

- [Easy Project Settings](https://github.com/gilzoide/unity-easy-project-settings): easily create custom Project Settings by adding the `[ProjectSettings]` attribute to your `ScriptableObject` subclass
- [Flex UI](https://github.com/gilzoide/unity-flex-ui): Flexbox layout support for Unity UI using the Yoga layout engine
- [Cloud Save](https://github.com/gilzoide/unity-cloud-save): Cloud Save common interface with implementations for Apple Game Center and Google Play Games
- [Camera Viewport Rect](https://github.com/gilzoide/unity-camera-viewport-rect): automatically setup `Camera` viewports from `RectTransform`s
- [Gesture Recognizers](https://github.com/gilzoide/unity-gesture-recognizers): touch/pointer gesture recognizer scripts based on `EventSystem` handlers or `Input` (Tap/Multitap, Long Press, Pan, Pinch, Twist, Swipe, Edge Pan)
- [Update Manager](https://github.com/gilzoide/unity-update-manager): simple to use Update Manager pattern + Jobified Update for MonoBehaviours and pure C# classes alike
- [SQLite-net](https://github.com/gilzoide/unity-sqlite-net): SQLite-net for Unity, supports Windows, Linux, macOS, iOS, tvOS, visionOS, Android and WebGL
- [SQLite Asset](https://github.com/gilzoide/unity-sqlite-asset): read-only SQLite database assets for Unity with ScriptedImporters for ".sqlite", ".sqlite2" and ".sqlite3" files
- [SQLite Asset - CSV](https://github.com/gilzoide/unity-sqlite-asset-csv): easily import ".csv" files as read-only SQLite database assets in Unity
- [Key-Value Store for Unity](https://github.com/gilzoide/unity-key-value-store): Key-Value Store save system interface and implementations for Unity
- [Texture Apply Async](https://github.com/gilzoide/unity-texture-apply-async): alternative to Texture2D.Apply() that doesn't require synchronizing with the render thread, avoiding stalls in the main thread
- [Conditional Objects](https://github.com/gilzoide/unity-conditional-objects): modify `GameObject`s and `Component`s at Prefab/Scene import time, based on build configurations
- [Prefab Pool](https://github.com/gilzoide/unity-prefab-pool): Prefab instance pool that is configurable in the Inspector, supports any engine Object type and is available as a serializable C# class, MonoBehaviour and ScriptableObject
- [Back Button Stack](https://github.com/gilzoide/unity-back-button-stack): easily manage a stack of objects that respond to the ESC button / Android Back button
- [Safe Area Layout](https://github.com/gilzoide/unity-safe-area-layout): uGUI layout group that makes children respect the Safe Area
- [Gradle Wrapper](https://github.com/gilzoide/unity-gradle-wrapper): automatically generate Gradle Wrapper (gradlew) when exporting Android projects
- [Serializable Collections](https://github.com/gilzoide/unity-serializable-collections): serializable versions of `Dictionary`, `HashSet` and `KeyValuePair` for Unity 2020.1+
- [Gradient Rect](https://github.com/gilzoide/unity-gradient-rect): Unity UI component that generates meshes using `Gradient`s
- [Rounded Corners](https://github.com/gilzoide/unity-rounded-corners): Unity UI component that generates meshes with rounded corners
- [Lottie Player](https://github.com/gilzoide/unity-lottie-player): player for Lottie animations, powered by rlottie, multithread/Job System-friendly
- [F# for Unity](https://github.com/gilzoide/unity-fsharp): F# scripting in Unity with automatic compilation
- [Managed Jobs](https://github.com/gilzoide/unity-managed-jobs): use classes and other managed types with Unity's Job System
- [Main Thread Task](https://github.com/gilzoide/unity-main-thread-task): `Task`/`UniTask`-based Main Thread dispatcher classes, no `GameObjects` involved
- [TaskFactoryObject](https://github.com/gilzoide/TaskFactoryObject): `TaskFactory` Unity objects plus a collection of `TaskScheduler`s with optional limited concurrency
- [Non-alloc Enumeration](https://github.com/gilzoide/unity-non-alloc-enumeration): non-alloc enumerables for Unity structures and C# IList/IReadOnlyList
- [Native Collections Stream](https://github.com/gilzoide/unity-native-collections-stream): Stream, TextReader and TextWriter implementations backed by Unity Native Collections
- [Scene Reference](https://github.com/gilzoide/unity-scene-reference): autogenerated ScriptableObjects that are stable references to the scenes configured in Build Settings
- [Asset List](https://github.com/gilzoide/AssetList): `ScriptableObject` that automatically aggregates assets using `AssetDatabase.FindAssets`
- [PlayerLoop Helper](https://github.com/gilzoide/unity-playerloophelper): single file helper class for registering/unregistering systems in Unity's PlayerLoop
</details>

<details>
<summary><b>Lua modules</b></summary>

- [molde](https://github.com/gilzoide/molde): zero dependency, single file template engine for Lua 5.1+ with builtin sandbox support
- [stringstream](https://github.com/gilzoide/stringstream-lua): object that loads chunks of strings on demand compatible with a subset of the Lua string API suitable for parsing
- [wildcard_pattern](https://github.com/gilzoide/wildcard_pattern-lua): use shell-like wildcards as Lua string patterns with support for importing gitignore-like file content
- [argmatcher](https://github.com/gilzoide/argmatcher): simple command line argument matcher for Lua
- [nested](https://github.com/gilzoide/nested): generic nested data structure file format, where data is formed by nested lists with both sequential data and key-value paired data
</details>

<details>
<summary><b>C/C++ libraries</b></summary>

- [flyweight.hpp](https://github.com/gilzoide/flyweight.hpp): single header implementation of the Flyweight design pattern for C++11
- [SQLiteVfs.hpp](https://github.com/gilzoide/sqlite-vfs-cpp): single header with classes for easily implementing SQLite VFS shims in C++
- [cdedent](https://github.com/gilzoide/cdedent): pure C implementation of Python's textwrap.dedent, with C++ wrappers.
- [pega-texto](https://github.com/gilzoide/pega-texto): Parsing Expression Grammars (PEG) runtime engine for C
</details>

<details>
<summary><b>D libraries</b></summary>

- [bettercmath](https://github.com/gilzoide/bettercmath): -betterC compatible 3D math library for D
- [betterclist](https://github.com/gilzoide/betterclist): -betterC compatible dynamic list backed by array for D
- [flyweightbyid](https://github.com/gilzoide/flyweightbyid): -betterC compatible Flyweight template based on explicit named ids for D
- [soa](https://github.com/gilzoide/soa-d): -betterC compatible Struct Of Arrays template for D
</details>

I'm also a musician and have [some songs recorded](https://soundcloud.com/gilzoide/) 🎵

Feel free to reach me about anything at all! ^^

[![Donate using Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/gilzoide/donate)
[![Buy me a coffee on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/O4O73OS4E)

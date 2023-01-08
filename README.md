# Godot Test with C++ and CMake

Sources:

- [https://thatonegamedev.com/cpp/godot-native-using-cmake/](https://thatonegamedev.com/cpp/godot-native-using-cmake/)
- [https://docs.godotengine.org/en/3.5/tutorials/scripting/gdnative/gdnative_cpp_example.html#doc-gdnative-cpp-example](https://docs.godotengine.org/en/3.5/tutorials/scripting/gdnative/gdnative_cpp_example.html#doc-gdnative-cpp-example)

---

## Clone the respository

You must clone this repository *recursively* in order to get *godot C++ headers*

```bash
git clone git@github.com:jacogasp/godot-game-template.git --recurse-submodules
```

## Configure

Go to `CoreGame` directory and make a new directory `.cmake`

```bash
cd godot-game-template/CoreGame`
mkdir .cmake
```

and configure with

```bash
cd .cmake
cmake ..
```

## Build

To build, within the `.cmake` folder run

```bash
cmake --build . -j6
```

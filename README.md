# VS_DBG VS Code Debug Example

## Two ways

First of all, set a `Breakpoint` in [test_lib.cc](test_lib/test_lib.cc) on line 7.

- Using extension - Microsoft's `CMake Tools`.
  1. Click the `CMake` icon in the left `Activity Bar`.
  2. Unfold `vs_dbg`, right click on `test_dbg`,and choose `Debug`.
- Using [.vscode/launch.json](.vscode/launch.json).
  1. Click the `Debug and Run (Ctrl+Shift+D)` icon in the left `Activity Bar`.
  2. Click the top green triangle to `Start Debugging`.


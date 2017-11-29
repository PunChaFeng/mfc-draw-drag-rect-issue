# mfc-draw-drag-rect-issue
A simple MFC app to reproduce MFC CDC::DrawDragRect() issue on Win10, version 1709, build 16299.64.

## Reproduce steps
1. Download the compiled executable file here. (you can also compile it by yourself, see How to compile section)
1. Launch the executable.
1. Click the dialog and drag (not the title bar).

It works well on Win10 version prior to version 1709. But on Win10 version 1709, you will see lots of unexpected "lines" during the mouse move, like this:


## How to Compile
1. Open the visual studio solution file, MFCApplication1.sln with Visual Studio 2017.
1. Compile the solution.

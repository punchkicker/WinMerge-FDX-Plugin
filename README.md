# WinMerge-FDX-Plugin
WinMerge plugin to unpack Final Draft (.fdx) files for comparison. It extracts the screenplay content into a formatted, readable plain text file, allowing WinMerge to directly compare .fdx files without needing to export them to text first.

TO USE:

1. Copy the UnpackFDX.sct file into the 'MergePlugins' folder in the WinMerge installation location. (Typically C:\Program Files\WinMerge\MergePlugins).
2. Restart WinMerge.
3. Enable automatic unpacking ('Plugins → Automatic Unpacking')
4. Drag in your FDX files to compare.
   
Note: The PackFile function is currently empty, so any changes made within WinMerge cannot be saved back to the original FDX files.

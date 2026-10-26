Rocky RAW Studio - Native Desktop Window Edition

This edition uses pywebview to open a separate Windows application window instead of a Chrome tab.

To build without Python on your own PC:
1. Upload extracted files to your GitHub repository. Preserve .github/workflows/build-windows-exe.yml.
2. Actions > Build Rocky RAW Studio Desktop EXE > Run workflow.
3. Download artifact Rocky-RAW-Studio-Desktop-Windows.
4. Extract and launch Rocky_RAW_Studio_Desktop.exe.

Windows WebView2 runtime may be required (usually installed on Windows 11). No separate Python installation needed for running the EXE.

Not tested on Windows in this environment. Always test with sample files before using for client jobs.

# GIArguments
Genshin Impact UnityPlayer arguments  
Some of them are `Editor arguments` and thus not valid in start process arguments

|Arguments|Argument|Description|
|-|-|-|
|**-adapter**|N|Allows the game to run full-screen on another display. The N maps to a Direct3D display adaptor. In most cases there is a one-to-one relationship between adapters and video cards. On cards that support multi-head (that is, they can drive multiple monitors from a single card) each “head” may be its own adapter.|
|-automated|||
|**-batchmode**||Run the application in “headless” mode. In this mode, the application doesn’t display anything or accept user input. This is useful for running servers for networked applications.|
|-connectserver|||
|-crashWhenShaderCompilerLaunchFail|||
|-distributeShaderCompiler|||
|**-force-clamped**||Used together with -force-glcoreXY, this prevents checking for additional OpenGL extensions, allowing it to run between platforms with the same code paths.|
|**-force-d3d11-no-singlethreaded**||Force DirectX 11.0 to be created without a D3D11_CREATE_DEVICE_SINGLETHREADED flag.|
|**-force-d3d11**||Force the game to use Direct3D 11 for rendering.|
|-force-d3d11-nothreads|||
|-force-driver-type-warp||Force the DirectX 11.0 driver type WARP device. For more information, see Microsoft’s documentation on Windows Advanced Rasterization Platform|
|***-force-feature-level-10-0***||Force DirectX 11.0 feature level 10.0.|
|***-force-feature-level-10-1***||Force DirectX 11.0 feature level 10.1.|
|***-force-feature-level-11-0***||Force DirectX 11.0 feature level 11.0.|
|-force-feature-level-11-1|||
|**-force-gfx-direct**||Force single threaded rendering.|
|-force-gfx-st|||
|-force-gfx-mt|||
|-force-gfx-jobs|<native\|legacy>||
|**-force-glcore**||Force the application to use the OpenGL core profile for rendering. The Editor tries to use the most recent OpenGL version available, and all OpenGL extensions exposed by the OpenGL drivers. Unity uses Direct3D if the platform doesn’t support OpenGL.|
|**-force-glcoreXY**|XY:<32\|33\|40\|41\|42\|43\|44\|45>|Similar to -force-glcore, but requests a specific OpenGL context version. Accepted values for XY: 32, 33, 40, 41, 42, 43, 44, or 45.|
|**-force-gles**||Make the Editor use OpenGL for Embedded Systems for rendering. The Editor tries to use the best OpenGL ES version available, and all OpenGL ES extensions exposed by the OpenGL drivers.|
|**-force-glesXY**|XY:<20\|30\|31\|31eap>|Similar to -force-gles, but requests a specific OpenGL ES context version. Accepted values for XY: 30, 31 or 32.|
|-force-opengl|||
|-gpu|||
|-mihoyoBuildBundle|||
|***-monitor***|N||
|-multidisplay|||
|**-nographics**||-nographics requires -batchmode|
|**-nolog**||Do not produce an output log. Normally output_log.txt is written in the *_Data folder next to the game executable, where Debug.Log output is printed.|
|-no-dialogs|||
|-parallelBuildBundle|||
|-parentHWND|HWND|Embed the Windows Standalone application into another application. When using this, you need to pass the parent application’s window handle (‘HWND’) to the Windows Standalone application. When passing -parentHWND 'HWND' delayed, the Unity application is hidden while it is running. You must also call SetParent from the Microsoft Developer library for Unity in the application. Microsoft’s SetParent embeds the Unity window. When it creates Unity processes, the Unity window respects the position and size provided as part of the Microsoft’s STARTUPINFO structure. To resize the Unity window, check its GWLP_USERDATA in Microsoft’s GetWindowLongPtr function. Its lowest bit is set to 1 when graphics have been initialized and it’s safe to resize. Its second lowest bit is set to 1 after the Unity splash screen has finished displaying.
For more information, see this example: EmbeddedWindow.zip|
|**-password**|||
|**-popupwindow**||Create the window as a a pop-up window, without a frame.|
|**-runEditorTests**|||
|-runTests|||
|**-screen-fullscreen**||Override the default full-screen state. This must be 0 or 1.|
|**-screen-height**||Override the default screen height. This must be an integer from a supported resolution.|
|**-screen-quality**||Override the default screen quality. Example usage would be: /path/to/myGame -screen-quality Beautiful|
|**-screen-width**||Override the default screen width. This must be an integer from a supported resolution.|
|**-serial**|||
|**-show-screen-selector**||Forces the screen selector dialog to be shown.|
|**-silent-crashes**|||
|**-single-instance**||Allow only one instance of the game to run at the time. If another instance is already running then launching it again with -single-instance focuses the existing one.|
|**-stackTraceLogType**|<None\|ScriptOnly\|Full>||
|-useShaderCacheServer|||
|-useShaderCacheServerRead|||
|-useShaderCacheServerWrite|||
|***-window-mode***|<exclusive\|borderless>||

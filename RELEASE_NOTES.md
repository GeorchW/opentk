### 4.0.0-pre3
 * Build System improvements to fully automatic pipeline.

### 4.0.0-pre2
 * Test and fix build system
 * Fix package metadata

### 4.0.0-pre
 Key Changes:
 * Added support for .Net Core
 * Removed all platform-specific backends.
 * Brand new GLFW-based windowing system.
 * Brand new GLFW-based input system.
 * Math library performance improvements and fixes.
 * Changed root namespace to OpenToolkit for future Xamarin compatibility - (https://github.com/mono/opentk/issues/19)

Note:
- 4.0.0-pre does not include any version of openAl, as that still depends on ADL

OpenTK 4.x is entirely MIT licensed and does not use ADL.

Full Log:
* Change: Make Command a valid modifier on OS-X #759
 * Splitting Platform/Windows/API.cs into OpenTK.NT #765
 * Immediately return after restoring resolution #766
 * Fix OpenTK.Mathematics assembly name #768
 * [4.0] Implement 'unmanaged' constraint #771 
 * Close display connection for X11 on dispose #773
 * [4.0] Fix StyleCop analysis not working on Windows #775
 * Fixed incorrect Quaternion/Vector rotation #777
 * [4.0] Build Cleanup #778
 * Fixed type for VertexAttribPointer #779
 * [4.0] Fix numerous binder errors #781
 * Fix #USE_SDL2_GAMECONTROLLER code path #782
 * [4.0] Refactor Generator.Rewrite #783
 * [4.0] Fix two typos in CONTRIBUTING.md #785
 * Add common.props for use in all projects #786
 * [4.0] Auto-update OpenTK.sln (done by VS2017) #787
 * Add missing build configs (VS2017) #788
 * Fixed OpenGL 3.2+ Context Creation (Mixed up Profile Mask / Flags) #790
 * [4.0] Create new .sln file for all new projects #791
 * [4.0] Fix CI scripts #792
 * [4.0] Fix general StyleCop errors #793
 * [4.0] Some more small rewriter changes #794
 * [4.0] Refactor Generator.Bind#795
 * [4.0] Get CI to succeed #796
 * Fix: Custom cursors not working under OS-X and dotnet #797
 * [4.0] Fix stylecop errors in OpenTK.Mathematics.#798
 * Fix OpenTK.NT compilation errors #799
 * [4.0] Fix OpenTK.AL compilation errors #800 
 * 4.0 #802
 * Fix csproj references to target netstandard2.0 instead of net461. #803
 * Style guide#804
 * [4.0] Integrate OpenTK.OpenAL#805
 * [4.0] refactored .Math stylecop errors #806
 * Use props/ directory directly #813
 * Add #814 to 4.0 #815
 * Fix document typo #818
 * Binder Docs + Performance#826
 * [4.0] Embedded license handling for binding generator #836
 * [4.0] Adding directory safety to the binder. #837
 * Update README after branch changes #839
 * [4.0] Add StructLayout to Color4#840
 * [4.0] Change root namespace to OpenToolkit #842
 * Fix the aftermath of merging #842 #843
 * [4.0] Impliment Vectord * Quaterniond #844
 * Fix aftermath of #842 #846
 * [4.0] Minor edits to README.md #848
 * [4.0] Update SDL2 version check #849
 * [4.0] Remove big chunk of unused code from Quaterniond.cs #852
 * [4.0] Remove GLES 1.0 and 1.1 support #856
 * [4.0] Add explicit operators for Color4/Vector4 conversions #858
 * [4.0] Remove unused code #860
 * [4.0] Begin moving Input to OpenTK.Input#861
 * [4.0] Begin moving Platform to OpenTK.Platform #862
 * [4.0] Add RootNamespace tags to projects#863
 * OpenGL Reimplementation #864
 * Input and Windowing via GLFW #867
 * Bindings generator for modularity and ADL#871
 * Update licensing information #875
 * Update Discord link. #876
 * Optimize Vector4/Color4 conversions with Unsafe.As #877
 * Apply Unsafe.As optimization to all vector types #878
 * Fix discord invite link #881
 * Ignoring MouseMoveEx errors and fall back to passed point. #883
 * Rename license files to avoid confusion. #885
 * Emergency fix in short license terms #887
 * [4.0] Adding Lerp function in the math helper #895
 * System.Math and OpenToolkit.MathHelper symmetry #897
 * Shorten float literals to the actual float value #898
 * Reflect 22/04/2019 development discussion #902
 * Remove obsolete methods within Vector types. #906
 * Add vector types with integer components. #908
 * OpenAL cleanup #909
 * Organise master #912
 * Purity annotations for Math types #915
 * Int vectors in windows #917
 * Box2i support #918
 * add Box3 #919
 * Box2n and Box3n cleanup #920
 * Add API to let users pick OpenGL version #921
 * Add Quaternion to Euler angles conversion #923
 * Fix binder script paths #924
 * Restore unit tests #925
 * Box tests #926
 * GLFW Input. #928
 * Improve EditorConfig file. #929
 * Adds Vulkan related GLFW methods to IGLFW. #930
 * Fixes the binder and makes it 10x faster. #931
 * Add tuple deconstructors and conversions to vector types. #933
 * Fix ToHSV and ToHsl functions generating nan when they shouldn't #934
 * Build System for 4.0 #936
 * Hid input #943
 * Implement ppi in INativeWindow. #945
 * Feature/new Bindings generator #946
 * PlaceholderGL#948
 * Fix Quaternion(euler angle order -> roundtrip tests)#949
 * Fix windowing tests #950
 * chmod +x build.sh #951
 * Fix <LangVersion> getting applied to F# projects. #952
 * Feature/fix box contains #953
 * Test fixes #954
 * Fix PlatformLibraryNameContainerBase on macOS. #962
 * Make GLFW.Image better. #963
 * Default GameWindowSettings.IsSingleThreaded to true. #964
 * Improve mouse cursor handling. #965
 * Fix window icon handling. #966
 * Clean up window events. #967
 * Fix file drop events. #968
 * Fix incorrect type on glfwGetError. #969
 * Move GLFWProvider to Windowing.Desktop. #970
 * Make GLFW structs simpler. #971
 * Clean up window properties/interfaces. #972
 * OpenGL_Bindings.csproj: Call bash instead of sh #974
 * Quaternion(d): Modify instance Invert() to match static functions #975
 * Remove ADL from GLFW. Use DllImport. #976
 * Begin work on merging OpenAL extensions. #986
 * Fix CI system #988
 * GLFW API cleanup. #989
 * Remove reference to Mathematics from GLFW bind. #990
 * Revised boostrap process + update build tools #992
 * Add remaining GLFW Window functions #996
 * Bring forward 3.x binding generators to 4.0 #1004
 * Add matrix multiplication + missing operator to Vector2/Vector2d #1011
 * Optimize barycentric interpolation #1019

### 3.1.0

	General:

	* Fixed problem where OpenGL 3.2 contexts where created using the wrong flags, causing renderdoc error (#790).
	* Fixed problem where Vector3.Transform(Quaternion) returned incorrect results ( #776 ).
	* SDL backend no longer handles exceptions thrown in input events ( #735 #737 )
	* Updated gamepadd mappings for SDL (#927).
	* Alt + numpad now results in correct data being passed to OnKeyPress (f17fa4b).

	Windows:

	* Keypress events are using CharSet.Unicode to allow for UTF characters.
	* If GetMouseMovePointsEx returns "access denied" we fall back to the old mouse move handling ( #883 ).
	* Detect joysticks which declare no valid controls & ignore (Cherry-picked from #819 ).
	* Fix where an invalid joystick axis overwrites the first joystick axis. (Cherry-picked from #819 ).
	* Makes the ArbCreateContext return valid settings ( #754 ).

	MacOS:

	* Unprocessed events no longer put the application into a partially-activated state ( #732 ).
	* Multiple fixes under PR #914:
	* NativeWindow.CursorVisible no longer resets the mouse position ( #668 ).
	* Custom cursors should work now ( e598ab2 ).
	* Command key is now a valid modifier ( 286119e ).
	* Fix where KeyDown events would trigger KeyPress when they shouldn't, e.g. when pasting ( ea3dd48 ).
	* KeyPress now receives the correct keycodes even if modifiers where held when typing ( 91b03dd ).

  	Internal:

	* Generator.Build now uses invariant culture for parsing avoiding an exception when the local system uses comma as decimal separator ( #750 ).
	* Removed weird assembly version check fixing #710.
	* Fixed Xamarin project so that it compiles ( See #725 and b16e7fa ).
	* Matrix4 uses unsafe to invert for performace ( #719 ).
	* Removed link to gitter chat, discord is where it's at ( #770 ).

### 3.0.1
    * Hotfix release
    * Fixed an issue with vector transformation

### 3.0.0
    * Final .NET Framework release
    * Numerous bug fixes

### 3.0.0-pre
	* Support for OpenGL 4.6
	* Replaced JoystickButton enum with simple long. (breaking API change)
	* Increase available joystick buttons to 64.
	* Add support for OpenGL ES3 through Angle + DIrect3D.
	* Fix 2 crashes on android
	* Move to built-in System.Diagnostics.Debug for Android + iOS
	* Fix for certain joysticks returning invalid HID pages.
	* Fix for certain joysticks with negative axis range being inverted.
	* Fix Xbox controller D-pad on windows
	* Fix joystick hat position sticking on Linux
	* Enhance xbox button detection to include GUIDE button.
	* Fix iOS GL bindings issue introduced by 2ea8334
	* Fix crash on setting time to <= 0 for iOS + Android.
	* Several minor XML documentation fixes and enhancements
	* Fix for angle backbuffer size issue on window resize
	* Possible fix for broken GLControl package.

### 2.0.0
	* Moved to new FAKE/Paket based build system
	* Removed superfluous release configurations
	* Numerous other fixes and enhancements

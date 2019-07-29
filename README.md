# Data files for the *ncTemplate* project

## Customization

- Rewrite the `README.md` file with information about your project data files, for example licensing details.
- Create a set of icons for your project and put them in the `icons` directory.  
  This template has already icons in different sizes to show you the required file sizes and names.
- The root for your project data is the `data` directory.  
  You can put all your data files there or create additional subdirectories like `textures`, `sounds`, `fonts`, `scripts` and so on.  
  The contents of this directory will be part of your project installation files and the root of the Emscripten filesystem.
- If your project targets the Android platform don't forget to set a list of files in `PACKAGE_ANDROID_ASSETS`.  
  You might want to create an `android` directory to keep specific Android files from being included in other platforms installers or Emscripten builds.

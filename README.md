# User Document

Hello! Welcome to Rust Spatializer, a VST3 format spatial audio creator plugin. You can download this plugin for use in your favorite Digital Audio Workstation (DAW).

To get your hands on the spatializer, simply follow these steps:

### Clone the project files
Our latest version of the rust spatializer is now available. You can clone it using the provided link

```
git clone https://github.com/tangy1227/ase-project.git
```

### Build the project
```
cargo xtask bundle ase-project --release
```
After running the code, you'll receive the VST3 format files, ready to be used in your DAW. Let's walk you through how to integrate it into Reaper this time.

### Rust Spatializer in Reaper
![Settings](https://github.com/tangy1227/ase-project/assets/90415168/4c74a550-0709-400e-a4f9-58de7dad4d89)
In Reaper, adding the VST3 format plugin is a breeze. Simply navigate to 'Settings' in the top menu bar.

![Preference](https://github.com/tangy1227/ase-project/assets/90415168/d6564600-a7ae-4ea7-9a46-fee72f35a3e9)
Then, head to 'Preferences' and select 'Plug-ins -> VST'. There, you can easily edit the path list to include your VST file location. After that, just hit 'Re-scan', and Reaper will automatically detect it.

Now, you're all set! Feel free to add the plugin to any track whenever you're ready to use it.

### Features
Within Reaper's GUI, you'll discover our intuitive spatialization interface.

![Rust Spatializer in Reaper](https://github.com/tangy1227/ase-project/assets/90415168/00e910f9-d762-486d-8abc-00f42a5c19d7)

With four distinct features, you can effortlessly manipulate audio by simply adjusting sliders. Control the gain and explore movement along three axes of the sphere: front-back, left-right, and up-down. This grants you the ability to visualize and shape audio in full 3D space!


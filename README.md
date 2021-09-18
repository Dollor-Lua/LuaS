# LuaS
You may be wondering, where's the source code? not here. I don't want to open source this project.
I did leave the images for you here though!

## Installation
head over to the [releases page](https://github.com/Dollor-Lua/LuaS/releases) and download the latest release/recommended release

### True Installation
Once you have the installer on your computer, run the executable. It should launch an installer.
Follow those instructions until LuaS is fully installed.

### Portable Installation
If you prefer, you can just download the two executables for luas (luas.exe and luasmk.exe)
Place the two executables in the same folder and then add that folder to your PATH

## Starting a LuaS project
To create a new LuaS project, go into the folder you wish to make the project in
once you have done that, run `luasmk new example-project`. This will create a new folder with the name "example-project"
- if you wish to create the project without creating it inside a folder only run `luasmk new`

## Launching the app locally
Want to test your app? Simply run `luas serve` and a server will be started on [http://localhost:8000](http://localhost:8000)
- You can also specify what port to run the app off of with the `-p` option. ex: `luas serve -p8000`

## Adding new routes
You can add new routes to your Routefile by adding new `get  '/location/' => 'views/location'` to it.
Make sure the `get` route commands are inside of the `return {}`

Be careful with the Routefile! It is very sensitive. spaces must be precise, and there can only be one get command per line.
Along with that, the `return {}` has to be written out with the "return {" on one line and the "}" on the line after the last get command.

## More documentation coming soon!

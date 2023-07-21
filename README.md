# StarFluxGames.Techtonica.ModBuildUtilities

| Property				| Type		| Description |
| ---					| ---		| --- |
| GamePath				| String	| The directory where the Techtonica executable is located |
| AssemblyReferencePath | String	| Your Techtonica_Data/Managed directory |
| GameModsPath			| String	| The Mods folder located in the same directory as your Techtonica executable |
| AssetBundlePath		| String	| The path to the AssetBundle for your mod |

| Utility				| Type		| Default	| Description |
| ---					| ---		| ---		| --- |
| EnableModDeployLocal	| Bool		| True		| Automatically deploy to your Mods directory |
| EnableGameDebugging	| Bool		| True		| Automatically attach Roslyn debugger for the Visual Studio IDE |
| EnableCopyLocal		| Bool		| False		| Copy dependencies to your build directory |
| EnableDocumentation	| Bool		| True		| Generate XML documentation |

# Credits
Tool originally made for PlateUp! by Yaraizen
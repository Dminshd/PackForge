# PackForge
## _A Datapack/Resourcepack/Shaderpack Generation Tool_

### Currently Supported Versions
> Minecraft 1.21

### Current Features
- [x] Generate files required for custom trim materials

### Planned Features
- [ ] Generate files required for custom trims
- [ ] Generate files required for custom recipes
- [ ] Generate files required for custom blocks
- [ ] Generate files required for custom items
- [ ] Generate files required for custom entities
- [ ] Generate files required for world generation modification
- [ ] Ability to import existing packs for modification

### How to Build
| Dependencies     | Links |
| ---------------- | ----------- |
| clang [^1]       | https://releases.llvm.org/download.html |
| cjson            | https://github.com/DaveGamble/cJSON |

[^1]: You can use any compiler you want just modify the shell script

1. Navigate to the root folder you cloned the project into
2. Run `bash build.sh`
3. Run the executable `./run`

### How to Use
Now you can follow the steps to generate your pack. If your pack includes any textures the folders should generate but the textures will not be generated. If I haven't been lazy I put any further instructions you need to follow in the tools step so you can follow those instructions. Otherwise you'll need to look up where to find put the textures. I will try to update this tool as its required. 

Thanks for checking it out, 
Dminshd
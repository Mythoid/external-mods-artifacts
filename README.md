# External Mods Artifacts Repository

This is a repository for storing any open sourced mods that are created by other developers rather than Mythoid's, that we self-build and use to build our modded server. The mods are already found on GitHub, has source code and also is compatible with MIT License.

## Directory Structure

Each mod will be in their respective `MOD_AUTHOR/MOD_NAME` directory, as follow:

```
.
├── MOD_AUTHOR/
│   ├── MOD_NAME/
│   │   ├── README.md
│   │   ├── neoforge/
│   │   │   ├── ...
│   │   │   ├── 1.19.2
│   │   │   ├── 1.20.1/
│   │   │   │   └── MOD_FILE.jar
│   │   │   ├── 1.20.4
│   │   │   ├── 1.21.1
│   │   │   └── ...
│   │   ├── fabric/
│   │   │   └── ...
│   │   └── ...
│   └── ...
└── ...
```

A mod directory needs to also have a `README.md` file that references to their repository on GitHub.
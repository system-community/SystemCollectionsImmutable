## What

- System.Collections.Immutable.5.0.0\lib\net461

## Requirements
[![Unity 2018.3+](https://img.shields.io/badge/unity-2018.3+-brightgreen.svg?style=flat&logo=unity&cacheSeconds=2592000)](https://unity3d.com/get-unity/download/archive)
[![.Net 2.1 Scripting Runtime](https://img.shields.io/badge/.NET-2.1-blueviolet.svg?style=flat&cacheSeconds=2592000)](https://docs.unity3d.com/2019.1/Documentation/Manual/ScriptingRuntimeUpgrade.html)


## How To Install

Since version 2021 LTS unity has built-in System.Memory so we will not need to install additional dependencies for System.Collections.Immutable to work.


### For Unity 2021 LTS Or Newer
Add the following lines

- for excactly version

- `5.0.0`
```csharp
"com.system-community.systemcollectionsimmutable": "https://github.com/system-community/SystemCollectionsImmutable.git?path=Assets/_Root#5.0.0",
```

To `Packages/manifest.json`

### For Unity 2020 LTS Or Older
Add the following lines

- for excactly version

- `5.0.0`
```csharp
"com.system-community.systemmemory": "https://github.com/system-community/SystemMemory.git?path=Assets/_Root#4.5.4",
"com.system-community.systembuffers": "https://github.com/system-community/SystemBuffers.git?path=Assets/_Root#4.4.0",
"com.system-community.systemnumericsvectors": "https://github.com/system-community/SystemNumericsVectors.git?path=Assets/_Root#4.4.0",
"com.system-community.systemruntimecompilerservicesunsafe": "https://github.com/system-community/SystemRuntimeCompilerServicesUnsafe.git?path=Assets/_Root#4.5.3",
"com.system-community.systemcollectionsimmutable": "https://github.com/system-community/SystemCollectionsImmutable.git?path=Assets/_Root#5.0.0",
```

To `Packages/manifest.json`


## Dependencies

- [![System.Memory 4.5.4](https://img.shields.io/badge/System.Memory-4.5.4+-brightgreen.svg?style=flat&cacheSeconds=2592000)](https://github.com/system-community/SystemMemory/tree/4.5.4)

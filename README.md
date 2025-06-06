# Exiled Dev References

A NuGet package containing all necessary DLLs for Exiled plugin development. 

This will be updated based on Exiled's .dll file requirements and other needed libraries. I may additionally add more well known and versatile .dlls (like Newtonsoft and similar projects) due to their constant use and their un-replacable quality. However I will have to check the distribution as ofc i dont want to break any rules 🙏

> **Note**: This is not being used for profit or other means its simply to assist developers that work on the Exiled Framework. Im putting this note to clarify my intentions is all. No profit or donations should or would ever be taken from this project. This project is free to edit/change/fork/etc to do all i ask is you credit me for the orginal idea for this.

## Installation

Install via NuGet Package Manager:
```
PM> Install-Package Exiled.Dev.References
```

Or via .NET CLI:
```
dotnet add package Exiled.Dev.References
```

## Included References
This package includes all the necessary DLLs for Exiled development, including:
```
### Core References
- Assembly-CSharp-firstpass.dll 
- BouncyCastle.Cryptography.dll
- Caress.dll
- CommandSystem.Core.dll
- DnsClient.dll
- Facepunch.Steamworks.Win64.dll
- Mirror.Components.dll
- Mirror.dll
- NorthwoodLib.dll
- PluginAPI.dll
- Pooling.dll

### Utility Libraries
- Mono.Cecil.dll
- Mono.Cecil.Mdb.dll
- Mono.Cecil.Pdb.dll
- Mono.Cecil.Rocks.dll
- Mono.Posix.dll
- Mono.Security.dll
- System.Runtime.CompilerServices.Unsafe.dll

### Unity Engine Libraries
- Unity.Burst.dll
- Unity.Burst.Unsafe.dll
- Unity.Mathematics.dll
- Unity.ProBuilder.Csg.dll
- Unity.ProBuilder.dll
- Unity.ProBuilder.KdTree.dll
- Unity.ProBuilder.Poly2Tri.dll
- Unity.ProBuilder.Stl.dll
- Unity.RenderPipelines.Core.Runtime.dll
- Unity.RenderPipelines.Core.ShaderLibrary.dll
- Unity.RenderPipelines.HighDefinition.Config.Runtime.dll
- Unity.RenderPipelines.HighDefinition.Runtime.dll
- Unity.RenderPipelines.ShaderGraph.ShaderGraphLibrary.dll
- Unity.TextMeshPro.dll
- Unity.Timeline.dll
- Unity.VisualEffectGraph.Runtime.dll
- UnityEngine.AccessibilityModule.dll
- UnityEngine.AIModule.dll
- UnityEngine.AndroidJNIModule.dll
- UnityEngine.AnimationModule.dll
- UnityEngine.ARModule.dll
- UnityEngine.AssetBundleModule.dll
- UnityEngine.AudioModule.dll
- UnityEngine.ClothModule.dll
- UnityEngine.ClusterInputModule.dll
- UnityEngine.ClusterRendererModule.dll
- UnityEngine.CoreModule.dll
- UnityEngine.CrashReportingModule.dll
- UnityEngine.DirectorModule.dll
- UnityEngine.dll
- UnityEngine.DSPGraphModule.dll
- UnityEngine.GameCenterModule.dll
- UnityEngine.GIModule.dll
- UnityEngine.GridModule.dll
- UnityEngine.HotReloadModule.dll
- UnityEngine.ImageConversionModule.dll
- UnityEngine.IMGUIModule.dll
- UnityEngine.InputLegacyModule.dll
- UnityEngine.InputModule.dll
- UnityEngine.JSONSerializeModule.dll
- UnityEngine.LocalizationModule.dll
- UnityEngine.NVIDIAModule.dll
- UnityEngine.ParticleSystemModule.dll
- UnityEngine.PerformanceReportingModule.dll
- UnityEngine.Physics2DModule.dll
- UnityEngine.PhysicsModule.dll
- UnityEngine.ProfilerModule.dll
- UnityEngine.RuntimeInitializeOnLoadManagerInitializerModule.dll
- UnityEngine.ScreenCaptureModule.dll
- UnityEngine.SharedInternalsModule.dll
- UnityEngine.SpriteMaskModule.dll
- UnityEngine.SpriteShapeModule.dll
- UnityEngine.StreamingModule.dll
- UnityEngine.SubstanceModule.dll
- UnityEngine.SubsystemsModule.dll
- UnityEngine.TerrainModule.dll
- UnityEngine.TerrainPhysicsModule.dll
- UnityEngine.TextCoreFontEngineModule.dll
- UnityEngine.TextCoreTextEngineModule.dll
- UnityEngine.TextRenderingModule.dll
- UnityEngine.TilemapModule.dll
- UnityEngine.TLSModule.dll
- UnityEngine.UI.dll
- UnityEngine.UIElementsModule.dll
- UnityEngine.UIElementsNativeModule.dll
- UnityEngine.UIModule.dll
- UnityEngine.UmbraModule.dll
- UnityEngine.UNETModule.dll
- UnityEngine.UnityAnalyticsCommonModule.dll
- UnityEngine.UnityAnalyticsModule.dll
- UnityEngine.UnityConnectModule.dll
- UnityEngine.UnityCurlModule.dll
- UnityEngine.UnityTestProtocolModule.dll
- UnityEngine.UnityWebRequestAssetBundleModule.dll
- UnityEngine.UnityWebRequestAudioModule.dll
- UnityEngine.UnityWebRequestModule.dll
- UnityEngine.UnityWebRequestTextureModule.dll
- UnityEngine.UnityWebRequestWWWModule.dll
- UnityEngine.VehiclesModule.dll
- UnityEngine.VFXModule.dll
- UnityEngine.VideoModule.dll
- UnityEngine.VirtualTexturingModule.dll
- UnityEngine.VRModule.dll
- UnityEngine.WindModule.dll
- UnityEngine.XRModule.dll

### Other Libraries
- YamlDotNet.dll
- zxing.dll
```

> **Note**: Assembly-CSharp.dll and Assembly-CSharp-Publicized.dll were excluded due to complications of double references or not be able to reference them properly. Hopefully i can find a fix for this but currently as of Exiled v9.5.1 you should be able to use this package and the Exiled package and will work (this is tested on my own public [plugin](https://github.com/Swishhyy/SUP))

# `Scalability.ini`

Graphics settings are organized into groups ...

- `@0` = Low
- `@1`
- `@2`
- `@3` = Ultra

## Shadows

Shadow quality is managed in `Scalability.ini`.

Settings include ...

```
[PostProcessQuality@0]
r.AmbientOcclusionLevels
r.FastBlurThreshold
r.ScreenSpaceReflections

[ShadowQuality@0]
r.LightFunctionQuality
r.ShadowQuality
r.Shadow.CSM.MaxCascades
r.Shadow.MaxResolution
r.Shadow.RadiusThreshold
r.Shadow.DistanceScale
r.Shadow.CSM.TransitionScale
r.DistanceFieldShadowing
r.DistanceFieldAO
r.Shadow.CachedShadowsCastFromMovablePrimitives

[TextureQuality@0] 
r.MaxAnisotropy
r.MaxAnisotropy
r.Streaming.LimitPoolSizeToVRAM
r.Streaming.PoolSize

[ViewDistanceQuality@0] 
r.ViewDistanceScale
```

## Amunets Dynamic Shadows

A [mod](https://steamcommunity.com/sharedfiles/filedetails/?id=2338340168) @ Steam Workshop that enables dynamic shadows.

Q: Why?

A: Similar to Fallout 4, given default settings lights (e.g. torches) unimmersively ignore walls, etc.

Configure ...

- Intended to be used with Shadow Quality = Ultra.
- Requires the following edit to `Scalability.ini`...

```
[ShadowQuality@3]
r.Shadow.CachedShadowsCastFromMovablePrimitives=1
```

## Reference

- [Tweaks and Fixes for Unofficial Dedicated Servers](https://steamcommunity.com/sharedfiles/filedetails/?id=2130895654) by kเt @ steamcommunity.

# `Scalability.ini`

## Shadows

Shadow quality is managed in `Scalability.ini`.

Settings include ...

```
[ShadowQuality@1]
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
```

## Amunets Dynamic Shadows

A [mod](https://steamcommunity.com/sharedfiles/filedetails/?id=2338340168) @ Steam Workshop that enables dynamic shadows.

- Intended to be used with Shadow Quality = Ultra.
- Requires the following edit to `Scalability.ini`...

```
[ShadowQuality@3]
r.Shadow.CachedShadowsCastFromMovablePrimitives=1
```

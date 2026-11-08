# MG5
## Devlog
1. I think it's more effective to use a NavMesh when you're using the mouse to control movement while physics are more effective when using wasd/joysticks to control movement. A game like Celeste probably uses physics while a game like OSU probably uses a NavMesh.
2. The loop in BirdManager looks at every bird in _birds and checks if the distance between the bird and the player is less than the minimum distance to interact. If this is true for a bird, that bird activates the RunAway method.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
This function checks if any object with collision is between you and another player
```
public static bool IsNothingBetweenPlayers(PlayerControl otherPlayer)
{
    var layer = LayerMask.GetMask(new string[]
    {
        "Ship",
        "Objects"
    });
    return !PhysicsHelpers.AnythingBetween(PlayerControl.LocalPlayer.GetTruePosition(), otherPlayer.GetTruePosition(), layer, false);
}
```

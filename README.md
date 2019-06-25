This package is for evaluating the armor type (light, medium, heavy) of a unit.
It is a thin wrapper around `BlzGetUnitIntegerField(u, UNIT_IF_DEFENSE_TYPE)`.
The API is exposed as an enum, and the enum values can be printed with the `.display()` method.

# Docs

[Online docs reference](https://cokemonkey11.github.io/WurstArmorType/)

# Updating docs

`../wurstdoktor/target/release/wurstdoktor.exe < wurst/WurstArmorType.wurst > wurstdoktor.yaml`

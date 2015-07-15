The Combustion Engine is a powerful energy producer. It reqires a liquid combustible fuel to operate.

Fluid | Energy Output | Energy per Bucket | Time 
----- | ------------- | ----------------- | ----
[Oil](/Energy/Oil.md) | 30 RF/t | 150,000 | 4m 10s
[Fuel](/Energy/Fuel.md) | 60 RF/t | 1,500,000 | 20m 50s

The Combustion Engine produces a lot more heat than the [Stirling Engine](/Energy/Stirling_Engine.md) and thus requires cooling with a coolant, for example water.

![Typical Combustion Engine setup - powered by fuel, cooled by water](/images/screenshots/combustionengine1.png)

The formula for the amount of water required is: **W = E * (T/2 + 0.5)^2**, where W is the amount of water (in mB/t), E is the energy output (in RF/t), and T is the temperature of the biome.

Biome | Temperature | Water required (Oil) | Water required (Fuel)
----- | ----------- | -------------------- | ---------------------
Desert | 2.0 | 6.75 mB/t | 14 mB/t
Plains | 0.8 | 2.5 mB/t | 5 mB/t
Taiga | 0.25 | 1.1 mB/t | 2.5 mB/t

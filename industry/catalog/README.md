# Catalog Documentation

_(IN PROGRESS)_

The catalog represents what each things purpose is within the current months task list.

By default the catalog will query the task service and infer the supply chain, choosing the leafs as either products or inputs and things in the middle as being built inhouse.

The catalog will also keep tabs on things located in a [warehouse](/industry/warehouse/README.md) and present data to views for shoppers.

Take the following task list as an example

`produce 500 150mm Railgun II`

requirements per run (production):
```
x11 Superconductor Rails (we'll build these)
x8 Morphite
x1 150mm Railgun I (we'll build these)
x1 Robotics
x1 R.A.M.- Weapon Tech
```

requirements (invention):
```
x1 Datacore - Plasma Physics
x1 Datacore - Quantum Physics
```

`produce 5,500 Superconductor Rails`

requirements per run (production)
```
x1 Hypersynaptic Fibers
x10 Fullerides
x28 Titanium Carbide
```

`produce 500 150mm Railgun I`

requirements (production)
```
x2457 Tritanium
x134 Pyerite
x154 Mexallon
x4 Zydrine
```
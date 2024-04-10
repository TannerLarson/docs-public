# Final goal

[Space parts](https://satisfactory-calculator.com/en/planners/production/index/json/%7B%22Desc_SpaceElevatorPart_7_C%22%3A%228%22%2C%22Desc_SpaceElevatorPart_6_C%22%3A%228%22%2C%22Desc_SpaceElevatorPart_8_C%22%3A%222%22%2C%22Desc_SpaceElevatorPart_9_C%22%3A%222%22%7D)
* Note: This needs alternate recipies

# Overall Plan
1. Start in Dune Desert
2. Rush tier 3
3. Coal power
4. Temporary steel beam production
5. Using Mk 3 belts
    * Blueprint designer / Build blueprints
    * Create resource hub
    * Start Rust and Posh factories
6. Build train tracks from Oil to Posh to Rust factories for power
7. Start Oil factory
8. Complete train loop between four main factories
9. Start Element factory
10. Complete main factories
11. Complete sub-factories
12. Build final factories using the main logistics hub
13. Beat the game

# Why organize this way?
One of the main reasons I stop enjoying Satisfactory is when I get overwhelmed with the logistics of late-game parts. The simplest solution to this is to pipe all complex resources to a single place and then use those resources to make everything else until you beat the game. This method inevitably leads to a few issues:
1. Disorganization / spaghetti makes everything more difficult
2. Bottlenecks. If everything is getting piped through a single Mk 5 conveyer belt, it limits the max input of all the necessary resources to 780 / min
3. More failure points due to the need to move a greater variety of materials

I believe an easy solution to these issues is to keep train usage to a bare minimum and build everything as close as possible to their respective resource nodes. If we follow this guide, we will only need to pull from a central storage for 5 unique parts (see [Parts not accounted for](#parts-not-accounted-for)). This should significantly minimize disorganization in our main storage facility. 

# Rules

## General
* The main logistics hub needs to recieve resources from the main train line when the train is between the Oil and Posh factories because the Oil factory needs resources from the Posh factory, and the Oil factory will yield resources from the Secondary Oil factory. This means that the main logistics hub should:
* be at the Oil factory
* be at the Posh factory
* have a separate dedicated train line directly from the Oil or Posh factory to wherever you want the main logistics hub to be.

## Railway
* There will be a main railway with four stops, one at each main factory
* Sub-factories (except for Secondary Oil) will not recieve their resources from the main railway
* Sub-factories will only drop off resources at one of the main four stations
* Posh and Element will have a small transportation system between them
* Each station will have a miniature storage facility that contain all the factory and sub-factory outputs, complete with their own sinks
* There will be at least six cars per train, with two locomotives each.
    * There will be a single train car dedicated to each main factory. Each of these cars will recieve all factory outputs evenly. For example, the car dedicated to the Rust factory should recieve an equal number of iron plates, rotors, smart plating, ect as long as there are enough resources to give
        * We technically don't need four separate cars, but by having more cars we will be more resilient to throughput increases
        * We want to evenly distribute input here because the vast majority of these resources will be exclusively for players to use directly. All the parts here that will be used for factories won't require very high input numbers.
    * One car will contain parts needed to produce things at the Secondary Oil factory
    * One car will be dedicated to Nitrogen distribution.
* More cars and locomotives can be added to a train and more trains can be added to the railway for greater throughput
* Trains will only ever drop materials off at the Oil factory. The first will be the Oil station, and the second will be the main storage facility
* DO NOT use 4m ramps when laying track

# Factories

## Main
'*' indicates that the resource needs to be used non-locally. If a resource doesn't have this mark, it isn't used in any other non-local factory. For example, batteries that are made in the Element factory are used in the main logistics hub factory for Magnetic Field Generators. Rubber is used in the Oil factory as well as the Secondary Oil factory, but isn't used in any other factory and therefore is not marked.

### Element (Aluminum / Sulfur)
* Alclad Aluminum Sheets
* Aluminum Casing
* Battery *
* Compacted Coal?
* Black Powder
#### Alternate Recipies
* Pure Aluminum Ingot
* Sloppy Alumina
* Fine Black Powder
#### Location
[Titan Forest](https://satisfactory-calculator.com/en/planners/production/index/json/%7B%22Desc_AluminumPlate_C%22%3A%221%22%2C%22Desc_AluminumCasing_C%22%3A%221%22%2C%22Desc_Battery_C%22%3A%221%22%2C%22Desc_CompactedCoal_C%22%3A%221%22%2C%22Desc_Gunpowder_C%22%3A%221%22%2C%22input%22%3A%7B%22Desc_OreCopper_C%22%3A%221440%22%2C%22Desc_Coal_C%22%3A%221680%22%2C%22Desc_Sulfur_C%22%3A%22480%22%2C%22Desc_OreBauxite_C%22%3A%22960%22%7D%2C%22altRecipes%22%3A%5B%22Recipe_Alternate_AlcladCasing_C%22%2C%22Recipe_Alternate_Gunpowder_1_C%22%2C%22Recipe_PureAluminumIngot_C%22%2C%22Recipe_Alternate_SloppyAlumina_C%22%5D%7D)


### Oil
* Fuel
* Rubber
* Plastic
* Fabric?
#### Alternate Recipies
* Heavy Oil Residue
* Recycled Plastic
* Recycled Rubber
* Diluted Fuel?
#### Location
[Spire Coast](https://satisfactory-calculator.com/en/planners/production/index/json/%7B%22Desc_LiquidFuel_C%22%3A%221%22%2C%22Desc_Fabric_C%22%3A%221%22%2C%22Desc_Plastic_C%22%3A%221%22%2C%22Desc_Rubber_C%22%3A%221%22%2C%22input%22%3A%7B%22Desc_LiquidOil_C%22%3A%221320%22%7D%2C%22altRecipes%22%3A%5B%22Recipe_ResidualFuel_C%22%2C%22Recipe_Alternate_PolyesterFabric_C%22%2C%22Recipe_Alternate_Plastic_1_C%22%2C%22Recipe_Alternate_RecycledRubber_C%22%2C%22Recipe_Alternate_HeavyOilResidue_C%22%5D%7D) / Lake Forest

### Rust (Iron / Steel)
* Iron Plate
* Iron Rod
* Reinforced Iron Plate
* Modular Frames
* Steel Beam
* Steel Pipe
* Rotor
* Stator
* Motor *
* Encased Industrial Beam
* Heavy Modular Frame
* Smart Plating *
* Versatile Framework *
#### Alternate Recipies
* Solid Steel Ingot
* Steel Rotor
* Iron Wire
* Encased Industrial Pipe
* Stitched Iron Plate
* Steeled Frame
* Heavy Encased Frame
#### Location
[Dune Desert (South)](https://satisfactory-calculator.com/en/planners/production/index/json/%7B%22Desc_IronRod_C%22%3A%221%22%2C%22Desc_IronPlate_C%22%3A%221%22%2C%22Desc_IronPlateReinforced_C%22%3A%221%22%2C%22Desc_SteelPipe_C%22%3A%221%22%2C%22Desc_SteelPlate_C%22%3A%221%22%2C%22Desc_SteelPlateReinforced_C%22%3A%221%22%2C%22Desc_ModularFrame_C%22%3A%221%22%2C%22Desc_ModularFrameHeavy_C%22%3A%221%22%2C%22Desc_Rotor_C%22%3A%221%22%2C%22Desc_Stator_C%22%3A%221%22%2C%22Desc_Motor_C%22%3A%221%22%2C%22Desc_SpaceElevatorPart_1_C%22%3A%221%22%2C%22Desc_SpaceElevatorPart_2_C%22%3A%221%22%2C%22input%22%3A%7B%22Desc_OreIron_C%22%3A%225280%22%2C%22Desc_Coal_C%22%3A%221680%22%7D%2C%22altRecipes%22%3A%5B%22Recipe_Alternate_ReinforcedIronPlate_2_C%22%2C%22Recipe_Alternate_EncasedIndustrialBeam_C%22%2C%22Recipe_Alternate_ModularFrame_C%22%2C%22Recipe_Alternate_ModularFrameHeavy_C%22%2C%22Recipe_Alternate_Rotor_C%22%2C%22Recipe_Alternate_Wire_1_C%22%2C%22Recipe_Alternate_IngotSteel_1_C%22%5D%7D)

### Posh (Copper / Quartz / Caterium)
* Wire
* Cable
* Copper Sheet
* Quickwire
* Quartz Crystal
* Silica
* Circuit Board
* AI Limiter *
* High-Speed Connector *
* Computer *
* Crystal Oscillator
#### Alternate Recipies
* Silicon Circuit Board
* Crystal Computer
* Steamed Copper Sheet
* Fused Quickwire?
* Silicon High-Speed Connector?
#### Location
[Dune Desert (North)](https://satisfactory-calculator.com/en/planners/production/index/json/%7B%22Desc_QuartzCrystal_C%22%3A%221%22%2C%22Desc_Silica_C%22%3A%221%22%2C%22Desc_CopperSheet_C%22%3A%221%22%2C%22Desc_Wire_C%22%3A%221%22%2C%22Desc_Cable_C%22%3A%221%22%2C%22Desc_HighSpeedWire_C%22%3A%221%22%2C%22Desc_CircuitBoard_C%22%3A%221%22%2C%22Desc_CircuitBoardHighSpeed_C%22%3A%221%22%2C%22Desc_HighSpeedConnector_C%22%3A%221%22%2C%22Desc_Computer_C%22%3A%221%22%2C%22Desc_CrystalOscillator_C%22%3A%221%22%2C%22input%22%3A%7B%22Desc_OreIron_C%22%3A%221140%22%2C%22Desc_OreCopper_C%22%3A%221440%22%2C%22Desc_OreGold_C%22%3A%22720%22%2C%22Desc_RawQuartz_C%22%3A%22480%22%7D%2C%22altRecipes%22%3A%5B%22Recipe_Alternate_SteamedCopperSheet_C%22%2C%22Recipe_Alternate_Quickwire_C%22%2C%22Recipe_Alternate_CircuitBoard_1_C%22%2C%22Recipe_Alternate_HighSpeedConnector_C%22%2C%22Recipe_Alternate_Computer_2_C%22%2C%22Recipe_Alternate_CopperAlloyIngot_C%22%2C%22Recipe_Alternate_ReinforcedIronPlate_2_C%22%5D%7D)

## Sub-factories
### Rust + Posh
* Electromagnetic Control Rod *
* Automated Wiring
* Adaptive Control Unit *

### Rust + Element
* Fused Modular Frame (requires nitrogen) *

### Posh + Element
* Heat Sink *
* Radio Control Unit *
#### Notes
* Should have its own transportation system directly from Posh to Element

### Secondary Oil
* Supercomputer *
* Modular Engine
* Cooling System (Requires nitrogen)
* Turbomotor *
#### Notes
* Gets inputs from Oil station and factory, which are then processed and moved back into the Oil station


## Power
* Coal
* Fuel
* Nuclear?
### Notes
* Infused Uranium Cell is more uranium efficient, but should be avoided if we have enough uranium
* Late game requires usage of either Nuclear power or Turbofuel usage
* If using Nuclear power, source all resources locally. DO NOT take from the train.

# Parts not accounted for

## Components
* Pressure Conversion Cube
    * Fused Modular Frame + Radio Control Unit

## Space Parts
* Magnetic Field Generator
    * Rust + Element + ECR
* Assembly Director System
    * Supercomputer + Adaptive Control Unit
* Nuclear Pasta
    * Pressure Conversion Cube + Copper Powder

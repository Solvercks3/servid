---
navigation:
  parent: electric_age/electric_age.md
  title: Large Steam Boiler
  icon: large_steam_boiler
  position: 3

item_ids:
  - large_steam_boiler
---

# Large Steam Boiler

The Large Steam Boiler is an upgraded version of the smaller Bronze and Steel Boilers. It uses fuels 8 times faster than the Furnace, but it produces 256 mb/t of Steam when fully heated.

## Large Steam Boiler

<Recipe id="modern_industrialization:electric_age/machine/large_steam_boiler_asbl" />

Unlike its single block counterpart, in the Large Steam Boiler, 80% of any unconsumed heat will be lost. This means the ratio of energy produced by fuel consumed will drastically decrease when the output decreases below maximum. This will happen when the Boiler is not used continuously at maximum output.

## Bronze Plated Bricks

<Recipe id="modern_industrialization:electric_age/casing/bronze_plated_bricks_asbl" />

The main block you'll need is the Bronze Plated Bricks, but you'll also need Bronze Pipe Machine Casings and Heatproof Machine Casings.

## Machine Casings

<Row>
  <Recipe id="modern_industrialization:steam_age/bronze/casing_pipe_asbl" />
  <Recipe id="modern_industrialization:electric_age/casing/heatproof_machine_casing_asbl" />
</Row>

The Large Steam Boiler is comprised of one layer of Heatproof Machine Casings and three layers of Bronze Plated Bricks.

The controller goes on the second layer (i.e. the first layer of Bronze Plated Bricks).

The two middle blocks are Bronze Pipe Machine Casings.

Hatches must be placed on the bottom layer.

## Boiler Preview

<GameScene zoom="4"  interactive={true}>
  <ImportStructure src="../assets/structures/large_steam_boiler.snbt" />
</GameScene>

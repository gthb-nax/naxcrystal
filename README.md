# esto es un commit para aprender a revertirlo #
y esta segunda línea es para abrir un pull request en vez de commit y ver si se puede revertir desde la web para no bajarme el desktop

## Esto es un fork de pret/pokecrystal

El objetivo es pulir el juego mediante muchas de las opciones explicadas en los tutoriales y así tener una base para otros proyectos derivados.

### Hecho

  remove pokémon sprite animations 31/08/2024
  editar el readme.md con detalles del proyecto

### Por hacer (más ! = mayor importancia)

  ? traducirlo todo
  !!! fix known bugs and maybe improve some messy code
  !!! add debug menu
  
  !!! add a new type (fairy)
  ! add a new pack pocket
  
  !! expand tilesets from 192 to 255
  ! allow priority colours
  allow tiles to have different attributes including x y flip - reduced tilesets?
  colour party menu icons by species
  allow more trainer parties with specifities
  print text when you lose a trainer battle
  !! short beeping noise from low HP
  ! remove artificial save delay
  ! acortar la duración del script de curación en centro pokémon
  option to show shiny colours in pokédex
  ? make wild encounters vary
  !! modify existing gender formula - so female pokémon are not necessarily weaker lol
  display more information on the move screen

  remove failure chance for AI
  ? remove redundant move grammar
  ! remove gym badges boosts

  !!! implement physical/special split
  ! replace stat exp with dvs
  no longer gain exp at level 100
  ! show move names for tm/hm when receiving or buying
  !! reusable tms
  !!! running shoes
  tweak sandstorm and hail behaviours
  use unic colours for each pokeball
  smashing rocks or headbutting trees may give items
  make grass-type mons immune to powders
  reviving pokémon from fossils
  add move reminder
  allow fishing while surfing

  ! changing switch as an evolutionary method
  disable jumping from ledges onto obstacles
  !!! allow using a field move if the pokémon can learn it
  ! toggable items like repel or healing from party menu

  ! cambiar las unidades de medida imperiales por sistema métrico
  ! experimentar con las opciones de player - género, colores...
  ! implementar el plano aéreo para sustituir el tipo Volador o la habilidad Levitación
  
# Pokémon Crystal [![Build Status][ci-badge]][ci]

This is a disassembly of Pokémon Crystal.

It builds the following ROMs:

- Pokemon - Crystal Version (UE) (V1.0) [C][!].gbc `sha1: f4cd194bdee0d04ca4eac29e09b8e4e9d818c133`
- Pokemon - Crystal Version (UE) (V1.1) [C][!].gbc `sha1: f2f52230b536214ef7c9924f483392993e226cfb`
- Pokemon - Crystal Version (A) [C][!].gbc `sha1: a0fc810f1d4e124434f7be2c989ab5b5892ddf36`
- CRYSTAL_ps3_010328d.bin `sha1: c60d57a24bbe8ecf7cba54ab3f90669f97bd330d`
- CRYSTAL_ps3_us_revise_010710d.bin `sha1: 391ae86b1d5a26db712ffe6c28bbf2a1f804c3c4`
- CGBBYTE1.784.patch `sha1: a25517f60ca0e887d39ec698aa56a0040532a4b3`

To set up the repository, see [INSTALL.md](INSTALL.md).


## See also

- [**FAQ**](FAQ.md)
- [**Documentation**][docs]
- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]

You can find us on [Discord (pret, #pokecrystal)](https://discord.gg/d5dubZ3).

For other pret projects, see [pret.github.io](https://pret.github.io/).

[docs]: https://pret.github.io/pokecrystal/
[wiki]: https://github.com/pret/pokecrystal/wiki
[tutorials]: https://github.com/pret/pokecrystal/wiki/Tutorials
[symbols]: https://github.com/pret/pokecrystal/tree/symbols
[ci]: https://github.com/pret/pokecrystal/actions
[ci-badge]: https://github.com/pret/pokecrystal/actions/workflows/main.yml/badge.svg

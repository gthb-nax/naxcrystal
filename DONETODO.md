### Hecho

  31/08/24
  remove pokémon sprite animations 
  03/09/24
  añadir este DONETODO.md a modo de roadmap 
  editar la radio del cuarto de Player para facilitar un quickcheck sin debug
  fix pic banks offset
  re-enable animated tiles even when textboxes are open
  fasten the healing at a healing machine
  fix PokemonPicPointers and UnownPicPointers' address assumption
  fix footprints' top and bottom halves split
  08/09/24
  change ft and lb symbols in dex for m and kg
  update (by hand!) dex_entries measurements like ---(height), ----(weight) - no padding with 0 needed for small pokémon
  09/09/24
  return Magikarp length event to mm! - adapted from Rangi42's polishedcrystal because i just couldn't figure it out!
  fix texts with references to imperial units
  fix multiplayer battle engine bugs
  12/11/24
  remove badge stat boosts
  fix single-player battle engine bugs (prevented scrolling on battle moves menu) - except transformed pkmn can still learn whatever via sketch (but it fails if the rival is transformed), wild pkmn can still teleport regardless of level
  made every gym leader have 13 dvs and elite four+red 15
  13/11/24
  fix overworld engine bugs

### Por hacer (más ! = mayor importancia)

  ? traducirlo todo
  !!! fix known bugs and maybe improve some messy code
  ! implement password system - grant quickcheck, show cheatsheet, starter sets, shiny charm...
  
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
  use unic colours for each pokeball (tweak also healing and HOF machines?)
  smashing rocks or headbutting trees may give items
  make grass-type mons immune to powders
  reviving pokémon from fossils
  add move reminder
  allow fishing while surfing

  ! changing switch as an evolutionary method
  disable jumping from ledges onto obstacles
  !!! allow using a field move if the pokémon can learn it
  ! toggable items like repel or healing from party menu

  ! experimentar con las opciones de player - género, colores...
  ! implementar el plano aéreo para sustituir el tipo Volador o la habilidad Levitación
  cambiar los turnos de confusión
  cambiar el funcionamiento de congelación
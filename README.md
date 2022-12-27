# A Pokedéx command for Pokémon Twitch Streamers


## Nightbot

Type this in chat:

Replace `URL` for your personal deployed instance

```
!addcom !dex $(urlfetch URL/dex/$(querystring)?ch=$(channel)&user=$(user)&userlevel=$(userlevel)&bot=nightbot)
```

or

Add the `!dex` command at https://nightbot.tv/commands/custom
```
$(urlfetch URL/dex/$(querystring)?ch=$(channel)&user=$(user)&userlevel=$(userlevel)&bot=nightbot)
```

## StreamElements

Replace `URL` for your personal deployed instance

Add the `!dex` command at https://streamelements.com/dashboard/bot/commands/custom
```
${urlfetch URL/dex/${pathescape ${0:}}?ch=${channel}&user=${user}&userlevel=${user.level}&bot=streamelements}
```

Usage
------------

  ➤ `!dex help` to get instructions.  
  ➤ `!dex` to get a random Pokemon.  
  ➤ `!dex gengar` or `!dex 94` to see the Pokedex info about    Gengar.  
  ➤ `!dex ability overgrow` to search pokemons with that ability.  
  ➤ `!dex type electric` to search pokemons with t  hat type.  
  ➤ `!dex about` to see about this command.

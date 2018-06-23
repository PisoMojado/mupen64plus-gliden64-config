# Installation:
* I had to build all mupen components - core library, and all main plugins 
 * The last major release is too far behind GLideN64's latest source
 * Important: I had to use the last major version, 2.5, of the mupen-input-sdl plugin
  * It's the only thing I could find that supported bindings defined by hulkenstrong at https://steamcommunity.com/app/353370/discussions/0/492379439691649588/

# Textures:
* Texture packs often only support a specific version of a ROM.
* Zelda MM Celpack works best on European version of the game.
* As of commit 5578519, I can't get .htc texture files to load from the defined hires_texture directory.
 * To work around it, I put the XXXX_HIRESTEXTURE.htc file in the cache directory, and the library loads it.


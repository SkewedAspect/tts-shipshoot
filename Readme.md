# Tabletop Simulator Ship Shoot

This is a project whose end goal is to answer the age old question:

> "Who would win in a fight: The Enterprise D or a Star Destroyer? What about
> Captain Kirk flying the Millenium Falcon, versus Han Solo in a Constitution
> Class? Ok, but what if six TIE Fighters jumped an Assimilated Andromeda
> Ascendant attacking LEXX??"

These are questions the world needs answers to. And TSSS is here to give you
those!

## Yes, but what is it, _really_?

It's a unified minature game based on the Fantasy Flight X-Wing (and WizKids
Attack Wing) games. We've kept (most) of the rules the same, while unifying
concepts and rules between the two systems. We have a unified way of building
ships, and all ships from both systems have been converted to match these new
rules. _In Theory_, builds of the same point value should be _roughly_ of equal
strength. To this end, we've bumped some ships up to larger bases, and even
implemented "Epic Scale" ships to cover everything.

This game has been implemented via Tabletop Simulator, since it gives us a very
good sandbox for testing these changes, and it's mod support is excellent. It
also lets us worry about game mechanics, and _not_ worry about networking or
game engine design. Limitation, sometimes, breeds creativity.

### What it also is

In and around this, we've also just built the best dang X-Wing or Attack Wing
mod out there. Play is streamlined and very easy, with a lot of heavy scripting
to make life so much easier.

## Using this Mod

Well, once we're on Steam Workshop, you'll get it there. Until then, simply
copy the save file for the Table you want from `/saves` into
`~/Library/Tabletop Simulator/Saves`. Make sure to copy the `.json` and `.png`
file!

### Linking to an asset

Because we have all of this in GitHub, it means we're able to link directly to
our source code, thanks to https://www.jsdelivr.com.

The url should simply be:
```
// Omit `@version` completely to get from master
https://cdn.jsdelivr.net/gh/SkewedAspect/tts-shipshoot<@version>/content/<file>

// Example, cloak token from `v1.0.0`
https://cdn.jsdelivr.net/gh/SkewedAspect/tts-shipshoot@1.0.0/content/models/cloakToken.obj
https://cdn.jsdelivr.net/gh/SkewedAspect/tts-shipshoot@1.0.0/content/images/CloakTokenTexture.png

// Example, cloak token from `master`
https://cdn.jsdelivr.net/gh/SkewedAspect/tts-shipshoot/content/models/cloakToken.obj
https://cdn.jsdelivr.net/gh/SkewedAspect/tts-shipshoot/content/images/CloakTokenTexture.png
```

(This should handle all our CDN needs, and allow anyone to take parts of this
that they want.)

## Status

We're just getting started, and this is a good place for us to collaborate and
work out of. Literally nothing's actually done.

## Contributing

Right now, we're not really looking for help; but if you've got something worth
while, go ahead and make a pull request.

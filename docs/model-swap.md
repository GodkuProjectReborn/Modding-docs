# model swap
to get the charID please go to [`charID`](https://github.com/GodkuProjectReborn/Modding-docs/blob/Mods/docs/charID.md)

Search = `xxx;xxx;y::9`
`xxx` = charID
`y` = rarityID

```py
"He": 0
"Ex": 1
"Sp": 2 # Also LL
"Ul": 3
```
once you get the character you wanna swap models with you need to get another one to swap into.
## example

```py
"554;554;3::9": 554, 554, 3 # Ultra Vegito blue
#                 goto 3  ^
# then you'll get a model value.
# it should look something like:
# 800,000,000-1,900,900,000
# there will be 2 of those. always choose the bottom one
# then you'll search another one. this time i'll do ultra rosé
"532;532;3::9": 532, 532, 3
#                 goto 3  ^
# copy Ultra Vegito blue's model value and replace rosé's with it then check rosé and his model should be Vegito's
# this won't change anything besides the voice (not in kit) and character model.
```
### this is for game guardian, please do not ask us how to do it as it is right here.

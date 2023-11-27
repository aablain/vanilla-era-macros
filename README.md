# Vanilla Era Macros
Macros for Vanilla (Era Client, based).

*Note*: I tend to use `<shift>` as my standard modifier key. If you want to use something else, just use a different key in the `[...mod:YOUR_KEY_HERE]` text

## Priest

#### Wand (don't cancel)
```lua
#showtooltip
/castsequence [exists] !shoot,!shoot
```

#### DoT or HoT
```lua
#showtooltip
/cast [harm,exists,nodead,nomod]Shadow Word: Pain; [harm,exists,nodead,mod:shift]Shadow Word: Pain(Rank 1); [nomod]Renew(Rank 1); [mod:shift]Renew(Rank 1)
```

#### Smite, always Max Rank:
```lua
#showtooltip
/cast Smite
```

#### Smite w/Downrank Mod
```lua
#showtooltip
/cast [harm,exists,nodead,nomod]Smite; [harm,exists,nodead,mod:shift]Smite(Rank 1);
```

#### Holy Fire, always Max Rank:
```lua
#showtooltip
/cast Holy Fire
```

#### Mindflay (don't cancel)
```lua
#showtooltip
/use [nochanneling] Mind Flay
```

#### Mind Blast/Mana Burn
```lua
#showtooltip
/cast [harm,exists,nodead,nomod]Mind Blast; [harm,exists,nodead,mod:shift]Mana Burn;
```

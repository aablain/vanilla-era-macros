# Vanilla Era Macros
Macros for Vanilla (Era Client, based).

*Note*: I tend to use `<shift>` as my standard modifier key. If you want to use something else, just use a different key in the `[...mod:YOUR_KEY_HERE]` text

## Priest

#### Wand (don't cancel)
```lua
#showtooltip 18
/castsequence !shoot,!shoot
```

#### DoT or HoT
```lua
#showtooltip
/cast [noharm,mod:shift] Renew(Rank 1); [noharm] Renew; [harm,mod:shift] Shadow Word: Pain(Rank 1);  Shadow Word: Pain
```

#### Smite, always Max Rank:
```lua
#showtooltip
/cast Smite
```

#### Smite w/Downrank Mod
```lua
#showtooltip
/cast [mod:shift] Smite(Rank 1); Smite;
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

#### Mind Sear (don't cancel)
```lua
#showtooltip
/use [nochanneling] Mind Sear
```

#### Mind Blast/Mana Burn
```lua
#showtooltip
/cast [harm,exists,nodead,mod:shift]Mana Burn; Mind Blast; 
```

#### Power Word: Shield w/Downrank Mod
```lua
#showtooltip
/cast [mod:shift]Power Word: Shield(Rank 1); Power Word: Shield;
```

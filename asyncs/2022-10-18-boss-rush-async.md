# FF6 Gauntlet Async
Some experimental flags to try and add an alternate flow to tackling a WC seed

The following are a list of notable flags:

## General
* Open World
* Vanilla bosses
* Random encounters 
* Starting Level 6
* 3 starting character
* 2 starting espers
* B-Dash enabled
* 3 Characters, 10 Espers required to unlock KT Gauntlet

## Scaling
* Unscaled Final Boss
* Scaled Dragons
* Level - 2.5x C + E + D (starting enemy level 12)
* HP/MP - 2.5x C + E + D 
* EXP   - 2x C + E + D
* **Beta** Bosses and dragons all have an exp rate of 150 per level 
    * This means all bosses will provide roughly the same exp. e.g. Whelk and TunnelArmor will give as much as Goddess or the dragons
    * For frame of reference here are the current xp values https://github.com/AtmaTek/WorldsCollide/blob/main/data/bosses_custom_exp.py
    * This is a buff to early game boss exp and a nerf to late-game boss exp
    * Bosses with multiple enemies (Like Stooges, Cranes.. **NOT** number 128, inferno, vargas, etc.) will give a larger amount of EXP due to this change

## Misc
* Narshe Battle (Kefka at Narshe) is now a guaranteed character or esper

**BETA** Gauntlet
* You may enter KT once, fighting all five bosses back-to-back-to-back-to-back-to-back
* Boss Order: Inferno (Right) > Guardian (Middle) > Doom (Left) > Goddess (Right) > Poltrgeist (Middle)
* No menuing between bosses, no saves until the end
* Once completed, you will end in the final switch room with 3 save points. You may not warp stone out once you complete the gauntlet. Make a backup save!

**BETA** Forced Item Rewards - The following checks are guaranteed items:
* All of Terra's checks
* All of Celes' checks
* Auction House

**BETA** Forced Esper Rewards - The following checks are guaranteed espers:
* Narshe Weapon Shop has 2 espers to choose from (with the other being locked behind whelk)
* Lone Wolf will offer you an esper "You'll never get this 'Maduin'!"
* Fanatic's Tower Follower
* Fanatic's Tower Leader (Yes, it can be an esper now)


### Flags 
Gauntlet and force esper/item flags are not yet available in &dev, so this will not work for the time being
```
-open -oa 3.2.2.2.3.3.4.10.10 -ob 63.1.1.11.61 -oc 63.1.1.11.62 -od 63.1.1.11.63 -oe 58.0.0 -of 24.15.15.3.3.11.61.11.62.11.63 -og 2.2.2.2.3.3.4.10.10 -sc1 random -sc2 random -sc3 random -sal -eu -csrp 80 125 -fst -brl -slr 3 5 -lmprp 75 125 -lel -srr 20 30 -rnl -rnc -sdr 1 2 -das -dda -dns -sch -com 98989898989898989898989898 -rec1 28 -rec2 27 -rec3 29 -xpm 3 -mpm 5 -gpm 5 -nxppd -lsced 0.5 -hmced 0.5 -xgced 2 -ase 2 -msl 60 -sed -bnu -res -fer 0 -escr 100 -dgne -wnz -mmnu -cmd -esr 1 5 -ebr 68 -emprp 75 125 -nm1 random -rnl1 -nm2 random -rnl2 -nmmi -gp 5000 -smc 3 -ieor 33 -ieror 33 -csb 3 14 -mca -stra -saw -sirt -sprp 75 125 -sdm 4 -npi -snbr -ccsr 20 -cms -cor -crr -crvr 50 60 -crm -ari -anca -adeh -nmc -nu -nfps -fs -fe -fvd -fr -fj -fbs -fedc -ond -rr -etn -frw -move bd -sl -firr 364,365,599,97,95,107,191,91,1137,29,309,82 -ferr 186,731,577,182,183,575 -mmprp 80 120 -stloc original -drloc original -fc -noshoes -scis -scia -warp -sfd 3 -sto 2 -stesp 2 2 -stl 6 -bef 125 125
```
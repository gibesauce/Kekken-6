# Kekken-6
---

# Credits
## Sadamitsu
- [Images](https://sadamitsu.ru/images.htm) - This is where I got the character renders
- [Composite Input](https://sadamitsu.ru/cwcheat/compositeinput.htm)
- [Converter](https://sadamitsu.ru/cwcheat/converter.htm)
- [Hand Gestures](https://sadamitsu.ru/cwcheat/gestures.htm)
- [Limbs](https://sadamitsu.ru/cwcheat/limbs.htm)
- [Move Finder](https://sadamitsu.ru/cwcheat/movefinder.htm)
- [P0 Animations](https://sadamitsu.ru/cwcheat/p0animations.htm)
- [Throw Camera Modes](https://sadamitsu.ru/cwcheat/throwcameramodes.htm)
- [NetCheat](https:|sadamitsu.ru/netcheat/)

## Raing3
- [PSP Cheat Documentation](https://github.com/raing3/psp-cheat-documentation)

## Kiloutre
- [TKMovesets](https://github.com/Kiloutre/TKMovesets) - Used to dump character animations from TTT2 (PS3/USA) and Tekken 7 (Steam)

---

## Free Memory Addresses
> I forgot where I got this. Credits to yer meemaws.
```hex
_L 0x20000000 to _L 0x20003FFC// User Memory; idk if you can use this
_L 0x2061A488 to _L 0x20640C3C// Unused Animation Area
_L 0x204C9000 to _L 0x204D3000// I'm not sure about this one
_L 0x2054BA10 to _L 0x2055F8F4
_L 0x20883600 to _L 0x208A4000
_L 0x208A6000 to _L 0x208A7C2C
_L 0x208B1990 to _L 0x208B1F7C
_L 0x208C4240 to _L 0x208DE16C
_L 0x20904250 to _L 0x2095B8CC
_L 0x20BFC910 to _L 0x20C2C2DC// I'm not sure
_L 0x20C3C910 to _L 0x20C6C2DC// I'm not sure
_L 0x20C7ED10 to _L 0x20C942DC// I'm not sure
_L 0x20C9BB00 to _L 0x20CA02FC// I'm not sure
_L 0x20DE4CD0 to _L 0x20DF049C// I'm not sure
_L 0x20DF0A30 to _L 0x20DF33FC// I'm not sure
_L 0x20E24000// Kernel Memory Starts (Don't Use it)
_L 0x217440D0 to _L 0x2174BFFC
; Memory Plugin is Needed
_L 0x2174C000 to idk where will it end, lmao
```
## Legend:
| Buttons | PlayStation |    Xbox    |
|:-------:|:-----------:|:----------:|
|    1    |      □      |     X      |
|    2    |      △     |     Y      |
|    3    |      ×      |     A      |
|    4    |      ○      |     B      |

## Attack Input: 08C07D3C or 08C07D3D
> Don't put neutral in any of these, it's just there.
> *0xY0000000Z* - Y can be 2 or 4 (2 is for conditional inputs, 4 is for regular inputs), Z is the button itself.
> (e.g. 0x40000004 = 3, 2 can only ve used on multiple buttons as it doesn't make sense to make a condition that has only one outcome, now does it?

> 'Both inputs below does not need 2 or 4'
> *0x00000X00* - means hold input (e.g. 300 = 1+2 Hold)
> *0x000X0000* - means do not press (e.g. 3000 = do not press 1+2)
  
| ID | Buttons |
|:--:|:-------:|
| 0 |    *    |
| 1 |    1    |
| 2 |    2    |
| 3 |   1+2   |
| 4 |    3    |
| 5 |   1+3   |
| 6 |   2+3   |
| 7 |  1+2+3  |
| 8 |    4    |
| 9 |   1+4   |
| A |   2+4   |
| B |  1+2+4  |
| C |   3+4   |
| D |  1+3+4  |
| E |  2+3+4  |
| F | 1+2+3+4 |

## Directional Inputs: 08C07D30
> Uppercase Letters with asterisk mean 'Hold'

| ID |      Buttons      |
|:--:|:-----------------:|
| 02 | d/b               |
| 04 | d                 |
| 06 | d or d/b          |
| 08 | d/f               |
| 0A | ???               |
| 0C | ???               |
| 0E | d/b or d or d/f   |
| 10 | b                 |
| 12 | d/b or d          |
| 20 | neutral           |
| 40 | f                 |
| 48 | f or d/f          |
| 50 | ???               |
| 60 | f or nothing      |
| 70 | on release        |
| 80 | u/b               |
| 90 | b or u/b          |
| D0 | f or b or u/b     |
| 100 | u                |
| 120 | ???              |
| 200 | u/f              |
| 248 | u/f or f or d/f  |
| 300 | u or u/f         |
| 348 | ???              |
| 380 | u/b or u or u/f  |
| 38A | ???              |
| 3C0 | ???              |
| 3DA | ???              |
| 3EE | any, except b    |
| 3F0 | ???              |
| 402 | D/B*             |
| 404 | D*               |
| 408 | D/F*             |
| 410 | B*               |
| 440 | F*               |
| 480 | U/B*             |
| 8001 | f,f             |
| 8002 | b,b             |
| 8003 | u~n (Side Step) |
| 8004 | d~n (Side Step) |

## Character IDs: 08C078B4
> [Wanna Take A Look Inside?](https://github.com/gibesauce/Kekken-6/blob/main/Documentation/CharID.md)

## Hit Ranks: 08C07A08
| ID  | Rank |
|:---:|---------------------------|
| 10F | Low |
| 217 | Mid
| 31F | Special Mid (Projectiles?) |
| 41F | Special Mid |
| 512 | High |
| 707 | Unblockable Mid |
| 806 | Unblockable High |
| 907 | Unblockable Low |
| B07 | High (For Airborne Opponent) |

## Body States: 
| ID | Status |
|:--:|-----------------------|
| 842 | Stand, Can Block |
| 1029 | |
| 1952 | Stand, Can Block |
| 2821 | Crouch, Cannot Block |
| 3029 | |
| 6084 | Grounded, Face Up |
| 6A84 | Grounded, Face Down |
| 7402 | Airborne, Face Up |
| 7E02 | Airborne, Face Down |
| 8291 | Crouch, Can Block |
| A000 | Invulnerable |
| E18A | |
| F01A | |

## Visual Recovery:
<details>
  <summary>Click to Expand</summary>

|  ID  |                   Name                   |
|:----:|------------------------------------------|
| 8000 | The Main Manager                         | 
| 8001 | Standing                                 |
| 8002 | Crouching                                |
| 8003 | K.O, Face Up                             |
| 8004 | On The Ground, Face Up, v1               |
| 8005 | On The Ground, Face Up, v2               |
| 8006 | Lying, Facing Up, to Recovery            |
| 8007 | Lying, Facing Up, Has Recovered          |
| 8008 | On The Ground, Facing Down, Hands Down, v1 |
| 8009 | Lying, Facing Down, Hands Down, to Recovery |
| 800A | Lying, Facing Down, Has Recovered        |
| 800B | Lying, Facing Down                       |
| 800C | On The Ground, Face Down, Hands Down, v2 |
| 800D | On The Ground, Face Down, Hands Up       |
| 800E | Lying, Facing Up, to Recovery            |
| 800F | Side Step to Left                        |
| 8010 | Side Step to Right                       |
| 8011 |                                          |
| 8012 |                                          |
| 8013 |                                          |
| 8014 |                                          |
| 8015 | Quick Roll Forward                       |
| 8016 | Jump forward                             |
| 8017 | Lying, Facing Down, Has Recovered        |
| 8018 | Tackle, Overturn, and Throws             |
| 8019 | K.O common                               |
| 801A | K.O by a High attack                     |
| 801B | K.O by a Mid attack                      |
| 801C | K.O by a Low attack                      |
| 801D | Default airborne, face up reaction       |
| 801E | Default airborne, face down reaction     |
| 801F | Default air reaction, from face down to face up while turning to the left |
| 8020 | Default air reaction, from face down to face up while turning to the right |
| 8021 | Default air reaction, from face up to face down while turning to the left |
| 8022 | Default air reaction, from face up to face down while turning to the right |
| 8023 | Default Stance                           |
| 8024 | Floor Break, Player                      |
| 8025 | Floor break, Opponent, Facing Up, Slow Speed, Airborne, 5HP Damage |
| 8026 | Floor break, Opponent, Facing Down, Slow Speed, Airborne, 5HP Damage |
| 8027 | Floor break, Opponent, Facing Up, Normal Speed, Airborne, 10HP Damage |
| 8028 | Floor break, Opponent, Facing Down, Normal Speed, Airborne, 10HP Damage |
| 8029 | Tackle, Right Punch Reversal, Throw      |
| 802A | Tackle, Right Punch Reversal, Throw Reaction |
| 802B | Throw Escape                             |
| 802C | Default Stance                           |
| 802D | Default Stance                           |
| 802E | Default Stance                           |
| 802F | Default Stance                           |
| 8030 | Default Stance                           |
| 8031 | Default Stance                           |
| 8032 | Default Stance                           |
| 8033 | Default Stance                           |
| 8034 | Default Stance                           |
| 8035 | Default Stance                           |
| 8036 | Default Stance                           |
| 8037 | Default Stance                           |
| 8038 | Default Stance                           |
| 8039 | Default Stance                           |
| 803A | Default Stance                           |
| 803B | Default Stance                           |
| 803C | Default Stance                           |
| 803D | Default Stance                           |
| 803E | Default Stance                           |
| 803F | Default Stance                           |
| 8040 | Default Stance                           |
| 8041 | Default Stance                           |
| 8042 | Default Stance                           |
| 8043 | Default Stance                           |
| 8044 | Azazel Default Stance Connection         |
| 8045 | The Main Manager                         |
| 8046 | Standing                                 |
| 8047 | Crouching                                |
| 8048 | K.O, Face Up                             |
| 8049 | On The Ground, Face Up, v1               |
| 804A | On The Ground, Face Up, v2               |
| 804B | Lying, Facing Up, to Recovery            |
| 804C | Lying, Facing Up, Has Recovered          |
| 804D | On The Ground, Facing Down, Hands Down, v1 |
| 804E | Lying, Facing Down, Hands Down, to Recovery |
| 804F | Lying, Facing Down, Has Recovered        |
| 8050 | Lying, Facing Down                       |
| 8051 | On The Ground, Face Down, Hands Down, v2 |
| 8052 | On The Ground, Face Down, Hands Up       |
| 8053 | Lying, Facing Up, to Recovery            |
| 8054 | Side Step to Left                        |
| 8055 | Side Step to Right                       |
| 8056 |                                          |
| 8057 |                                          |
| 8058 |                                          |
| 8059 |                                          |
| 805A | Quick Roll Forward                       |
| 805B | Jump forward                             |
| 805C | Lying, Facing Down, Has Recovered        |
| 805D | Tackle, Overturn, and Throws             |
| 805E | K.O common                               |
| 805F | K.O by a High attack                     |
| 8060 | K.O by a Mid attack                      |
| 8061 | K.O by a Low attack                      |
| 8062 | Default airborne, face up reaction       |
| 8063 | Default airborne, face down reaction     |
| 8064 | Default air reaction, from face down to face up while turning to the left |
| 8065 | Default air reaction, from face down to face up while turning to the right |
| 8066 | Default air reaction, from face up to face down while turning to the left |
| 8067 | Default air reaction, from face up to face down while turning to the right |
| 8068 | Default Stance                           |
| 8069 | Floor Break, Player                      |
| 806A | Floor break, Opponent, Facing Up, Slow Speed, Airborne, 5HP Damage |
| 806B | Floor break, Opponent, Facing Down, Slow Speed, Airborne, 5HP Damage |
| 806C | Floor break, Opponent, Facing Up, Normal Speed, Airborne, 10HP Damage |
| 806D | Floor break, Opponent, Facing Down, Normal Speed, Airborne, 10HP Damage |
| 806E | Tackle, Right Punch Reversal, Throw      |
| 806F | Tackle, Right Punch Reversal, Throw Reaction |
| 8070 | Throw Escape                             |
| 8071 | Default Stance                           |
| 8072 | Default Stance                           |
| 8073 | Default Stance                           |
| 8074 | Default Stance                           |
| 8075 | Default Stance                           |
| 8076 | Default Stance                           |
| 8077 | Default Stance                           |
| 8078 | Default Stance                           |
| 8079 | Default Stance                           |
| 807A | Default Stance                           |
| 807B | Default Stance                           |
| 807C | Default Stance                           |
| 807D | Default Stance                           |
| 807E | Default Stance                           |
| 807F | Default Stance                           |
| 8080 | Default Stance                           |
| 8081 | Default Stance                           |
| 8082 | Default Stance                           |
| 8083 | Default Stance                           |
| 8084 | Default Stance                           |
| 8085 | Default Stance                           |
| 8086 | Default Stance                           |
| 8087 | Default Stance                           |
| 8088 | Default Stance                           |
| 8089 | Azazel Default Stance Connection         |
</details>

## Some Shitty Codes
```hex
_C1 Slow-Mo on Hit
_L 0xE0010004 0x20407C78
_L 0x20407CA0 0x00000024
_L 0xE0040023 0x20407CA0
_L 0xE0030008 0x30407CA0
_L 0x20405890 0x00000001
_L 0x20407974 0x00001000
_L 0x204082A4 0x00001000
_L 0xE00408E4 0x10408656
_L 0xE0030014 0x20407CA0
_L 0x20405890 0x00000002
_L 0x20407974 0x00000500
_L 0x204082A4 0x00000500

_C1 Rage on Practice Mode
_L 0xE0070016 0x004140B8
_L 0xE0020000 0x009060E0
_L 0xE1010010 0x20407B4E
_L 0x00407B4E 0x00000040
_L 0xE0020001 0x009060E0
_L 0xE101003F 0x30407B4E
_L 0x00407B4E 0x00000004
_L 0x00000000 0x00000000
```

> *Note: There might be mistakes from here on out.=-)*

## Connection Type
| Hex | Address | Attribute |
|:-:|:-:|---|
| 80 | 0x08E423B0 | Common |
| 96 | |
| 182 | 0x08E423C0 | Slight Tracking |
| 185 | | Moderate Tracking |
| 20F | |
| 214 | |
| 219 | 0x08E423BC | Related to Movement |
| 401 | 0x08E423B4 | Parallel Connection |
| 402 | | Parallel Connection |
| 403 | |
| 404 | |
| 405 | | Parallel Connection |
| 614 | | |
| 619 | | |
| 1ADC | | Connection to Throw |
| 2800 | | Effects |
| 3FFF | | |
| 8080 | 0x08E423B8 | Connection to BT |
| 9ADC | | Connection to Back Throw |

## Permissions & Effects
> [Wanna Take A Look Inside?](https://github.com/gibesauce/Kekken-6/blob/main/Documentation/Permissions.md) 

## Customisations
```Markdown
08CBF290 - Head
08CBF2A4 - Face
08CBF2B8 - Upper Body
08CBF2CC - Lower Body
08CBF2E0 - Other
08CBF2F4 - Effect
08CBF31C - Rage
08CBF394 - Aura
08CBF330 - Hair (Base)

08CBF324 - Costume Colour 1 (Accessories)
08CBF328 - Costume Colour 2 (Upper Body)
08CBF32C - Costume Colour 3 (Lower Body)

; Costume Colour is Universal
0000 - Colour 1 (White)
0001 - Colour 2 (Black)
0002 - Colour 3 (Red)
0003 - Colour 4 (Blue)
0004 - Colour 5 (YelLow)
0005 - Colour 6 (Green)
0006 - Colour 7 (Purple)
0007 - Colour 8 (Brown)


-Paul Phoenix-
*Head*
51CC - Default
48E8 - Bandana
5824 - Biker Bandana
4D20 - Cowboy Hat
3A74 - Dundee Hat & Hair Down
31E4 - Dundee Hat
5898 - Hi-Top Fade
35E4 - Sports Cap
5158 - Ten Gallon Hat
*Face*
0000 - Default
33E4 - Aviator Sunglasses
1C74 - Eye Patch
4124 - Sharp Sunglasses
36CC - Thick Frame Sunglasses
*Upper Body*
4814 - P1 Default
1FEC - P2 Default
495C - Cowboy Shirt
4B78 - Flight Jacket (Brown)
21BC - Flight Jacket (Black)
2230 - Jean Jacket
255C - Leather Vest
20D4 - Shirtless
44A8 - Spiked Shoulder Pads
5654 - T-Shirt
4198 - Wilder Jean Jacket (Black)
403C - Wilder Jean Jacket (White)
*Lower Body*
556C - P1 Default
49D0 - P2 Default
5328 - Cowboy Jeans (Brown)
1A4C - Cowboy Jeans (White)
3740 - Cowboy Jeans (Black)
4434 - Flight Pants (Orange)
56C8 - Flight Pants (Black)
5DEC - Jeans
2148 - Leather Pants
2DE8 - Torn Jeans (Black)
57B0 - Torn Jeans (White)
3258 - Torn Jeans (Red/Brown)
*Other*
0000 - Default
32CC - Broadsword
37B4 - Chinese Sword
34CC - Japanese Sword
3AE8 - One-Hit Kill Sign (3B)
4604 - Sledgehammer (71)
*Effect*
1E44 - Default
4BEC - Effect (Red)
4E7C - Effect (Purple)
4A44 - Effect (Blue)
5024 - Effect (White)
2E6C - Comic Effect (Japanese)
3940 - Comic Effect (English)
*Rage*
5C38 - Default
5FBC - SP Rage (White)
1824 - SP Rage (Black)
1AC0 - SP Rage (Yellow)
3C60 - SP Rage (Lightning)
3E14 - SP Rage (Ice)
420C - SP Rage (Fire)
*Aura*
0000 - Default
2814 - Aura (Blue)
2BB4 - Aura (Green)
2ACC - Aura (Pink)
28FC - Aura (Purple)
29E4 - Aura (Red)
26B8 - Aura (White)
272C - Aura (Yellow)
27A0 - Ki (Blue)
2B40 - Ki (Green)
2A58 - Ki (Pink)
2888 - Ki (Purple)
2970 - Ki (Red)
2C28 - Ki (White)
2C9C - Ki (Yellow)
*Hair*
0000 - Default
1D5C - High Ponytail Base
17B0 - Low Ponytail Base
2318 - Ponytail Base
3170 - Slicked Back Base


-Miguel Caballero Rojo-
*Head*

*Face*

*Upper Body*

*Lower Body*

*Other*
5970 - Broadsword
2BEC - Chinese Sword
47EC - Combat Knife & Quiver
5E44 - Flamenco Guitar (6B)
1770 - Japanese Sword
4E98 - Pistol (28)
2BA0 - Sledgehammer (71)
*Effect*

*Rage*

*Aura*

*Hair*
```



## Audio Tracks
### Folder 1: SFX
```Markdown
| F | 
| 10 | 
| 11 |
| 12 | 
| 13 | 
| 14 | 
| 14 | 
| 16 | 
| 17 | 
| 18 | 
| 19 | 
| 1A |  
| 2D | Ki Charge SFX
| 727 | Hatchet SFX
```
### Folder 2: Grunts
```Markdown
; Miguel
| 01 | hmp
| 02 | tsu!
| 03 | ha!
| 04 | hu!
| 05 | SI!
| 06 | DIYAH!
| 07 | HOOWAH!
| 08 | HMMWAH!
| 09 | hahahahaha
| 0A | HAHAHAHAHA
| 0B | woohoo!
| 0C | woof?
| 0D | ehe
| 0E | huh! (Sound of disappointment)
| 0F | dah!
```

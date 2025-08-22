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
*Ignore Some of these for now*
_L 0x20000000 to _L 0x20003FFC// User Memory; idk if you can use this
_L 0x2061A488 to _L 0x20640C3C// Unused Animation Area
_L 0x204C8C00 to _L 0x204D3B50
_L 0x20883590 to _L 0x208A7C30
_L 0x208C4240 to _L 0x208C81B0
_L 0x208C82F0 t0 _L 0x208C86B0
_L 0x20904250 to _L 0x2094E40C
_L 0x20E24000// Kernel Memory Starts (Don't Use it)
_L 0x217440D0 to _L 0x2174BFFC
; Memory Plugin is Needed
_L 0x2174C000 to idk where will it end, lmao
```
---

## Legend:
| Buttons | PlayStation |    Xbox    |
|:-------:|:-----------:|:----------:|
|    1    |      □      |     X      |
|    2    |      △     |     Y      |
|    3    |      ×      |     A      |
|    4    |      ○      |     B      |
---

## Attack Input: 08C07D3C or 08C07D3D
> Don't put neutral in any of these, it's just there.

> *0xY000ZZZZ* - Y can be 2 or 4 (2 is for conditional inputs, 4 is for regular inputs), Z is the button itself.
> (e.g. 0x40000004 = press 3, 0x00003000 = do not press 3, 0x00000300 = hold 3)
> 

> Note: 0x20000ZZZ can only be used on multiple buttons as it doesn't make sense to make a condition that only has one outcome, now does it?
>
> Hold and "Do Not Press *" inputs does not need 2 or 4
  
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
---

## Directional Inputs: 08C07D30
> Uppercase Letters with asterisk mean 'Hold'

| ID |      Buttons      |
|:--:|:-----------------:|
| 02 | d/b |
| 04 | d |
| 06 | d or d/b |
| 08 | d/f |
| 0A | |
| 0C | |
| 0E | d/b or d or d/f |
| 10 | b |
| 12 | d/b or d |
| 20 | neutral |
| 40 | f |
| 48 | f or d/f |
| 50 | |
| 60 | f or nothing |
| 70 | on release |
| 80 | u/b |
| 90 | b or u/b |
| D0 | f or b or u/b |
| 100 | u |
| 120 | |
| 200 | u/f |
| 248 | u/f or f or d/f |
| 300 | u or u/f |
| 348 | |
| 380 | u/b or u or u/f |
| 38A | |
| 3C0 | |
| 3DA | |
| 3EE | any, except b |
| 3F0 | |
| 402 | D/B* |
| 404 | D* |
| 408 | D/F* |
| 410 | B* |
| 440 | F* |
| 480 | U/B* |
| 8001 | f,f |
| 8002 | b,b |
| 8003 | u~n (Side Step) |
| 8004 | d~n (Side Step) |
---

## Character IDs: 08C078B4
> [Wanna Take A Look Inside?](https://github.com/gibesauce/Kekken-6/blob/main/Documentation/CharID.md)
---

## Hit Ranks: 08C07A08
| ID  | Rank |
|:---:|---------------------------|
| 10F | Low |
| 217 | Mid |
| 31F | Special Mid (Projectiles?) |
| 41F | Special Mid |
| 512 | High |
| 707 | Unblockable Mid |
| 806 | Unblockable High |
| 907 | Unblockable Low |
| B07 | High (For Airborne Opponent) |
---

## Body States: 
| ID | Status |
|:--:|--------|
| 842 | Stand, Cannot Block |
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
---

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

---

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
```
```hex
_C1 Slightly Better Slow-Mo on Hit
_L 0xE02908C0 0x204078E2// If the Stage is Loaded
_L 0xE1010000 0x009043B8// Address 1
_L 0x20413F94 0x00000000
_L 0xE102000A 0x009043B8// Address 1
_L 0xE001001E 0x109043BC// Address 2
_L 0x30100001 0x009043BC// Address 2
# -- Timer Set -- #
_L 0xE10C000A 0x009043B8// Address 1
_L 0xE10B0001 0x009043BC// Address 2
_L 0x50407974 0x00000004// Copy 4 Bytes to 883F00 (P1 Current Speed)
_L 0x00883F00 0x00000000
_L 0x504082A4 0x00000004// Copy 4 Bytes to 883F04 (P2 Current Speed)
_L 0x00883F04 0x00000000
_L 0x504082D0 0x0000000C// Copy 12 Bytes to 883F08 (X,Y, and Z Coordinates)
_L 0x00883F08 0x00000000
_L 0x50408604 0x00000004// Copy 4 Bytes to 883F14 (P2 Pushback Data)
_L 0x00883F14 0x00000000
_L 0x2056F4B0 0x00000000
_L 0x2056F4B4 0x00000005
_L 0x1015350C 0x00003F60// Camera Zoom In
# -- Timer 1 -- #
_L 0xE107000A 0x009043B8// Address 1
_L 0xE106001E 0x209043BC// Address 2
_L 0x20407974 0x00000000// P1 Speed to 0
_L 0x204082A4 0x00000000// P2 Speed to 0
_L 0x204082D0 0x00000000// Write x to X coordinates (relative to a stage)
_L 0x204082D4 0x40C00000// Write x to Y coordinates (height)
_L 0x204082D8 0x00000000// Write x to Z coordinates (relative to a stage)
_L 0x20408604 0x00000000// This fucks up the pushback but you get that oompf
# -- Timer 2 -- #
_L 0xE10F000A 0x009043B8// Address 1
_L 0xE10E001E 0x009043BC// Address 2
_L 0x50883F00 0x00000004// Copy 4 Bytes Back to 407974
_L 0x00407974 0x00000000
_L 0x50883F04 0x00000004// Copy 4 Bytes Back to 4082A4
_L 0x004082A4 0x00000000
_L 0x50883F08 0x0000000C// Copy 12 Bytes Back to 4082D0  
_L 0x004082D0 0x00000000
_L 0x50883F14 0x00000004// Copy 4 Bytes Back to 408604
_L 0x00408604 0x00000000
_L 0x1015350C 0x00003F80// Camera Zoom Out
_L 0x209043B8 0x00000000// Reset Address 1
_L 0x209043BC 0x00000000// Reset Address 2
_L 0x20413F94 0x00000000
_L 0x20407974 0x00001000// P1 Normal Speed
_L 0x204082A4 0x00001000// P2 Normal Speed
```
```hex
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
---

## Connection Type
| Hex | Address | Attribute |
|:-:|:-:|---|
| 80 | 0x08E423B0 | Common |
| 96 | | |
| 97 | | |
| 99 | | |
| 182 | 0x08E423C0 | Slight Tracking |
| 185 | | Moderate Tracking |
| 20F | | |
| 214 | | |
| 219 | 0x08E423BC | Related to Movement |
| 401 | 0x08E423B4 | Parallel Connection |
| 402 | | Parallel Connection |
| 403 | | |
| 404 | | |
| 405 | | Parallel Connection |
| 614 | | |
| 619 | | |
| 880 | | |
| 897 | | |
| 982 | | |
| 1ADC | | Connection to Throw |
| 2800 | | Effects |
| 3FFF | | |
| 8080 | 0x08E423B8 | Connection to BT |
| 9ADC | | Connection to Back Throw |
| 84099 | | |
---

## Permissions & Effects
> [Wanna Take A Look Inside?](https://github.com/gibesauce/Kekken-6/blob/main/Documentation/Permissions.md) 
---

## Customisations
> [Wanna Take A Look Inside?](https://github.com/gibesauce/Kekken-6/blob/main/Documentation/Customisations.md)
---

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

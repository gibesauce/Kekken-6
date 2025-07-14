# Kekken-6
---

# Credits
## Sadamitsu
- [Composite Input](https:|sadamitsu.ru/cwcheat/compositeinput.htm)
- [Converter](https:|sadamitsu.ru/cwcheat/converter.htm)
- [Hand Gestures](https:|sadamitsu.ru/cwcheat/gestures.htm)
- [Limbs](https:|sadamitsu.ru/cwcheat/limbs.htm)
- [Move Finder](https:|sadamitsu.ru/cwcheat/movefinder.htm)
- [P0 Animations](https:|sadamitsu.ru/cwcheat/p0animations.htm)
- [Throw Camera Modes](https:|sadamitsu.ru/cwcheat/throwcameramodes.htm)
- [NetCheat](https:|sadamitsu.ru/netcheat/)

## Kiloutre
- [TKMovesets](https:|github.com/Kiloutre/TKMovesets) - Used to dump character animations from TTT2 (PS3/USA) and Tekken 7 (Steam)

---

## Free Memory Addresses

### I forgot where I got this. Credits to yer meemaws.
```hex
_L 0x2061A488 to _L 0x20640C40
_L 0x204C9000 to _L 0x204D3000
_L 0x2054C000 to _L 0x2055F8F4
_L 0x20884000 to _L 0x208A4000
_L 0x208A6000 to _L 0x208A7C00
_L 0x208C4300 to _L 0x208D4FA0
_L 0x20906000 to _L 0x20946000
; Memory Plugin is Needed
_L 0x21744000 to _L 0x24700000
```

## Legend:
| Buttons | PlayStation |    Xbox    |
|:-------:|:-----------:|:----------:|
|    1    |      □      |     X      |
|    2    |      △      |     Y      |
|    3    |      ×      |     A      |
|    4    |      ○      |     B      |

## Face Buttons: 08C07D3C or 08C07D3D
### 0xY0000000Z - Y can be 2 or 4 (2 is for conditional inputs, 4 is for regular inputs), Z is the button itself.
| Hexadecimal | Buttons |
|:-----------:|:-------:|
|      0      |    *    |
|      1      |    1    |
|      2      |    2    |
|      3      |   1+2   |
|      4      |    3    |
|      5      |   1+3   |
|      6      |   2+3   |
|      7      |  1+2+3  |
|      8      |    4    |
|      9      |   1+4   |
|      A      |   2+4   |
|      B      |  1+2+4  |
|      C      |   3+4   |
|      D      |  1+3+4  |
|      E      |  2+3+4  |
|      F      | 1+2+3+4 |

## Directional Inputs: 08C07D30
#### Uppercase Letters mean 'Hold'
| Hexadecimal | Buttons |
|:-----------:|:-------:|
| 02 | d/b
| 04 | d
| 06 | d or d/b
| 08 | d/f
| 0A | ???
| 0C | ???
| 0E | d/b or d or d/f
| 10 | b
| 12 | d/b or d
| 20 | neutral
| 40 | f
| 48 | f or d/f
| 50 | ???
| 60 | f or nothing
| 70 | on release
| 80 | u/b
| 90 | b or u/b
| D0 | f or b or u/b
| 100 | u
| 120 | ???
| 200 | u/f
| 248 | u/f or f or d/f
| 300 | u or u/f
| 380 | u/b or u or u/f
| 38A | ???
| 3DA | ???
| 3EE | any buttons, except b
| 3F0 | ???
| 402 | D/B
| 404 | D
| 408 | D/F
| 410 | B
| 440 | F
| 480 | U/B
| 8001 | f,f
| 8002 | b,b
| 8003 | u~n (side Step)
| 8004 | d~n (side Step)

## Character Hexadecimal: 08C078B4
| Hexadecimal | Character |
|:-----------:|:---------:|
| 00 | Paul
| 01 | Law
| 02 | Lei
| 03 | King
| 04 | Yoshimitsu
| 05 | Nina
| 06 | Hwoarang
| 07 | Xiaoyu
| 08 | Christie
| 09 | Jin
| 0A | Julia
| 0B | Kuma
| 0C | Bryan
| 0D | Heihachi
| 0E | Kazuya
| 0F | Lee
| 10 | Steve
| 11 | Marduk
| 12 | Jack-6
| 13 | Roger Jr.
| 14 | Anna
| 15 | Wang
| 16 | Ganryu
| 17 | Asuka
| 18 | Bruce
| 19 | Baek
| 1A | Devil Jin
| 1B | Raven
| 1C | Feng
| 1D | Armor King
| 1E | Lili
| 1F | Dragunov
| 20 | Panda
| 21 | Eddy
| 22 | Bob
| 23 | Zafina
| 24 | Miguel
| 25 | Leo
| 26 | Azazel (Unplayable)
| 27 | Nancy (Unplayable)
| 28 | Lars
| 29 | Alisa
| 2A | Player 3?
| 2B | Player 4?
| 2C | Mokujin?

## Hit Ranks: 08C07A08
| Hexadecimal  |           Rank            |
|:---:|---------------------------|
| 10F | Low
| 217 | Mid
| 31F | Special Mid (Projectiles?)
| 41F | Special Mid
| 512 | High
| 707 | Unblockable Mid
| 806 | Unblockable High
| 907 | Unblockable Low
| B07 | High (For Airborne Opponent)

## Body States: 
|   Hexadecimal     |       Status          |
|:--------:|-----------------------|
| 842 | Stand, Can Block
| 6084 | Grounded, Face Up
| 6A84 | Grounded, Face Down
| 7402 | Airborne, Face Up
| 7E02 | Airborne, Face Down
| 8291 | Crouch, Can Block
| A000 | Invulnerable
| E18A | 
| F01A | 

## Visual Recovery:
|  Hexadecimal  |                   Name                   |
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
| 800F | side Step to Left                        |
| 8010 | side Step to Right                       |
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
| 8054 | side Step to Left                        |
| 8055 | side Step to Right                       |
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

# *Note: There might be mistakes from here on out. :-)

## Connection Type
| Hexadecimal | Address | Attribute
|:-:|:-:|---|
| 80 | 0x08E423B0 | Common
| 96 | |
| 182 | 0x08E423C0 | Slight Tracking
| 185 | | Moderate Tracking
| 20F | |
| 214 | |
| 219 | 0x08E423BC |
| 401 | 0x08E423B4 | Parallel Connection
| 402 | | Parallel Connection
| 403 | |
| 404 | |
| 405 | | Parallel Connection
| 1ADC | | Connection to Throw
| 2800 | | Effects
| 8080 | 08E422B8 |
| 9ADC | | Connection to Back Throw

## Permissions: 
<details>
 <summary><b>Jumpscare</b></summary>

| Hex (Tk6) | Hex (TTT2) | Hex (Tk7) | Hex (Tk8) | Attribute |  
|:---------:|:----------:|:---------:|:---------:|-----------|  
| 00        |            |           |           | No Condition |  
| 01        |            |           |           | If Practice Mode |  
| 02        |            | 02        |           | If It Hits |  
| 03        |            | 17        |           | If It Hits Front-Facing Standing Opponent. XXXX is the required distance |  
| 04        |            |           |           | If It Hits Backturned Standing Opponent. XXXX is the required distance |  
| 05        |            |           |           | If It Hits Left-turned Standing Opponent. XXXX is the required distance |  
| 06        |            |           |           | If It Hits Right-turned Standing Opponent. XXXX is the required distance |  
| 07        | 07         | 07        |           | If It Hits Front-Facing Crouching Opponent. XXXX is the required distance |
| 08        | 08         | 08        |           | If It Hits Backturned Crouching Opponent. XXXX is the required distance |  
| 09        | 09         | 09        |           | If It Hits Left-turned Crouching Opponent. XXXX is the required distance |  
| 0A        | 0A         | 0A        |           | If It Hits Right-turned Crouching Opponent. XXXX is the required distance |  
| 0B        |            |           |           | If It Hits Grounded Opponent (Face Up, Feet Away). 0000XXXX is the required distance |
| 0C        |            |           |           | If It Hits Grounded Opponent (Face Up, Feet Towards). 0000XXXX is the required distance |
| 0D        |            |           |           | If It Hits Grounded Opponent (Face Up, Left Side). 0000XXXX is the required distance |
| 0E        |            |           |           | If It Hits Grounded Opponent (Face Up, Right Side). 0000XXXX is the required distance |
| 0F        |            |           |           | If It Hits Grounded Opponent (Face Down, Feet Away). 0000XXXX is the required distance |
| 10        |            |           |           | If It Hits Grounded Opponent (Face Down, Feet Towards). 0000XXXX is the required distance |
| 11        |            |           |           | If It Hits Grounded Opponent (Face Down, Left Side). 0000XXXX is the required distance |
| 12        |            |           |           | If It Hits Grounded Opponent (Face Down, Right Side). 0000XXXX is the required distance |
| 13        |            |           |           |
| 14        |            |           |           |
| 15        |            |           |           |
| 16        |            |           |           |
| 17        | 17         |           |           | If It Hits Front-Facing Standing/Crouching Opponent. 0000XXXX is the required distance |
| 18        | 18         |           |           | If It hits Backturned Standing/Crouching Opponent. 0000XXXX is the required distance |
| 19        | 19         |           |           | If It hits Left-turned Standing/Crouching Opponent. 0000XXXX is the required distance |
| 1A        | 1A         |           |           | If It hits Right-turned Standing/Crouching Opponent. 0000XXXX is the required distance |
| 1B        | 1B         |           |           | If It hits Airborne Opponent (Face Up, Feet Towards). 0000XXXX is the required distance |
| 1C        | 1C         |           |           | If It hits Airborne Opponent (Face Up, Feet Away). 0000XXXX is the required distance |
| 1D        |            |           |           | If It hits Airborne Opponent (Face Up, Left Side). 0000XXXX is the required distance |
| 1E        |            |           |           | If It hits Airborne Opponent (Face Up, Right Side). 0000XXXX is the required distance |
| 1F        |            |           |           | If It hits Airborne Opponent (Face Down, Feet Towards). 0000XXXX is the required distance |
| 20        |            |           |           | If It hits Airborne Opponent (Face Down, Feet Away). 0000XXXX is the required distance |
| 21        |            |           |           | If It hits Airborne Opponent (Face Down, Left Side). 0000XXXX is the required distance |
| 22        |            |           |           | If It hits Airborne Opponent (Face Down, Right Side). 0000XXXX is the required distance |
| 23        |            | 23        |           | If The Opponent's distance < 0000XXXX (min:300, max:1B58) |
| 24        |            | 24        |           | If The Opponent's distance > 0000XXXX (min:300, max:1B58) |
| 25 | 
| 26 | 
| 27 | 
| 28 | 
| 29 | 
| 2A | 
| 2B |  
| 2C       | 2E        | 2C       | 2C       | If Regular Hit |
| 2D       | 31        | 2F       |          | If Opponent Blocked |
| 2E       | 32        | 30       |          | If Attack Whiffs |
| 30 | 
| 31 | 
| 32 | 
| 33 | 
| 34 | 
| 35 | 
| 36       | 3F        | 43       | 42       |  |
| 37       | 40        | 44       | 43       |  |
| 38 | 
| 39 | 
| 3A | 
| 3B | 
| 3C | 
| 3D       |           | 48       |          | If backturned |
| 3E       |           | 49       |          | If not backturned |
| 3F | 
| 40 | 
| 41 | 
| 42       |           | 4D       |          | Related to Throws |
| 43 | 
| 44 | 
| 45       |           | 50       |          | If BT or RT |
| 46       |           | 51       |          | If BT or LT |
| 47 | 
| 48 | 
| 49       |           | 54       |          | If laying on ground and opponent at feet |
| 4A       |           | 55       |          | If laying on ground and opponent at right side |
| 4B       |           | 56       |          | If laying on ground and opponent at left side |
| 4C       |           | 57       |          | If laying on ground and opponent at head |
| 4D       | 5D        | 60       |          | If opponent is facing forward |
| 4E       |           |          |          | If opponent is facing right |
| 4F       |           |          |          | If opponent is facing left |
| 50       |           |          |          | If opponent is backturned |
| 51       |           |          |          | |
| 52       |           |          |          | If opponent's attack is High |
| 53       |           |          |          | |
| 54       |           |          |          | If opponent attacks |
| 55       |           | 67       |          | If opponent's attack frame is XX |
| 56 | 
| 57 | 
| 58 | 
| 59 | 
| 5A | 
| 5B | 
| 5C | 
| 5D | 
| 5E | 
| 5F | 
| 60 | 
| 61 | 
| 62 | 
| 63 | 
| 64 | 
| 65 | 
| 66 | 
| 67 | 
| 68       |           | 7A       |          |  |
| 69 | 
| 6A | 
| 6B | 
| 6C       | 7C        | 7E       |          | If opponent is downed |
| 6D       |           | 7F       |          | If opponent is not downed |
| 6E | 
| 6F | | | | | if opponent is ??
| 70       | 80        | 82       |          | If counterhit |
| 71       |           | 83       |          | If pressed 1 only |
| 72       |           | 84       |          | If pressed 2 only |
| 73       |           | 85       |          | If pressed 1+2 only |
| 74 
| 75       |           | 87       |          | If character is KO'd |
| 76
| 77 
| 78       |           | 8A       |          | If character HP ≥ XX |
| 79
| 7A 
| 7B       |           |          |          | If opponent's HP ≤ XX |
| 7C | 
| 7D | 
| 7E | 
| 7F | 
| 80       |           | 92       |          | If on P1 side |
| 81       |           | 93       |          | If on P2 side |
| 82       |           | 94       |          | if on P2 Side |
| 83       |           | 95       |          | if on P1 Side |
| 84       |           | 96       |          | if on P1 Side |
| 85       |           | 97       |          | if on P2 Side |
| 86       |           | 9B       |          | If KiCharge |
| 87 | 
| 88 | 
| 89 | 
| 8A       |           |          |          | if opponent performs one of the moves from the [registry](https://sadamitsu.ru/cwcheat/registry.htm). 0000XXXX is the start index |
| 8B | 
| 8C | 
| 8D | 
| 8E | 
| 8F       |           | B6       |          | if character is near to the wall (01 = if wall is at the front, 02 = if wall is at the left side, 04 = if wall is at the back, 08 = if wall is at the right side) |
| 90 | 
| 91 | 
| 92 | 
| 93 | 
| 94 | 
| 95 | 
| 96        | AC       |          |          | 
| 97 | | | | 
| 98        |          | D8       |          |
| 99        | 8C       | D9       |          | if character is <Move ID> *see 08C07A18*
| 9A | | | | if character is not <Move ID> *see 08C07A18*
| 9B | | | | if opponent is <Move ID> *see 08C078B4*
| 9C | | | | if opponent is not <Move ID> *see 08C078B4*
| 9D | | | | 
| 9E | | | | 
| 9F | | | | if opponent is <Character Move> *see 08C078B4* (Probably Exclusive to Alisa, look at her u/f+1+2 Throw)
| A0 | 
| A1        | D6       | E1       | E4       | Character Controller
| A2 |
| A3 | 
| A4 | 
| A5 | 
| A6 | 
| A7 | 
| A8 | 
| A9 | 
| AA | 
| AB | 
| AC | 
| AD | 
| AE | 
| AF | 
| B0 | 
| B1
| B2
| B3
| B4
| B5
| B6
| B7 | 
| B8 | E8 (TTT2) | | |
| BA | | FD (Tk7) | | if <<inner KiCharge>> (00 = off, 01 = on)
| BB | 
| BC
| BD
| BE
| BF
| C0
| C1
| C2
| C3
| C4 | | 121 | | 
| C5 |
| C6 | 
| C7
| C8
| C9
| CA
| CB
| CC
| CD
| CE
| CF
| D0
| D1 | 126 | 149 | | if flag XX is set by 805C *see 0407C84*
| D2 |
| D3 |
| D4 | 
| D5 | 
| D6 | 139 | 160 | 166 | if flag XX is set by 8068
| D7
| D8
| D9
| DA
| DB
| DC
| DD
| DE
| DF
| E0
| E1
| E2
| E3
| E4
| E5
| E6 | 
| E7
| E8
| E9
| EA | 
| EB | 184 | 214 | | if character speed > 0000XXXX
| EC | 
| ED
| EE
| EF | 
| F0 | 
| F1 | 
| F2 | 
| F3 | 
| F4 | 
| F5 | 
| F6 | 
| F7 | 
| F8 | 
| F9 | 
| FA | 
| FB | 
| FC | 
| FD | 
| FE | 
| FF | 
| 100 | 
| 102 | 
| 103 | 
| 104 | 
| 105 | 
| 106 | 
| 11E | 1AA | | | 
| 13B | | 261 | | if customisation item is equipped |
| 13E | | | | if Yoshimitsu is not in NSS
| 13F | | | | if Yoshimitsu is in NSS
| 140 | 
| 141 | 
| 142 | 
| 143 | | | | if opponent is airborne
| 144 | | | | if B! is available
| 160      | 285       |          |          | If opponent hits with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against Low Attacks) |
| 161      | 286       | 330      |          | If opponent hits with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against Mid/High Attacks) |
| 162      | 287       |          |          | if opponent hits with one of the moves from the [registry](http://sadamitsu.ru/cwcheat/registry.htm), 0000XXXX is the start index |
| 16E | | | |
| 170      |           |          |          | if opponent hits character with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against High Attacks) |
| 171      |           |          |          | if opponent hits character with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against Mid Attacks) |
| 174      |           |          |          | if opponent hits with one of the moves from the [registry](http://sadamitsu.ru/cwcheat/registry.htm), 0000XXXX is the start index |
| 181      |           |          |          | if opponent hits character with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against High Attacks) |
| 182      |           |          |          | if opponent hits character with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against Mid Attacks) |
| 185      |           |          |          | if opponent hits character with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against High Attacks) |
| 186      |           |          |          | if opponent hits character with 000000XX [limb](https://sadamitsu.ru/cwcheat/limbs.htm) (Against Mid Attacks) |
| 18D      | 2B2       | 371      | 44C      | End of Permission |
|          |           |          |          | |
|          |           |          |          | |
| 8001 | 8001 | 8001 | 8001 |  Camera Shake #1
| 8002 | 8002 | 8002 | 8002 | Camera Shake #2
| 8003 | 8003 | 8003 | 8003 | Camera Shake #3
| 8004 | 8004 | 8004 | 8004 | Camera Shake #4
| 8005 | | | | | Camera Shake #0
| 8006 | 8006 | 8006 | 8006 | Camera Shake #1 (Alt)
| 8007 | 8007 | 8007 | 8007 | Camera Shake #2 (Alt)
| 8008 | 8008 | 8008 | 8008 | Camera Shake #3 (Alt)
| 8009 | 8009 | 8009 | 8009 | Camera Shake #4 (Alt)
| 800A | | | | |Camera Shake *000000XX* XX is the strength
| 800B | 800B | 800B | 800B | Blast Wave on the floor
| 800C | 
| 800D | 
| 800E | 
| 800F (Tk6/Tk7) | 800E (TTT2) | Ground Break Effect
| 8010 | Strong Blast Wave on the floor
| 8011 | Character is on fire (0 | YelLow, 1 | Purple)
| 8012 | Opponent is on fire (0 | YelLow, 1 | Purple)
| 8013 |  
| 8014 | Somewhat related to 8011
| 8015 | Seen on Elemental Reaction: Thunder (Hexadecimalk what it does)
| 8016 | Seen on Elemental Reaction: Thunder (Hexadecimalk what it does)
| 8017 | Seen on Elemental Reaction: Ice (Hexadecimalk what it does)
| 801B | Seen on Elemental Reaction: Ice (Hexadecimalk what it does)
| 801C (Tk6) | 801B (TTT2) | 801E (Tk7) | Steam Comes Out of The Mouth
| 801D (Tk6) | 8067 (TTT2) | 801F (Tk7) | Alisa's Character Specific Visual Effect
| 801E (Tk6) | 801D (TTT2) | 802E (Tk7) | Character Specific Visual Effect
| 801F | Character Specific Visual Effect
| 8020 (Tk6) | 8036 (Tk7) | Character Extra Specific Visual Effects
| 8021 (Tk6) | 8039 (Tk7) | Opponent Specific Visual Effect
| 8022 (Tk6) | 803A (Tk7) | Opponent Extra Visual Effect
| 8023 (Tk6) | 8024 (TTT2) | 803B (Tk7) | Regular Hit Effect
| 8024 | Grapple Indicator (Main)
| 8025 (Tk6) | 8042 (Tk7) | Smoke Effect
| 8026 (Tk6) | 802C (TTT2) | 8043 (Tk7) | Faint Smoke Effect (Doesn't Work in Tk6 PSP)
| 8027 (Tk6) | 802D (TTT2) | Block Effect
| 8028 | Vertical Blast
| 8029 | Strong Vertical Blast
| 802A | Collection of Visual Effects (http:|sadamitsu.ru/cwcheat/802A.htm)
| 802B | Collection of Visual Effects (http:|sadamitsu.ru/cwcheat/802A.htm)
| 802C | 
| 802D (Tk6) | 8048 (Tk7) | Ground Break Effect Under Specific Limb *0000XXYY* (XX is the limb, YY is the mode; 00, 01 or 02)
| 802E | Alisa's Extra Specific Visual Effects
| 802F | 
| 8030 | 
| 8031 | Evil Mist Effect (Specific Characters Only)
| 8032 | 
| 8033 | 
| 8034 | Chain Sparks on the Ground, v1
| 8035 | Chain Sparks on the Ground, v2
| 803C | Steam Comes Out of the Mouth (Same as 801C)
| 803D | Character Specific Visual Effect
| 803E | Character Extra Visual Effect (Same as 8020)
| 803F | Opponent Specific Visual Effect
| 8040 | Opponent Extra Visual Effect (Same as 8022)
| 8041 | Regular Hit Effect (Same as 8023)
| 8042 | Grapple Indicator (Main) (Same as 8024)
| 8043 | Smoke Effect (Same as 8025)
| 8044 | Faint Smoke Effect (Same as 8026)
| 8045 | Block Effect (Same as 8027)
| 8046 | Opponent's Vertical Blast
| 8047 | Opponent's Strong Vertical Blast
| 8048 | Collection of Visual Effects (http:|sadamitsu.ru/cwcheat/802A.htm)
| 8049 | Collection of Visual Effects (http:|sadamitsu.ru/cwcheat/802A.htm)
| 804A | Chain Sparks on the Ground, v1
| 804B | Chain Sparks on the Ground, v2
| 804C | 
| 804D | 
| 804E | 
| 804F (Tk6) | 8058 (TTT2) | 821B (Tk7) | Opponent Damage
| 8050 (Tk6) | 8059 (TTT2) | 821C (Tk7) | Character Damage
| 8051 (Tk6) | 806C (Tk7) | Gain Health
| 8052 | 
| 8053 | 
| 8054 | 
| 8055 (Tk6) | 8062 (TTT2) | ???
| 8056 | 
| 8057 | Countdown Timer for Tk6SC Dialogs
| 8058 (Tk6) | 8066 (TTT2) | 8078 (Tk7) | Launch The <<Inner KiCharge>> timer. XXXX is the time (Current Timer Value in 0407C80)
| 8059 (Tk6) | 8079 (Tk7) | 
| 805A (Tk6) | 807A (Tk7) | 
| 805B (Tk6) | 807B (Tk7) |
| 805C (Tk6) | 806C (TTT2) | 807C (Tk7) | Set flag XX for permission D1 *see 0407CB4*
| 805D | Changes flag XX for permission D1 *see 0407CB4*
| 805E | 
| 805F | 
| 8060 | 
| 8061 | 
| 8062 | 
| 8063 | 
| 8064 | 
| 8065 | 
| 8066 | 
| 8067 | 
| 8068 (Tk6) | 8096 (TTT2) | 80A6 (Tk7) | 80C5 (Tk8) | Set flag XX for permission D6
| 8069 | 
| 806A | 
| 806B | 
| 806C | 
| 806D | 
| 806E | 
| 806F | 
| 8070 | 
| 8071 | 
| 8072 | 
| 8073 | 
| 8074 | 
| 8075 | 
| 8076 | 
| 8077 | 
| 8078 | 
| 8079 | 
| 807A | 
| 807B | 
| 807C | 
| 807D | 
| 807E | 
| 807F | 
| 8080 | 
| 8081 | 
| 8082 | 
| 8083 (Tk6) | 80EA (TTT2) | 817C (Tk7) | Ability to Block
| 8084 (Tk6) | 80EB (TTT2) | 817D (Tk7) | Launch the <<KiCharge>> timer. XXXX is the time (Current Timer Value in 08C07C60)
| 8085 (Tk6) | 80EC (TTT2) | 817E (Tk7) | ???
| 8086 (Tk6) | 80ED (TTT2) | 817F (Tk7) | ???
| 8087 (Tk6) | 80EE (TTT2) | 8180 (Tk7) | ???
| 8088 (Tk6) | 80EF (TTT2) | 8181 (Tk7) | Disconnect of Positions while performing a throw
| 8089 (Tk6) | 
| 808A (Tk6) | 80F3 (TTT2) | 8185 (Tk7) | Disconnect of Height Average while performing a throw, Smoothly
| 808B (Tk6) | 80F4 (TTT2) | 8186 (Tk7) | Disconnect of Height Average while performing a throw, Instantly
| 808C (Tk6) | 80F5 (TTT2) | 8187 (Tk7) | 
| 808D (Tk6) | 80F6 (TTT2) | 8188 (Tk7) | 
| 808E (Tk6) | 80F7 (TTT2) | 8189 (Tk7) | 
| 808F (Tk6) | 80F8 (TTT2) | 818A (Tk7) | 81FA (Tk8) | Tracking (0 | No Tracking, 1 | Homing, 7 | Standard, 12 | Infinite)
| 8090 (Tk6) | 80F9 (TTT2) | 818B (Tk7) | 
| 8091 (Tk6) | 80FA (TTT2) | 818C (Tk7) | Change Body State *see 08C0796C*
| 8092 (Tk6) | 
| 8093 (Tk6) | 
| 8094 (Tk6) | 80FB (TTT2) | 818D (Tk7) | Return to Position after performing a throw
| 8095 (Tk6) | Set size of CollHexadecimalers *XXXX, 0000 | 0%, 1000 | 100%*
| 8096 (Tk6) | 
| 8097 (Tk6) | 8100 (TTT2) | 8193 (Tk7) | Footstep SFX
| 8098 (Tk6) | 
| 8099 (Tk6) | 
| 809A (Tk6) | 8196 (Tk7) | Character can be Lower ground level (00 | off, 01 | on)
| 809B | 
| 809C (Tk6) | 8105 (TTT2) | Every 1st Frame
| 809D | 
| 809E (Tk6) | 8106 (TTT2) | Removes breaking ground effect while airborne
| 809F | 
| 80A0 | 
| 80A1 (Tk6) | 81A3 (Tk7) | ???
| 80A2 (Tk6) | 81A4 (Tk7) | Returns Direction while performing a throw
| 80A3 | 
| 80A4 | 
| 80A5 | Alisa's items can pass though walls
| 80A6 | 
| 80A7 | 
| 80A8 | 
| 80A9 | 
| 80AA | 
| 80AB (Tk6) | 81C8 (Tk7) | Skip XX frames of the folLowing move
| 80B6 | 
| 80B7 (Tk6) | 8128 (TTT2) | 81D4 (Tk7) | Opponent will perform a move from character base
| 80B8 | Opponent will perform a move from character base
| 80B9 | 
| 80BA (Tk6) | 812A (TTT2) | 81D6 (Tk7) | Set Character Speed
| 80BB (Tk6) | 812B (TTT2) | 81D7 (Tk7) | Change Character Speed
| 80BC | Set Opponent Speed
| 80BD | Change Opponent Speed
| 80BE | Set Value for *08C07978*
| 80BF (Tk6) | 812F (TTT2) | 81DB (Tk7) | Set Value for *08C0797C*
| 80C0 | Character will perform a move from character base
| 80C1 |
| 80C2 | Character Ghost will perform a move
| 80C3 | 
| 80C4 | 
| 80C5 | 
| 80C6 | 
| 80C7 (Tk6) | 8138 (TTT2) | 81E4 (Tk7) | Floor Break F!
| 80C8 (Tk6) | 8139 (TTT2) | 81E5 (Tk7) | Rotation of the Character when the Floor Breaks F!
| 80C9 | 
| 80CA | 
| 80CB (Tk6) | 100% Scaling? (00 | Off, 01 | On)
| 80CC | 
| 80CD | 
| 80CE | 
| 80CF | 
| 80D5 (Tk6) | 8145 (TTT2) | 81F2 (Tk7) | Laser Launcher
| 80D6 (Tk6) | 8146 (TTT2) | 81F3 (Tk7) | Laser Mode
| 80D7 (Tk6) | 8147 (TTT2) | 81F4 (Tk7) | Laser Stopper
| 80DF (Tk6) | Change Character Position
| 80E0 (Tk6) | Direction of Character Changing Position
| 80E1 | 
| 80E2 | Change Character Rotation
| 80E3 | Change Opponent Rotation
| 80E4 | 
| 80E5 | 
| 80E6 (Tk6) | Change Character Height
| 80ED (Tk6) | Character Disappears, including VFX
| 80EF (Tk6) | Opponent Disappears, including VFX
| 80FB (Tk6) | Subtitles
| 80FC | 
| 80FD (Tk6) | Tk6SC Dialogue Subtitles *00XX00YY*
| 80FE | 
| 80FF (Tk6) | Reset Camera Position
| 8100 | 
| 8101 | 
| 8102 | 
| 8103 (Tk6) | Clothes Position
| 8108 | 
| 8109 (Tk6) | 8184 (TTT2) | ???
| 810C | 
| 810D (Tk6) | 8188 (TTT2) | 824A (Tk7) | ???
| 810E (Tk6) | 8189 (TTT2) | 824B (Tk7) | ???
| 810F (Tk6) | 818A (TTT2) | 824C (Tk7) | Combo Meter Reset on XX frame *000000XX*
| 8110 | 
| 8111 (Tk6) | 818B (TTT2) | ???
| 8112 (Tk6) | Combo Meter Does Not Reset
| 8113 | 
| 8114 | 
| 8115 (Tk6) | 8251 (Tk7) | Character Disappears, without VFX (01 | Disappear, 02 >| Flicker)
| 8116 (Tk6) | 8252 (Tk7) | Opponent Disappears, without VFX (01 | Disappear, 02 >| Flicker)
| 8117 | 
| 8118 | 
| 8119 | 
| 811A | 
| 811B | 
| 811C | 
| 811D | 
| 811E | 
| 811F | 
| 8120 (Tk6) | 8193 (TTT2) | 8255  (Tk7) | Spend Bound '*Screw (Tk7)'
| 8125 (Tk6) | Item Move, attach item to XX limb
| 8126 (Tk6) | Item Move, switch on
| 8127 (Tk6) | Item Move, Reset
| 8128 (Tk6) | Item Move, Activate
| 8129 (Tk6) | Projectile Item Move, Projectile's Forward/Backward Movement Speed
| 812A (Tk6) | Projectile Item Move, Projectile's Upward/Downward Movement Speed
| 812B (Tk6) | Projectile Item Move, slot of Stand Reaction
| 812C (Tk6) | Projectile Item Move, slot of Air Reactions
| 812D | 
| 812E (Tk6) | Projectile Item Move, Damage
| 812F (Tk6) | Projectile Item Move, Hit Rank
| 8130 (Tk6) | Projectile Item Move, Gravitation
| 8131 (Tk6) | Item Move, Shift Attack Point *0000XXYY* (XX | ITEM/YY | Distance)
| 8132 | 
| 8133 | 
| 8134 (Tk6) | Projectile Item Move, Iteam Appears
| 8135 | 
| 8136 (Tk6) | Projectile Item Move, Reset
| 8137 | 
| 8138 | 
| 8139 | 
| 813A | 
| 813B | 
| 813C | 
| 813D | 
| 813E | 
| 813F | 
| 8140 (Tk6) | Projectile Item Move, Launch
| 8141 | 
| 8142 | 
| 8143 | 
| 8144 (Tk6) | Yoshimitsu's Left Hand Sword (0 | off, 1 | on)
| 8145 (Tk6) | Yoshimitsu's Right Hand Sword (0 | off, 1 | on)
| 8146 (Tk6) | Yoshimitsu's Left Hand Sword Effects (0 | off, 1 | on)
| 8147 (Tk6) | Yoshimitsu's Right Hand Sword Effects (0 | off, 1 | on)
| 8148 (Tk6) | 81A9 (TTT2) | 826A (Tk7) | Homing Effect for LP (0 | off, 1 | on)
| 8149 (Tk6) | 81AA (TTT2) | 826B (Tk7) | Homing Effect for RP (0 | off, 1 | on)
| 814A (Tk6) | 81AB (TTT2) | 826C (Tk7) | Homing Effect for LK (0 | off, 1 | on)
| 814B (Tk6) | 81AC (TTT2) | 826D (Tk7) | Homing Effect for RK (0 | off, 1 | on)
| 814C (Tk6) | 81AD (TTT2) | Homing Effect for Tail (0 | off, 1 | on)
| 814D (Tk6) | 
| 814E (Tk6) | Rage Mode (00 | off, 01 | on)
| 814F (Tk6) | 8273 (Tk7) | ???
| 8150 (Tk6) | 
| 8151 (Tk6) |
| 8152 (Tk6) |
| 8153 (Tk6) |
| 8154 (Tk6) | 
| 8155 (Tk6) | 
| 8156 (Tk6) | 
| 8157 (Tk6) | 
| 8158 (Tk6) | 
| 8159 (Tk6) | 
| 815A (Tk6) | 
| 815B (Tk6) | 
| 815C (Tk6) |
| 815D (Tk6) | 
| 815E (Tk6) | 
| 815F (Tk6) | 
| 8160 (Tk6) |
| 8161 (Tk6) | 
| 8162 (Tk6) | 
| 8163 (Tk6) | 8230 (TTT2) | 8387 (Tk7) | Alisa's Rocket Thrust Effects Appears (0 | Left Leg, 1 | Right Leg, 2 | Wings)
| 8164 (Tk6) | 8231 (TTT2) | 8388 (Tk7) | Alisa's Rocket Thrust Effects Disappears (0 | Left Leg, 1 | Right Leg, 2 | Wings)
| 8165 (TK6) | 8232 (TTT2) | 8389 (Tk7) | Alisa's Saws Appears (00 | Left Hand Saw, 01 | Right Hand Saw)
| 8166 (Tk6) | 8233 (TTT2) | 838A (Tk7) | Alisa's Saws Disappears (00 | Left Hand Saw, 01 | Rught Hand Saw)
| 8167 (Tk6) | 8234 (TTT2) | 838B (Tk7) | Alisa's Items Attached (0 | Head, 1 | Left Hand, 2 | Right Hand, 3 | Torso)
| 8168 (Tk6) | 8235 (TTT2) | 838C (Tk7) | Alisa's Items Detached (0 | Head, 1 | Left Hand, 2 | Right Hand, 3 | Torso)
| 8169 (Tk6) | 8236 (TTT2) | 838D (Tk7) | ???
| 816A (Tk6) |  
| 816B (Tk6) |  
| 816C (Tk6) |  
| 816D (Tk6) |  
| 816E (Tk6) | 823B (TTT2) | 8392 (Tk7) | Alisa's Flaps (2A | Appears on Left Hand, 2B | Disappears on Left Hand, 2C | Appears on Right Hand, 2D | Disappears on Right Hand)
| 816F (Tk6) | | 
| 8170 (Tk6) | |
| 8171 (Tk6) | | 
| 8172 (Tk6) | | 
| 8173 (Tk6) | | 
| 8174 (Tk6) | | Change Character's 8000 to XXX
| 8175 (Tk6) | | Change Character's 8001 to XXX
| 8176 (Tk6) | | Change Character's 8002 to XXX
| 8177 (Tk6) | | Change Character's 8003 to XXX
| 8178 (Tk6) | | Change Character's 8004 to XXX
| 8179 (Tk6) | | Change Character's 8005 to XXX
| 817A (Tk6) | | Change Character's 8006 to XXX
| 817B (Tk6) | | Change Character's 8007 to XXX
| 817C (Tk6) | | Change Character's 8008 to XXX
| 817D (Tk6) | | Change Character's 8009 to XXX
| 817E (Tk6) | | Change Character's 800A to XXX
| 817F (Tk6) | | Change Character's 800B to XXX
| 8180 (Tk6) | | Change Character's 800C to XXX
| 8181 (Tk6) | | Change Character's 800D to XXX
| 8182 (Tk6) | | Change Character's 800E to XXX
| 8183 (Tk6) | | Change Character's 800F to XXX
| 8184 (Tk6) | | Change Character's 8010 to XXX
| 8185 (Tk6) | | Change Character's 8011 to XXX
| 8186 (Tk6) | | Change Character's 8012 to XXX
| 8187 (Tk6) | | Change Character's 8013 to XXX
| 8188 (Tk6) | | Change Character's 8014 to XXX
| 8189 (Tk6) | | Change Character's 8015 to XXX
| 818A (Tk6) | | Change Character's 8016 to XXX
| 818B (Tk6) | | Change Character's 8017 to XXX
| 818C (Tk6) | | Change Character's 8018 to XXX
| 818D (Tk6) | | Change Character's 8019 to XXX
| 818E (Tk6) | | Change Character's 801A to XXX
| 818F (Tk6) | | Change Character's 801B to XXX
| 8190 (Tk6) | | Change Character's 801C to XXX
| 8191 (Tk6) | | Change Character's 801D to XXX
| 8192 (Tk6) | | Change Character's 801E to XXX
| 8193 (Tk6) | | Change Character's 801F to XXX
| 8194 (Tk6) | | Change Character's 8020 to XXX
| 8195 (Tk6) | | Bring Character's 8000 Move Number to default
| 8196 (Tk6) | | Bring Character's 8001 Move Number to default
| 8197 (Tk6) | | Bring Character's 8002 Move Number to default
| 8198 (Tk6) | | Bring Character's 8003 Move Number to default
| 8199 (Tk6) | | Bring Character's 8004 Move Number to default
| 819A (Tk6) | | Bring Character's 8005 Move Number to default
| 819B (Tk6) | | Bring Character's 8006 Move Number to default
| 819C (Tk6) | | Bring Character's 8007 Move Number to default
| 819D (Tk6) | | Bring Character's 8008 Move Number to default
| 819E (Tk6) | | Bring Character's 8009 Move Number to default
| 819F (Tk6) | | Bring Character's 800A Move Number to default
| 81A0 (Tk6) | | Bring Character's 800B Move Number to default
| 81A1 (Tk6) | | Bring Character's 800C Move Number to default
| 81A2 (Tk6) | | Bring Character's 800D Move Number to default
| 81A3 (Tk6) | | Bring Character's 800E Move Number to default
| 81A4 (Tk6) | | Bring Character's 800F Move Number to default
| 81A5 (Tk6) | | Bring Character's 8010 Move Number to default
| 81A6 (Tk6) | | Bring Character's 8011 Move Number to default
| 81A7 (Tk6) | | Bring Character's 8012 Move Number to default
| 81A8 (Tk6) | | Bring Character's 8013 Move Number to default
| 81A9 (Tk6) | | Bring Character's 8014 Move Number to default
| 81AA (Tk6) | | Bring Character's 8015 Move Number to default
| 81AB (Tk6) | | Bring Character's 8016 Move Number to default
| 81AC (Tk6) | | Bring Character's 8017 Move Number to default
| 81AD (Tk6) | | Bring Character's 8018 Move Number to default
| 81AE (Tk6) | | Bring Character's 8019 Move Number to default
| 81AF (Tk6) | | Bring Character's 801A Move Number to default
| 81B0 (Tk6) | | Bring Character's 801B Move Number to default
| 81B1 (Tk6) | | Bring Character's 801C Move Number to default
| 81B2 (Tk6) | | Bring Character's 801D Move Number to default
| 81B3 (Tk6) | | Bring Character's 801E Move Number to default
| 81B4 (Tk6) | | Bring Character's 801F Move Number to default
| 81B5 (Tk6) | | Bring Character's 8020 Move Number to default
| 81B6 (Tk6) | 
| 81B7 (Tk6) | | 
| 81B8 (Tk6) | | 
| 81B9 (Tk6) | | 
| 81BA (Tk6) | | Raven's Ghost performs a XXX move (Can be used by any character)
| 81BB (Tk6) | | Raven's Ghost Disappears (Can be used by any character)
| 81BC (Tk6) | | Switch sides
| 81BD | 
| 81BE | 
| 81BF | 
| 81C0 | 
| 81C1 | 
| 81C2 (Tk6) | 82D5 (TTT2) | 8248 (Tk7) | 860A (Tk8) | Gesture for Both Hands
| 81C3 (Tk6) | 82D6 (TTT2) | 8249 (Tk7) | 860B (Tk8) | Gesture for Left Hand
| 81C4 (Tk6) | 82D7 (TTT2) | 824A (Tk7) | 860C (Tk8) | Gesture for Right Hand
| 81C5 (Tk6) | 82D9 (TTT2) | 824B (Tk7) | 860D (Tk8) | Gesture for Both Hands
| 81C6 (Tk6) | 82DA (TTT2) | Gesture Animation for Both Hands
| 81C7 (Tk6) | 82DB (TTT2) | 824E (Tk7) | Gesture Animation for Left Hand
| 81C8 (Tk6) | 82DC (TTT2) | 824F (Tk7) | Gesture Animation for Right Hand
| 81C9 | 
| 81CA | 
| 81CB (Tk6) | 8435 (Tk7) | Camera Anim for Cutscenes, Based on Character Coordinates
| 81CC | 
| 81CD | Camera Anim for Cutscenes, Based on Stage Coordinates
| 81CE | 
| 81CF (Tk6) | 82E9 (TTT2) | 843C (Tk7) | Camera Mode for Throws
| 81D0 | | Camera Anim for Cutscene, Based on Character Coordinates ("Maybe?" 843D in Tk7)
| 81D1 | 
| 81D2 | 
| 81D3 |
| 81D4 | 
| 81D5 | 
| 81D6 | 
| 81D7 | 
| 81D8 | 
| 81D9 | 
| 81DA | 
| 81DB | 
| 81DC | 
| 81DD | 
| 81DE | 
| 81DF (Tk6) | 8286 (TTT2) | 84C1 (Tk7) | Facial Expression *0000XXYY* (XX | Expression Number, YY | Smoothing)
| 81E0 (Tk6) | 84C2 (Tk7) | Facial Animation
| 81E1 | 
| 81E2 | 
| 81E3 | 
| 81E4 (Tk6) | 82F9 (TTT2) | 84C4 (Tk7) | 87F0 (Tk8) | Play Sound from Character's Base (XX0000YY *XX is the folder, YY is the sound*)
| 81E5 (Tk6) | 82FB (TTT2) | 84C6 (Tk7) | Play Sound from Opponent's Base (XX0000YY *XX is the folder, YY is the sound*)
| 81E6 (Tk6) | 
| 81E7 (Tk6) | 84CB (Tk7) | Audio Track for Cutscenes
| 81E8 (Tk6) | 8301 (TTT2) | 84CC (Tk7) | Set of Camera Effects
| 81F0 (Tk6) | 
| 8203 (Tk6) | 230B (TTT2) | 853D (TK7) | ???

| I haven't found the T6 equivalent yet
| 12D (TTT2) | 385 (Tk7) | ???
| 1CA (TTT2) | 2CD (Tk8) | ???
| 1E4 (TTT2) | 2E6 (Tk7) | ???
| 1E5 (TTT2) | 3BB (Tk8) | ???
| 8093 (TTT2) | 80A3 (Tk7) | ???
| 8189 (TTT2) | 824B (Tk7) | ???
| 81B4 (TTT2) | ???
| 81B5 (TTT2) | 85D6 (Tk7) | ???
| 81BC (TTT2) | 827E (Tk7) | ??? (Can be seen on Bryan's d+3+4,2~D/B at |>38)
| 81BD (TTT2) | 827F (Tk7) | ???
| 8258 (TTT2) | 83AD (Tk7) | ??? (Can be seen on Jin's b,f+2,3 at |>38)
| 8259 (TTT2) | 83AE (Tk7) | ??? (Can be seen on Jin's b,f+2,3 at |>14)
| 825D (TTT2) | 83B2 (Tk7) | ??? (Can be seen on Jin's f+1+2 [2] at |>38)
| 825F (TTT2) | 83B4 (Tk7) | ???

| 9D (Tk7) | if Rage is activated *000000XX* (00 | off, 01 | on)
| 8069 (Tk7) | ???
| 8211 (Tk7) | ??? (Can be seen on Tk7 Kazuya's CD+3 at |>38)
| 8212 (Tk7) | ??? (Can be seen on Tk7 Kazuya's CD+3 at |>38)
| 8236 (Tk7) | ???
| 82A3 (Tk7) | ???
| 82A4 (Tk7) | ???
| 82B8 (Tk7) | ???
| 82C8 (Tk7) | Framedata Corrector
| 82C9 (Tk7) | Framedata Corrector
| 82CB (Tk7) | ??? (Can be seen on Tk7 Bryan's d+2 at |>14)
| 82D4 (Tk7) | ??? (Can be seen on T7 Armor King's f+1+4 at |>38)
| 82DB (Tk7) | ??? (Can be seen on Tk7 Armor King's f,f+4 at |>38)
| 82E9 (Tk7) | ???
| 84D1 (Tk7) | ???

| 1C5 (Tk8) | ???
| 83C3 (Tk8) | ???
</details>

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
1AC0 - SP Rage (YelLow)
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
272C - Aura (YelLow)
27A0 - Ki (Blue)
2B40 - Ki (Green)
2A58 - Ki (Pink)
2888 - Ki (Purple)
2970 - Ki (Red)
2C28 - Ki (White)
2C9C - Ki (YelLow)
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



# Audio Tracks
## Folder 1: SFX
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
## Folder 2: Grunts
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

## eda
Exploratory Data Analaysis

**Key Interesting Features** :
    - household
    - 1W Rolling Week
    - product type purchased
    - channel

### Sub-Tasks:
- Visual Exploration
- Relationships between features
- Tabular exploration / numeric



### Feature: PACKAGE 

> dataset : the original PHILIPPINES_BEVERAGE_PURCHASE_HHP_CLEANED.csv
>
> Description convention of Distribution:
>
> - `most`: >= larger than 5 times (based on 1000)
> - `1st`, `2nd`, `3rd`: within 10 times 

|      | Package Type             | Distribution                                                 | Sample                                                       |
| ---- | ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | Null                     | 1st: `INSTANT COFFEE` <br>2nd: `UHT MILK` <br>3rd: `DRINKING WATER / MINERAL WATER`, `SOFTDRINKS` |                                                              |
| 2    | BAG / POUCH              | only 1 in `POWER SPORTS / ENERGY DRINK`                      |                                                              |
| 3    | BOTTLE                   | only 1 in `POWER SPORTS / ENERGY DRINK`                      |                                                              |
| 4    | BOTTLED WATER            | Only in `DRINKING WATER/MINERAL WATER`                       | ![4bottled_water.jfif](img_package_type\4bottled_water.jfif) |
| 5    | BOX                      | Most: `INSTANT COFFEE` <br> Few: `POWER SPROTS / ENERY DRINK` | ![5box.jfif](img_package_type\5box.jfif)                     |
| 6    | BOX (STICK)              | only 98 in `INSTANT COFFEE`                                  | ![6box_stick.jfif](img_package_type\6box_stick.jfif)         |
| 7    | CAN                      | Most: `LIQUID / RTD JUICE` <br>2nd: `SOFTDRINKS` <br>3rd: `UHT MILK` | ![7can.jfif](img_package_type\7can.jfif)                     |
| 8    | DISPENSER                | only in `DRINKING WATER/MINERAL WATER`                       | ![8dispenser.jfif](img_package_type\8dispenser.jfif)         |
| 9    | DOY PACK                 | most: `LIQUID / RTD JUICE` <br>2nd: `UHT MILK` <br>3rd: `INSTANT COFFEE` | ![9doy_pack.jfif](img_package_type\9doy_pack.jfif)           |
| 10   | DOY PACK (RESEALABLE)    | only in `INSTANT COFFEE`                                     | ![10doy_pack_resealable.jfif](img_package_type\10doy_pack_resealable.jfif) |
| 11   | DOY PACK (W/ TWIST TOP)  | only in `LIQUID / RTD JUICE`                                 | ![11doy_pack_w_twist_top.jfif](img_package_type\11doy_pack_w_twist_top.jfif) |
| 12   | FOIL PACK                | only 92 in `LIQUID / RTD JUICE`                              | ![12foil_pack.jfif](img_package_type\12foil_pack.jfif)       |
| 13   | FOIL PACK (W/ TWIST TOP) | only 5 in `LIQUID / RTD JUICE`                               | ![13foil_pack_w_twist_top.jfif](img_package_type\13foil_pack_w_twist_top.jfif) |
| 14   | GLASS BOTTLE             | most: `SOFTDRINKS` <br>2nd: `LIQUID / RTD SPROTS / ENERGY D`<br>3rd: `INSTANT COFFEE`<br>4th: `LIQUID / RTD JUICE`<br>5th: `UHT MILK` | ![14glass_bottle.jfif](img_package_type\14glass_bottle.jfif) |
| 15   | HARD PAPER               | only 50 in `INSTANT COFFEE`                                  | ![15hard_paper.jfif](img_package_type\15hard_paper.jfif)     |
| 16   | MASON JAR                | only 16 in `INSTANT COFFEE`                                  | ![16mason_jar.jfif](img_package_type\16mason_jar.jfif)       |
| 17   | MUG                      | only 129 in `INSTANT COFFEE`                                 | ![17mug.jfif](img_package_type\17mug.jfif)                   |
| 18   | PLASTIC BOTTLE           | most: `SOFTDRINKS`<br>2nd: `LIQUID / RTD SPORTS / ENERGY D`<br>3rd: `LIQUID / RTD JUICE`<br>4tht: `INSTANT COFFEE`<br>5th: `UHT MILK` | ![18plastic_bottle.jfif](img_package_type\18plastic_bottle.jfif) |



|      | Package Type                 | Distribution                                                 | Sample                                                       |
| ---- | ---------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 19   | PLASTIC BOTTLE W/ SPORTS CAP | only 17 in `LIQUID / RTD SPORTS / ENERGY D`                  | ![19plastic_bottle_w_sports_capjfif.jfif](img_package_type\19plastic_bottle_w_sports_capjfif.jfif) |
| 20   | PLASTIC CELLOPHANE           | only 316 in `INSTANT COFFEE`                                 | ![20plastic_cellophane.jfif](img_package_type\20plastic_cellophane.jfif) |
| 21   | PLASTIC CUP                  | only in `LIQUID / RTD JUICE`                                 | ![21plastic_cup.jfif](img_package_type\21plastic_cup.jfif)   |
| 22   | PLASTIC PACK                 | only in `INSTANT COFFEE`                                     | ![22plastic_pack.jfif](img_package_type\22plastic_pack.jfif) |
| 23   | PLASTIC PACK (REFILL)        | only 14 in `INSTANT COFFEE`                                  |                                                              |
| 24   | PLASTIC PACK (STICK)         | only in `INSTANT COFFEE`                                     | ![24plastic_pack_stick.jfif](img_package_type\24plastic_pack_stick.jfif) |
| 25   | PLASTIC POUCH                | only 1 in `INSTANT COFFEE`                                   |                                                              |
| 26   | POLY BAG                     | only 1 in `INSTANT COFFEE`                                   |                                                              |
| 27   | REFILL                       | only in `INSTANT COFFEE`                                     |                                                              |
| 28   | SACHET                       | most: `INSTANT COFFEE`<br>2nd: `POWER SPORTS / ENERGY DRINK` | ![28sachet.jfif](img_package_type\28sachet.jfif)             |
| 29   | SACHET (DUO / TWIN PACK)     | only in `INSTANT COFFEE`                                     | ![29sachet_duo_twin_pack.jfif](img_package_type\29sachet_duo_twin_pack.jfif) |
| 30   | STICK                        | only in `INSTANT COFFEE`                                     | ![30stick.jfif](img_package_type\30stick.jfif)               |
| 31   | STYRO CUP                    | only 1 in `INSTANT COFFEE`                                   | ![31styro_cup.jfif](img_package_type\31styro_cup.jfif)       |
| 32   | TETRA PACK                   | most: `UHT MILK`<br>2nd: `LIQUID / RTD JUICE`                | ![32tetra_pack.jfif](img_package_type\32tetra_pack.jfif)     |
| 33   | TETRA PACK (W/ TWIST TOP)    | only in `LIQUID / RTD JUICE`                                 | ![33tetra_pack_w_twis_top.jfif](img_package_type\33tetra_pack_w_twis_top.jfif) |
| 34   | UTILITY JAR                  | only 9 in `INSTANCT COFFEE`                                  | ![34utility_jar.jfif](img_package_type\34utility_jar.jfif)   |

 
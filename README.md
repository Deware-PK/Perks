# Perks
Perks plugin which add special ability to players who has perks' item inside their inventory.\
It also compatible with AirdropX ( By Deware ) and WeaponMechanics( By DeeCaaD )

Configuration: (You can find out what special ability that this plugin have below Buff section)

```
# Available perk type: PHYSICAL , PROJECTILE , WEAPON

AllBuffs:
  Custom_Name: '&6&AllBuffs'
  Material: APPLE
  Description:
  - ''
  - Apple which will give
  - you ability of speed
  Type: PHYSICAL
  Custom_Model_Data: 40051
  Data:
    Buff:
      Acceleration: 1
      Jump: 2
      Resistance_Confustion: true
      Resistance_Poison: true
      Resistance_Slowness: true
      Resistance_Wither: true
      Resistance_All_Potion: true
      Resistance_All_Bad_Potion: true
      Absorption:
        Amplifier: 1
        Duration: 30
      Confusion_To_Victims:
        Percentage: 2
        Amplifier: 1
        Duration: 10
      Poison_To_Victims:
        Percentage: 2
        Amplifier: 1
        Duration: 10
      Slowness_To_Victims:
        Percentage: 2
        Amplifier: 1
        Duration: 10
      Wither_To_Victims:
        Percentage: 2
        Amplifier: 1
        Duration: 10
      Reduce_Reload_Time: 20
      Reduce_Damage: 5.5
      Reduce_Rifle_Damage: 6.2
      Reduce_Explosive_Damage: 9.3
      Reduce_SMG_Damage: 4.4
      Reduce_LMG_Damage: 3.5
      Reduce_Sniper_Damage: 7.6
      Increase_Zooming_Range: 2.1
      Killed_And_Get_Speed:
        Amplifier: 1
        Chance: 50
        Duration: 3

```

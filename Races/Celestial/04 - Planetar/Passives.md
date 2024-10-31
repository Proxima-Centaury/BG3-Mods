# Planetar Passives

### RotER_Planetar_Base_Racial_Speed ( Replaces Base Racial Speed `Passive` )
```markdown
DisplayName :
> Base Racial Speed

Description :
> You can move [1] per turn.

DescriptionParams :
> Distance(12);

Icon :
> DEFAULT

Properties :
> Highlighted

Boosts :
> ActionResource(Movement, 12, 0);
```

### RotER_Planetar_Truesight ( Replaces Darkvision `Passive` )
```markdown
DisplayName :
> Truesight

Description :
> You can see in the dark up to [1], see INVISIBLE creatures and gain ADVANTAGE on Dexterity SAVINGTHROWS.

DescriptionParams :
> Distance(18);

DescriptionTooltips :
<LSTag Type="Status" Tooltip="INVISIBLE">Invisible</LSTag>
<LSTag Tooltip="Advantage">Advantage</LSTag>
<LSTag Tooltip="SavingThrow">Saving Throws</LSTag>

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> DarkvisionRangeMin(18);
> ActiveCharacterLight(233033a1-b43a-4ad9-976a-8a062b345e21);
> ApplyStatus(TRUESIGHT, 100, -1);
> ApplyStatus(SEE_INVISIBILITY, 100, -1);
> Advantage(SavingThrow, Dexterity);
```

### RotER_Planetar_Divine_Awareness
```markdown
DisplayName :
> Divine Awareness

Description :
> You can sense and read other creatures thoughts.

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> ApplyStatus(DETECT_THOUGHTS, 100, -1);
```

### RotER_Planetar_Celestial_Weapons_Lvl_1
```markdown
DisplayName :
> Celestial Weapons Lv.1

Description :
> As an Angel, your weapons are infused with radiant energy, inflicting additional [1].

DescriptionParams :
> DealDamage(1d6, Radiant);

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> CharacterWeaponDamage(1d6, Radiant);
```

### RotER_Planetar_Celestial_Weapons_Lvl_2 ( Replaces Lv.1 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.2

Description :
> As an Angel, your weapons are infused with radiant energy, inflicting additional [1].

DescriptionParams :
> DealDamage(1d8, Radiant);

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> CharacterWeaponDamage(1d8, Radiant);
```

### RotER_Planetar_Celestial_Weapons_Lvl_3 ( Replaces Lv.2 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.3

Description :
> As an Angel, your weapons are infused with radiant energy, inflicting additional [1].

DescriptionParams :
> DealDamage(2d8, Radiant);

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> CharacterWeaponDamage(2d8, Radiant);
```

### RotER_Planetar_Celestial_Weapons_Lvl_4 ( Replaces Lv.3 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.4

Description :
> As an Angel, your weapons are infused with radiant energy, inflicting additional [1].

DescriptionParams :
> DealDamage(3d8, Radiant);

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> CharacterWeaponDamage(3d8, Radiant);
```

### RotER_Planetar_Celestial_Weapons_Lvl_5 ( Replaces Lv.4 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.5

Description :
> As an Angel, your weapons are infused with radiant energy, inflicting additional [1].

DescriptionParams :
> DealDamage(4d8, Radiant);

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> CharacterWeaponDamage(4d8, Radiant);
```

### RotER_Planetar_Celestial_Weapons_Lvl_6 ( Replaces Lv.5 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.6

Description :
> As an Angel, your weapons are infused with radiant energy, inflicting additional [1].

DescriptionParams :
> DealDamage(5d8, Radiant);

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> CharacterWeaponDamage(5d8, Radiant);
```
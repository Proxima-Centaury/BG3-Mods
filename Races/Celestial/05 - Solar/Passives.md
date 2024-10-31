# Solar Passives

### RotER_Solar_Base_Racial_Speed ( Replaces Base Racial Speed `Passive` )
```markdown
DisplayName :
> Base Racial Speed

Description :
> You can move [1] per turn.

DescriptionParams :
> Distance(15);

Icon :
> DEFAULT

Properties :
> Highlighted

Boosts :
> ActionResource(Movement, 15, 0);
```

### RotER_Solar_Truesight ( Replaces Darkvision `Passive` )
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
> DarkvisionRangeMin(24);
> ActiveCharacterLight(e278f6a0-26d7-49be-b11a-9b84bc313c3c);
> ApplyStatus(TRUESIGHT, 100, -1);
> ApplyStatus(SEE_INVISIBILITY, 100, -1);
> Advantage(SavingThrow, Dexterity);
```

### RotER_Solar_Divine_Awareness
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

### RotER_Solar_Immunity
```markdown
DisplayName :
> Immunity

Description :
> You are immune to necrotic and poison damages.

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> Resistance(Necrotic, Immune);
> Resistance(Poison, Immune);
```

### RotER_Solar_Resilience ( Replaces Resilience `Passive` )
```markdown
DisplayName :
> Resilience

Description :
> You are gifted with immunity against CHARMED, EXHAUSTED, FRIGHTENED and POISONED statuses.

DescriptionTooltips :
<LSTag Type="Status" Tooltip="CHARMED">charmed</LSTag>
<LSTag Type="Status" Tooltip="EXHAUSTED">exhausted</LSTag>
<LSTag Type="Status" Tooltip="FRIGHTENED">frightened</LSTag>
<LSTag Type="Status" Tooltip="POISONED">poisoned</LSTag>

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> StatusImmunity(CHARMED);
> StatusImmunity(SG_Charmed);
> StatusImmunity(EXHAUSTED);
> StatusImmunity(SG_Exhausted);
> StatusImmunity(FRIGHTENED);
> StatusImmunity(SG_Frightened);
> StatusImmunity(POISONED);
> StatusImmunity(SG_Poisoned);
```

### RotER_Solar_Celestial_Weapons_Lvl_1
```markdown
DisplayName :
> Celestial Weapons Lv.1

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

### RotER_Solar_Celestial_Weapons_Lvl_2 ( Replaces Lv.1 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.2

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

### RotER_Solar_Celestial_Weapons_Lvl_3 ( Replaces Lv.2 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.3

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

### RotER_Solar_Celestial_Weapons_Lvl_4 ( Replaces Lv.3 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.4

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

### RotER_Solar_Celestial_Weapons_Lvl_5 ( Replaces Lv.4 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.5

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

### RotER_Solar_Celestial_Weapons_Lvl_6 ( Replaces Lv.5 `Passive` )
```markdown
DisplayName :
> Celestial Weapons Lv.6

Description :
> As an Angel, your weapons are infused with radiant energy, inflicting additional [1].

DescriptionParams :
> DealDamage(6d8, Radiant);

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> CharacterWeaponDamage(6d8, Radiant);
```
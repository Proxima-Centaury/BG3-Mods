# Paragon Passives

### RotER_Paragon_Base_Racial_Speed ( Replaces Base Racial Speed `Passive` )
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

### RotER_Paragon_Truesight ( Replaces Darkvision `Passive` )
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

### RotER_Paragon_Divine_Awareness
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

### RotER_Paragon_Resilience ( Replaces Resilience `Passive` )
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

### RotER_Paragon_Magical_Weapons
```markdown
DisplayName :
> Magical Weapons

Description :
> As a Celestial Paragon, your weapons are infused with magical energy, inflicting magical damages.

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> RotER_Magical_Weapon;

Boost ( RotER_Magical_Weapon ) :
> WeaponIsMagical ( PropertyFlags )
```
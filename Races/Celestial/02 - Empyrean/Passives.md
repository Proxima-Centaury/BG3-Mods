# Empyrean Passives

### RotER_Empyrean_Base_Racial_Speed ( Replaces Base Racial Speed `Passive` )
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

### RotER_Empyrean_Truesight ( Replaces Darkvision `Passive` )
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

### RotER_Empyrean_Magical_Weapons
```markdown
DisplayName :
> Magical Weapons

Description :
> As a Titan, your weapons are infused with magical energy, inflicting magical damages.

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> RotER_Magical_Weapon;

Boost ( RotER_Magical_Weapon ) :
> WeaponIsMagical ( PropertyFlags )
```
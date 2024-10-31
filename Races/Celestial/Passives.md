# Celestial Passives

### RotER_Celestial_Base_Racial_Speed
```markdown
DisplayName :
> Base Racial Speed

Description :
> You can move [1] per turn.

DescriptionParams :
> Distance(9);

Icon :
> DEFAULT

Properties :
> Highlighted

Boosts :
> ActionResource(Movement, 9, 0);
```

### RotER_Celestial_Darkvision
```markdown
DisplayName :
> Darkvision

Description :
> You can see in the dark up to [1].

DescriptionParams :
> Distance(12);

Icon :
> DEFAULT

Properties :
> Highlighted

Boosts :
> DarkvisionRangeMin(12);
> ActiveCharacterLight(051648e6-f05a-e41f-e398-ffd5cd148989);
```

### RotER_Celestial_Resilience
```markdown
DisplayName :
> Resilience

Description :
> You are gifted with immunity against CHARMED, EXHAUSTED and FRIGHTENED statuses.

DescriptionTooltips :
<LSTag Type="Status" Tooltip="CHARMED">charmed</LSTag>
<LSTag Type="Status" Tooltip="EXHAUSTED">exhausted</LSTag>
<LSTag Type="Status" Tooltip="FRIGHTENED">frightened</LSTag>

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
```

### RotER_Celestial_Resistance
```markdown
DisplayName :
> Resistance

Description :
> You are resistant to radiant, bludgeoning, piercing and slashing damages coming from non-magical sources.

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> Resistance(Radiant, ResistantToNonMagical);
> Resistance(Bludgeoning, ResistantToNonMagical);
> Resistance(Piercing, ResistantToNonMagical);
> Resistance(Slashing, ResistantToNonMagical);
```

### RotER_Celestial_Spell_Shield
```markdown
DisplayName :
> Spell Shield

Description :
> You gain ADVANTAGE on Intelligence and Wisdom SAVINGTHROWS.

DescriptionTooltips :
<LSTag Tooltip="Advantage">Advantage</LSTag>
<LSTag Tooltip="SavingThrow">Saving Throws</LSTag>

Icon :
> CUSTOM

Properties :
> Highlighted

Boosts :
> Advantage(SavingThrow, Intelligence);
> Advantage(SavingThrow, Wisdom);
```
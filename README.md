# DnD-Swiss

It's a personal project that aims to help dnd players for roll their dices and track of their spell slots\spells.

## Planned Features in Order

It has to be Python project or atleast have Python part for Sysadmin reasons.

1. Users can Register and Login
    - User data have to be stored on db. (PostgreSQL is a good option)
        - Dice History (Maybe Redis)
        - Spell Slots and Spell History with spell details.
            - Spell Details: Range, Damage Type, Action Type, and Radius
        - Character Sheet (Later)
2. Users can Roll Dices
    - Users should be able to roll advantged/disadvantaged
    - Users should be able to use bonus modifiers. (Result of dice should be appear on screen)
    - Dice rolling animation is MUST have. (Can't stand ugly apps.)
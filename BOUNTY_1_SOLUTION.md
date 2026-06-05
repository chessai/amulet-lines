# Bounty 1 Solution

This is a solution to bounty 1 with two new additions to the deck: Colossal Skyturtle/Eternal Witness and Ghost Quarter.
It also requires you to have a single Forest in the deck when you cast Scapeshift, which I am not counting as an extra card.

### Starting Conditions

* Battlefield:

  * 1 Spelunking.
  * 0 Amulet of Vigor.
  * 5 lands:

    * 1 Simic Growth Chamber.
    * 1 Forest.
    * 3 Any land that is not Vestige or a Bounce.

* Hand:

  * Scapeshift.
* Graveyard:

  * Empty.
* Floating mana:

  * 1, after casting Scapeshift.
* Land drop available:

  * No.
* Other resources:

  * None.

### Line

1. Cast Scapeshift, sacrificing 1 Simic Growth Chamber and 4 untapped lands.
   **State:** 1 floating
2. Find 2x Vestige, Ghost Quarter, Simic Growth Chamber, TWest. Tap everything but Ghost Quarter, bounce TWest.
   **State:** 8 floating
3. Sacrifice Ghost Quarter on a Vestige, fetch Forest, tap Forest for mana.
   **State:** 9 floating
4. Transmute TWest for Pact, Pact for Analyst, cast and activate Analyst.
   **State:** 0 floating
5. Return original 4 untapped lands, 1 Vestige, 1 GQ, 1 SGC, 1 TWest, tap them for mana, bounce TWest.
   **State:** 10 floating
6. Transmute for Pact, Pact for Skyturtle/Eternal Witness, channel Skyturtle/play EWit targeting Shift, cast Shift.
   **State:** 0 floating
7. Fetch Woodland, 2x Bounce, Mirrorpool, Deeps on Vestige, Cave, Otawara, Boseiju, tap everything.
   **State:** 11 floating
8. Woodland copy Analyst, crack Woodland, return all lands from graveyard and tap them.
   **State:** 14 floating
9. Transmute TWest for ZOrb and loop.

### Result

Any infinite Analyst loop (infinite hasty creatures, infinite Boseiju + Otawara activations, etc.)

### Notes

The original formulation of the problem stipulated 4 Forests in the starting battlefield.
This is technically impossible with the provided decklist, which only has 3 Forests.
It is also not necessary to the line, as any untapped land will function just as well.
I thus tweaked the starting assumptions to reflect that.
It is not a substantive change, but if you did need to start with exactly 4 Forests, the decklist would need 5 Forests total for the line to work.

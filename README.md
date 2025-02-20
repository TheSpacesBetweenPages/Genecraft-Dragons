# Genecraft-Dragons
A basic character creator of sorts I've adapted from my cousins project assignment.
Quote from my Dwarf Fortress comment:

"""Reminds me of this monster character creation project my cousin made. You can add and "evolve" a dragons organs based on a list of traits linked to that main part; which would then correspond to three physical and mental stats, which depending on the trait selected has major or minor drawbacks to the other traits. You can compensate for this, but as a consequence it adds to gestation time, which can last potentially centuries. Hence its a self checking system of sorts.
I may plan to implement it in Dwarf Fortress, once I can get a working combat system in Godot.
 Spirit: Magic abilities, mainly used in the core. A dragons brain/essence and primary organ. As well as the mana reactor, for "breath attacks" possibly evolved to get the weight off more intensive casting with the core, to allow it to focus on thinking and processing.
Mind: Theoretically akin to memory and intuition? Though not necessarily social.
Spark
Physical traits are also locational, for some reason.
Body: General toughness, endurance, possibly disease immunity? I
Externals: More esoteric abilities tend to negatively effect this.
Internals: Including general senses like touch and smell, but also things like balance. I'd imagine its similar to kinetic/spacial sense, as well as the tracking skill if they have those traits."""
Example of a frequent menu:

Internals: 
[def view_stats(thing):
    array = thing.get_total_stats()
    print(" ╤⌬╧ ", array[0,0], "Body and", array[0,3], "Externals\n",
          "╤⌬╧ ", array[0,1], "Mind and", array[0,4], "Spark\n",
          "╤⌬╧ ", array[0,2], "Soul and", array[0,5], "Internals\n",
          "╤⌬╧ ", array[0,6], "Gene complexity")
]
"""

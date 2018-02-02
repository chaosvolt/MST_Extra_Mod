# MST_Extra_Mod

A mod for Cataclysm: Dark Days Ahead that requires More Survival Tools and Boatmod. Adds assorted additional content and changes that improve quality of life when playing innawoods, adding various interesting ideas variously thought up or suggested to me.

Recipe Additions/Overrides for Existing Items:
* Added the option of making waterskins using sealed stomachs. The idea is it isn't that complicated to add a strap to an already usable water container.
* Added overrides for some of the most basic leather and fur recipes, allowing the use of cured pelts/hides. The idea is that rawhide is still usable for some limited applications.
* Added both an override and an alternative recipe for boat oars, changing the material demand and making it non-reversible. The alternative version allows use of cordage instead of nails, and cutting instead of hammering.
* The `adhesive` crafting requirement has been overridden to allow pitch (see below) as an option. This does not yet make it an option for all recipes as not all have been converted to use the requirements system, but this should improve over time.

New Clothing:
* Pack baskets, allowing a basic storage item to be crafted without access to cloth or leather.
* Birchbark sheathes, something that might be useful for players innawoods, similar to how birchbark quivers are an option.

Medical/Chemistry Items:
* Willowbark tea. Way back when I PR'd willow bark and a recipe to make aspirin from them, I had the idea of using them directly as they've historically been used. My initial proposed implementation had some flaws in it, and at the time I simply axed it rather than trying to fix the idea. Being less efficient than processing into aspirin, yet still being useful when taken individually, this should fit the intended purpose.
* Tar oil, made from birchbark or pine boughs. Represents both birch and pine oil, which have antiseptic properties. Less effective than thyme oil or disinfectant for gameplay reasons, as I do not have any data on whether birch or pine oil are any less effective compared to other essential oils with antiseptic properties. Note that "oil" does not require the addition of cooking oil. I haven't been able to find whether thyme oil and mugwort oil is actually made in a realistic manner, but birch/pine oil don't involve cooking oil. :v
* Pitch, made by reducing tar oil to a more solid state. Usable as an adhesive for some recipes as stated above.

New Tools:
* A makeshift hoe with a stone blade. Recipe is comparable to that of the stone adze.

Vehicles and Parts:
* A makeshift sled with associated parts, that can be either assembled or constructed as a folding-vehicle item. The idea is one I had a long time ago, before I even released More Survival Tools. It was a bit of an annoyance to make and balance the parts, so I ended up scrapping it back in the day.
* The frame is notable mainly for being much less of a drain on rope than light wooden frames, which is by far the biggest problem with simply making a vanilla travois. The result is more fragile, however.
* The basket does not store as much as a wooden box, travois, etc. But it uses different resources, straw or birchbark primarily.
* Finally, the sled runners serve a niche that is effectively unique. It functions as a source of a stable single-tile wheelbase that does not require access to welding, and is also the only stable "wheel" to lack steering ability. To avoid illogical events like slapping foot pedals on a sled, its stats make it inadequate to accelerate a vehicle. Instead its primary purpose is for dragging a pulk or other storage vehicle.
* Log frames that can be made with fire, cutting, and an adze. Usable for outrigging, rafts, etc. The frame itself can float, rather than requiring separate boat boards.
* A log canoe that can be made from several logs, representing the dugout style. Made as a single item, the resulting vehicle can be packed up to carry if it you have the strength to.

Construction:
* Beehives. This was an idea that came up during the Utterly Mad succession game, and works in a somewhat hacky way. No use of the bees field for you, because holy crap bees are awful about homing in on players and never dissipating. Producing honeycombs still takes time and some established initial resources to begin with, but the result should be worth it.

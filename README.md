# MST_Extra_Mod

A mod for Cataclysm: Dark Days Ahead and Cataclysm: Bright Nights, the official followup to the now-obsolete More Survival Tools mod formerly present in the repo. Adds assorted additional content and changes that improve quality of life when playing innawoods, adding various interesting ideas variously thought up or suggested to me.

If you are using Dark Days Ahead, place the included MST_Extra folder in your data/mods folder. If you are using the Bright Nights fork, use the MST_Extra_BN folder instead. In either case it is recommended that, if updating the mod, to delete the older version of the folder rather than just dumping the new one onto the old one.

The following list of content is not only incomplete and unlikely to be out of date, it's also specifically only what MST Extra adds that was not originally present in More Survival Tools. All content that was part of the original MST at the time of its obsolescence is also now a part of this mod.

In addition, there may be differences in content between the DDA version and the BN version due to various QoL and performance tweaks made to BN, some of which negates the need for some changes that may be present in the DDA version.

Recipe Additions/Overrides for Existing Items:
* Added the option of making waterskins using sealed stomachs. The idea is it isn't that complicated to add a strap to an already usable water container.
* Added overrides for some of the most basic leather and fur recipes, allowing the use of cured pelts/hides. The idea is that rawhide is still usable for some limited applications (not present in BN, as it's now in the game's recipe directly).
* Added both an override and an alternative recipe for boat oars, changing the material demand and making it non-reversible. The alternative version allows use of cordage instead of nails, and cutting instead of hammering.
* The `adhesive` crafting requirement has been overridden to allow pitch (see below) as an option.
* The `cordage` and `cordage_short` crafting requirements have been overridden to allow leather cordage (see below) as options.
* The `fletching` crrafting requirement has been overriden to allow birchbark as an option.
* Added a recipe for carving a spile out of bone. Hand drill will still be required, and I might plan to add a flint drill in the future.
* Use of pitch in the waterproofing crafting requirement.
* A recipe for leaching saltpeter out of bird droppings (not present in BN, as animal waste has been dummied out).
* Overrides allowing bologna, dog food, and cat food to use meat scraps as an option.

Item Override
* Charcoal purifiers set as a subsititute tool for water purifiers, allowing their use in the clean water recipe that uses them.
* Hobo stoves have been reworked entirely. Instead of a basically useless tool, you instead deploy it as furniture, serving as a low-capacity fire container that protects the fire from wind and rain, making it useful outdoors.
* Petrified eyes, spiral stones, chunks of sulfur, golf balls, pool balls, baseballs, and magic 8-balls have all been edited to count as valid ammo for staff slings, while rubber slugs and limestone can be used in slingshots. The most rock-like are identical statwise to rocks, lighter objects tend to be less powerful and more fragile, sulfur can blind enemies if it hits the head, rubber slugs can stun like beanbag rounds, etc.
* In the DDA version, tarps have been correctly edited to have `SURFACE` quality.

New Clothing:
* Pack baskets, allowing a basic storage item to be crafted without access to cloth or leather.
* Birchbark sheathes, something that might be useful for players innawoods, similar to how birchbark quivers are an option.
* Birchbark canteens, sealed with pitch or similar materials.
* Leather and fur arm and leg wraps, as a supplement to other basic wrap recipes. As with the overrides, cured hides/pelts can be used as well.
* Basic blankets and sheets can be made into makeshift cloaks if you're desperate.
* Atlatl quivers, used in place of the older method of editing javelin bags, now that atlatl darts are a distinct item instead of atlatls using vanilla javelins.
* Makeshift gas hoods as a cruder option for envoirnmental protection, that can be worn over helmets.
* Side drums are a wearable instrument, percussion being notably absent among the vanilla musical intruments.

Medical/Chemistry Items:
* Willowbark tea. Way back when I PR'd willow bark and a recipe to make aspirin from them, I had the idea of using them directly as they've historically been used. My initial proposed implementation had some flaws in it, and at the time I simply axed it rather than trying to fix the idea. Being less efficient than processing into aspirin, yet still being useful when taken individually, this should fit the intended purpose.
* Tar oil, made from birchbark or pine boughs. Represents both birch and pine oil, which have antiseptic properties. Less effective than thyme oil or disinfectant for gameplay reasons, as I do not have any data on whether birch or pine oil are any less effective compared to other essential oils with antiseptic properties. Note that "oil" does not require the addition of cooking oil. I haven't been able to find whether thyme oil and mugwort oil is actually made in a realistic manner, but birch/pine oil don't involve cooking oil. :v
* Pitch, made by reducing tar oil to a more solid state. Usable as an adhesive for some recipes as stated above, and as ammo for makeshift repair kits (see below).
* Garlic oil, using the `WEAK_ANTIBIOTIC` use action. As with standard weak antibiotic, it's best used to to prevent a bite from turning infected if you lack any other antiseptic, but is better than nothing if you have a full-blown infection.
* Makeshift poultices, with two separate methods of crafting based on historical methods (crushed dry herbs, versus wet materials with absorbent binder). Main purpose is a way to make a healing item using some of the antibacterial items in the game that aren't otherwise usable for this, but it also has a secondary niche as a "can treat bleeding and bites, but not as well as a specialized item" function.
* Leather and fur can be tanned in small batches, taking a single piece of cured pelt/hide at a time to make leather/fur patches.

New Food Items:
* Ability to make basic roasted garlic and chili peppers, due to my experience finding these to be two of the most underused crops in the game.
* Garlic bread, for similar reasons as above.
* Posca, a historical mixed drink that provides an additional use for honey and basic wines.
* Jerked offal, adding a viable option to preserve organ meat for long-term use.
* Porridge that can be made from wheat or barley, as basically every other source of flour has a similiar basic alternative recipe.
* Pine bark can harvested from pine trees during spring, cooked as a simple source of calories, and made into flour.

New Tools/Related Items:
* A makeshift hoe with a stone blade. Recipe is comparable to that of the stone adze.
* Clay jars that can be used for some of the most basic canning recipes, in reference to the Appert process. A clay canning pot can also be made to facilitate this.
* Leather cordage can be made from leather, fur, or rawhide, as an alternative to woven cordage.
* Log buckets can be used as a crude, bulky, but servicable option for carrying a decent amount of liquid.
* Added clay alternatives to oil lamps and ember carriers.
* Added a clay oven that can be deployed to contain a fire, protecting it from wind and rain.
* A makeshift repair kit made from innawoods equivalents to the basic repair kit. Has the same qualities as the basic knife and adze used to make it, and uses pitch instead of duct tape when performing repairs.
* A stone-tipped hand drill, useful for drilling into wood and other soft uses for 1 drilling quality.
* Fire ploughs as an even cruder, less efficient, alternative to fire drills. In particular this doesn't require light to craft, removing a common catch-22 for players who find themselves needing light (and thus a fire) to make a firestarting tool.

Vehicles and Parts:
* A makeshift sled with associated parts, that can be either assembled or constructed as a folding-vehicle item. The idea is one I had a long time ago, before I even released More Survival Tools. It was a bit of an annoyance to make and balance the parts, so I ended up scrapping it back in the day.
* The frame is notable mainly for being much less of a drain on rope than light wooden frames, which is by far the biggest problem with simply making a vanilla travois. The result is more fragile, however.
* The basket does not store as much as a wooden box, travois, etc. But it uses different resources, straw or birchbark primarily.
* Finally, the sled runners serve a niche that is effectively unique. It functions as a source of a stable single-tile wheelbase that does not require access to welding, and is also the only stable "wheel" to lack steering ability. To avoid illogical events like slapping foot pedals on a sled, its stats make it inadequate to accelerate a vehicle. Instead its primary purpose is for dragging a pulk or other storage vehicle.
* Log frames that can be made with fire, cutting, and an adze. Usable for outrigging, rafts, etc. The frame itself can float, rather than requiring separate boat boards.
* A log canoe that can be made from several logs, representing the dugout style. Made as a single item, the resulting vehicle can be packed up to carry if it you have the strength to.

Construction:
* Beehives. This was an idea that came up during the Utterly Mad succession game, and works in a somewhat hacky way. No use of the bees field for you, because holy crap bees are awful about homing in on players and never dissipating. Producing honeycombs still takes time and some established initial resources to begin with, but the result should be worth it.
* An option to convert window frames into door frames, as that has been my number one most common cause of roof collapses that shouldn't be happening anyway.
* Constructable version of charcoal water purifiers.
* Leather version of door curtains.
* Makeshift stills, based off a technique looked up that uses sand or earth to insulate glass containers for distillation.
* Pulley lifters that can be constructed indoors, to provide a source of lifting quality for more advanced bases in isolated areas.
* Wooden windbreaks, simple barricades mainly to block wind for basic shelters.
* Version of the tarp lean-to using the leather tarp.

Other:
* Escaped livestock now start to filter into the standard forest monstertgroup as time goes on, remaining relatively rare but allowing the player some shot at finding livestock to tame.


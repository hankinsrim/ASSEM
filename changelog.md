# 0.1

## Fixes

- **Added** [XP32 Maximum Skeleton Special Extended](https://www.nexusmods.com/skyrimspecialedition/mods/1988) - XPMSE's inclusion resolves an overflow crash caused by including [Pandora
XPMSE Behavior Patch](https://www.nexusmods.com/skyrimspecialedition/mods/133232) without XPMSE.
- **Added** [Phantom Ammo Fix](https://github.com/hankinsrim/PhantomAmmoFix) - Fixes a vanilla (or vanilla + SKSE) bug where your quiver shows arrows you do not have.
- **Added** [Realistic Water Two](https://www.nexusmods.com/skyrimspecialedition/mods/2182) - Added to fix vanilla ponds magically flowing in one direction. Not the only solution to the
problem, but it was the best-looking solution to the problem.
- **Removed** Better Combat Escape, [SSE](https://www.nexusmods.com/skyrimspecialedition/mods/43936) & [NG](https://www.nexusmods.com/skyrimspecialedition/mods/72901) - They crashed on
cell changes during combat.
- **Removed** [Auto Input Switch](https://www.nexusmods.com/skyrimspecialedition/mods/54309) - Its hooks fail to install.

## Quality of Life

- **Added** [Weapon Stat Viewer](https://www.nexusmods.com/skyrimspecialedition/mods/124747) - Displays hidden weapon stats in the inventory.
- **Added** [Better Jumping SE](https://www.nexusmods.com/skyrimspecialedition/mods/18967) - Jump while sprinting.
- **Added** [Unread Books Glow Redone](https://www.nexusmods.com/skyrimspecialedition/mods/138451) - Spell, Skill, and Quest books glow lightly when unread.
- **Added** [moreHUD](https://www.nexusmods.com/skyrimspecialedition/mods/12688) - Shows what shrine blessings give, plus other additions.
- **Added** [Arrow Recovery Tweak](https://www.nexusmods.com/skyrimspecialedition/mods/104464) - Stops picking up arrows that were shot at you.
- **Replaced** [Trainwreck](https://www.nexusmods.com/skyrimspecialedition/mods/106440) with [Crash Logger](https://www.nexusmods.com/skyrimspecialedition/mods/59818) - It's more helpful,
and in the future this will let me try add-ons for Crash Logger that may help identify freezes.
- **Replaced** [SSE Display Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/34705) with 
[SSE Display Tweaks - Average FPS Option](https://www.nexusmods.com/skyrimspecialedition/mods/194831) - Adds an average FPS readout.
- **Configured** [SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/12604) - V/W column shown by default.
- **Configured** [Open Animation Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/92109) - Its in-game menu is off.

## Graphics

- **Added** [Faster HDT-SMP](https://www.nexusmods.com/skyrimspecialedition/mods/57339), [Vanilla Hair Remake SMP](https://www.nexusmods.com/skyrimspecialedition/mods/63979), and
[Weight adjustment](https://www.nexusmods.com/skyrimspecialedition/mods/161949) - Adds physics to vanilla hair.
- **Added** **VHR Two-Sided Lighting Fix** (Shipped in WJ file for now) - Fixes the inward-facing lighting on hair that looks off when used on a mostly vanilla graphics stack. I'm sure
it looks fine with a full CS/ENB setup.

## Balance

- **Added** [Sprint Jump Stamina](https://www.nexusmods.com/skyrimspecialedition/mods/197558) - Charges stamina for sprint-jumping, so sprinting and sprint-jumping are equal in total travel
time.

## Creation Club Content Removal

- **Removed** **Free CC** and **.1130 _ResourcePack fixes** - Fishing, Survival Mode, Rare Curios, Saints & Seducers and the Resource Pack. USSEP masters all five files, so they are
replaced with empty dummy plugins plus a cleanup plugin that handles what USSEP was left pointing at.
- **Added** **CC Dummy Masters** (Shipped in WJ file for now) - Five empty plugins so USSEP still finds its masters.
- **Added** **USSEP CC Cleanup** (Shipped in WJ file for now) - Disables the references USSEP leaves behind, rewrites its Survival Mode conditions as if Survival is off, and puts a couple of vanilla items back.
- **Added** [Configurable Main Menu](https://www.nexusmods.com/skyrimspecialedition/mods/196819) - Lets you choose which main menu options display.
- **Added** **Configurable System Menu** (Shipped in WJ file for now) - Lets you choose which system menu options display.
- **Replaced** [CritterSpawn Congestion Fix](https://www.nexusmods.com/skyrimspecialedition/mods/67276) with **CritterSpawn Congestion Fix - No CC** (Shipped in WJ file for now) - The
same minus one script.
- **Removed** [Fish Plaque Fixes and Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/93868) - Only needed for CC content.
- **Disabled** the CC Fishing Patch plugin from [Fully Harvest Hanging Carcasses](https://www.nexusmods.com/skyrimspecialedition/mods/86751) - Only needed for CC content.

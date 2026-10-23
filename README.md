# Sunset Shore

A simulated tropical beach that plays a full sunset or sunrise in real time, made as a party background.

Open `index.html` in Chrome, Edge or Firefox and press **F** for fullscreen. It runs offline; a working WebGL 2 graphics setup is needed.

- Sky colours come from a light-scattering model of the atmosphere; clouds drift and slowly change shape.
- Waves build, break with foam and spray, and run up a flat beach that stays glossy for a few seconds before drying.
- Palms, bushes, beach grass and lava rocks are lit by the same sun and sky, with distance haze.

## Settings

The menu is hidden in the coconuts of the tall palm (or press **M**):

- Sunset or sunrise, and where in the cycle to play from (±6 hours)
- Speed from real time up to 120×, and an optional loop
- Follow the local clock: sunrise at 06:00, sunset at 18:00 your time
- Clouds, surf, colour strength and detail level

Keys: **M** menu · **F** fullscreen · **Space** pause · **←/→** ±5 minutes

## Files

- `index.html`: the standalone page
- `sunset-shore.html`: the same page without the document wrapper, used for the hosted version

# Desk Otter look mechanics

Desk Otter keeps the lower torso, feet, tail base, and any desk surface stable. The gaze is led by the pupils and eyelids, followed by a small natural head turn or pitch and restrained upper-body follow-through. The round glasses remain rigidly attached to the face and preserve their size and shape; the eyes must stay inside the original apertures. Hair, blue shirt, brown fur, proportions, and friendly desk-worker expression remain unchanged.

Motion budget: every 22.5-degree step changes the eyes, eyelids, muzzle/nose direction, and head angle by a similar small amount. No adjacent step may jump in scale, baseline, face construction, glasses placement, tail position, or prop attachment.

- 000 up: face broadly frontal; pupils and muzzle aim clearly upward; chin lifts slightly without moving the feet.
- 090 screen-right: head and muzzle turn toward the viewer's right; right-facing facial plane becomes more visible; pupils sit right of head center.
- 180 down: face broadly frontal; pupils and muzzle aim clearly downward; eyelids and chin lower slightly.
- 270 screen-left: exact semantic opposite of 090; head and muzzle turn toward the viewer's left; pupils sit left of head center.

Diagonals interpolate smoothly between these cardinal pose families. The glasses follow the head as one rigid wearable object. Tail and desk props remain stable or lag subtly; they never flip sides or detach. Whole-sprite rotation, replacement eyes, floating effects, text, guides, and shadows are forbidden.

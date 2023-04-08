# libsm64-unity

Unity engine demo client of libsm64. This repo provides a Unity package which can be imported from the
package manager. For some example scenes on how to use it, or to just get started hacking around with
it directly, check out the [libsm64-unity-dev](https://github.com/libsm64/libsm64-unity-dev) repo.

This fork is supposed to add some features that are included in the latest version of libsm64 to hold people over until a more up to date version of the unity library is released. Added features include:
- Defines for more readable code
- Public read only variables: Health and State
- Functions: sm64_set_mario_action, sm64_set_mario_animation, sm64_set_mario_state, sm64_set_mario_position, sm64_set_mario_velocity, sm64_set_mario_health, sm64_mario_take_damage, sm64_mario_heal, sm64_mario_kill, sm64_mario_interact_cap

Keep in mind I know nothing about libraries or Unity plugins, so stuff might break and/or look bad. I also have not added non-mesh colliders support or sound support. I have no idea how to do either of those.

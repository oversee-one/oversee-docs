---
description: >-
  This section contains information about obtaining, changing, and using the
  variables of the cheat itself.
---

# Cheat Variables

### GetBool

Gets the value of a variable by name.\
Example:

```lua
local boolean = g_Cheat.GetBool("misc.auto_jump")
```

### GetInt

Gets the value of a variable by name.\
Example:

```lua
local integer = g_Cheat.GetInt("misc.fog.max_distance")
```

### GetFloat

Gets the value of a variable by name.\
Example:

```lua
local float = g_Cheat.GetFloat("misc.aspect_ratio")
```

### GetColor

Gets the value of a variable by name.\
Example:

```lua
local color = g_Cheat.GetColor("misc.something")
```



### SetBool

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.GetBool("misc.auto_jump", true)
```

### SetInt

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.GetInt("misc.fog.max_distance", 2500)
```

### SetFloat

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.SetFloat("misc.aspect_ratio", 1.77)
```

### SetColor

Sets the value of a variable by name.\
Example:

```lua
g_Cheat.SetColor("misc.something", Color.new(0.5, 0.2, 0.0))
```





{% hint style="info" %}
Then there is a very long list of available variables. The name of the variable corresponds to its action.
{% endhint %}

## Booleans

```
ragebot.enable
chams.enemy_visible.draw_chams
ragebot.forced_safety
ragebot.double_tap
ragebot.shotgun.auto_stop
ragebot.hide_shots
ragebot.multi_thread
antiaims.enable
antiaims.at_knife
antiaims.slow_walk
ragebot.rifle.multipoint_3
antiaims.jitter_sides
ragebot.shotgun.hit_box_1
antiaims.avoid_overlap
antiaims.jitter_move
antiaims.at_targets
ragebot.awp.hit_box_2
antiaims.invert_side
antiaims.anti_peek
misc.auto_jump
misc.auto_strafe
misc.fog.enable
ragebot.awp.double_tap_1
misc.fake_lag.enable
misc.ad_block
ragebot.pistol.multipoint_5
misc.unlock_inventory_access
misc.buybot.enable
misc.buybot.keep_awp
misc.buybot.molotov
misc.buybot.smokegrenade
misc.buybot.hegrenade
misc.buybot.taser
misc.buybot.heavyarmor
misc.buybot.vesthelm
misc.buybot.defuser
misc.team_ragdolls
misc.enemy_ragdolls
misc.local_ragdolls
misc.infinity_duck
chams.enemy_backtrack.mat_param_2
misc.edge_jump
misc.fake_duck
misc.quick_stop
misc.visual_interpolation
misc.change_fov_while_scoped
misc.hit_sound
misc.hidden_convars
misc.filter_console
misc.grenade_warning
misc.watermark
chams.enemy_backtrack.mat_param_4
ragebot.awp.safe_priority
misc.spectator_list
misc.shared_esp
misc.shared_chams
misc.hitmarker
chams.enemy_backtrack.mat_param_3
misc.auto_pick
misc.auto_pick_button
ragebot.scout.early_auto_stop
misc.auto_pick_on_shot
misc.out_of_view
chams.team_invisible.mat_param_1
misc.client_impacts
misc.third_person
misc.penetration_crosshire
misc.preserve_killfeed
ragebot.auto.multipoint_4
misc.server_impacts
world.show_world_grenades
ragebot.rifle.multipoint_4
ui.watermark
ragebot.rifle.auto_scope
ui.spectator_list
ui.keybindlist
ui.chat
ui.custom_hud
misc.hud.kill_list_colorize
misc.hud.clear_kill_feed_on_round
misc.hud.crosshire_dot
misc.radar.enable
misc.radar.item_1
misc.radar.item_2
misc.radar.item_3
misc.radar.item_4
misc.radar.item_5
misc.radar.item_6
misc.radar.item_7
misc.logs.item_1
misc.logs.item_2
misc.logs.item_3
misc.logs.item_4
misc.logs.item_5
misc.removals.item_1
misc.removals.item_2
misc.removals.item_3
misc.removals.item_4
misc.removals.item_5
misc.removals.item_6
misc.removals.item_7
misc.removals.item_8
misc.removals.item_9
misc.removals.item_10
misc.removals.item_11
ragebot.auto.auto_stop
ragebot.auto.auto_scope
ragebot.auto.early_auto_stop
ragebot.auto.safe_priority
ragebot.shotgun.safe_priority
ragebot.auto.dynamic_points
chams.on_shot.mat_param_5
ragebot.auto.double_tap_1
ragebot.auto.double_tap_2
ragebot.auto.hit_box_1
ragebot.deagle.multipoint_3
ragebot.auto.hit_box_2
esp.enemy.box.outline_inner
ragebot.deagle.multipoint_2
ragebot.auto.hit_box_3
ragebot.deagle.multipoint_5
ragebot.auto.hit_box_4
ragebot.deagle.multipoint_4
ragebot.auto.hit_box_5
ragebot.auto.hit_box_6
ragebot.auto.multipoint_1
ragebot.auto.multipoint_2
ragebot.auto.multipoint_3
ragebot.auto.multipoint_5
ragebot.auto.multipoint_6
ragebot.scout.auto_stop
ragebot.scout.auto_scope
chams.weapon_visible.mat_param_4
ragebot.scout.safe_priority
ragebot.awp.hit_box_3
ragebot.scout.dynamic_points
chams.weapon_invisible.mat_param_2
ragebot.scout.double_tap_1
chams.weapon_invisible.mat_param_1
ragebot.shotgun.early_auto_stop
ragebot.scout.double_tap_2
ragebot.revolver.auto_stop
ragebot.scout.hit_box_1
ragebot.scout.hit_box_2
ragebot.scout.hit_box_3
ragebot.deagle.auto_stop
ragebot.scout.hit_box_4
ragebot.scout.hit_box_5
ragebot.scout.hit_box_6
ragebot.scout.multipoint_1
ragebot.scout.multipoint_2
ragebot.scout.multipoint_3
chams.arms.draw_chams
ragebot.scout.multipoint_4
ragebot.scout.multipoint_5
ragebot.scout.multipoint_6
ragebot.awp.auto_stop
ragebot.awp.auto_scope
ragebot.awp.early_auto_stop
ragebot.awp.dynamic_points
ragebot.awp.double_tap_2
ragebot.awp.hit_box_1
ragebot.awp.hit_box_4
ragebot.awp.hit_box_5
ragebot.awp.hit_box_6
ragebot.awp.multipoint_1
ragebot.awp.multipoint_2
ragebot.awp.multipoint_3
ragebot.awp.multipoint_4
ragebot.awp.multipoint_5
ragebot.awp.multipoint_6
ragebot.deagle.auto_scope
ragebot.deagle.early_auto_stop
ragebot.deagle.safe_priority
ragebot.deagle.dynamic_points
ragebot.deagle.double_tap_1
ragebot.deagle.double_tap_2
ragebot.pistol.auto_stop
ragebot.deagle.hit_box_1
glow.weapon.enabled
ragebot.deagle.hit_box_2
ragebot.deagle.hit_box_3
ragebot.deagle.hit_box_4
ragebot.deagle.hit_box_5
ragebot.deagle.hit_box_6
ragebot.deagle.multipoint_1
ragebot.deagle.multipoint_6
chams.enemy_invisible.draw_chams
ragebot.revolver.auto_scope
chams.on_shot.mat_param_4
ragebot.revolver.early_auto_stop
ragebot.revolver.safe_priority
ragebot.revolver.dynamic_points
ragebot.revolver.double_tap_1
ragebot.revolver.double_tap_2
ragebot.revolver.hit_box_1
ragebot.revolver.hit_box_2
ragebot.revolver.hit_box_3
ragebot.revolver.hit_box_4
ragebot.revolver.hit_box_5
ragebot.revolver.hit_box_6
ragebot.revolver.multipoint_1
ragebot.revolver.multipoint_2
ragebot.revolver.multipoint_3
ragebot.revolver.multipoint_4
ragebot.revolver.multipoint_5
ragebot.revolver.multipoint_6
ragebot.pistol.auto_scope
ragebot.smg.multipoint_2
ragebot.rifle.multipoint_1
ragebot.pistol.early_auto_stop
ragebot.pistol.safe_priority
ragebot.pistol.dynamic_points
chams.enemy_invisible.mat_param_3
ragebot.pistol.double_tap_1
ragebot.pistol.double_tap_2
ragebot.pistol.hit_box_1
ragebot.pistol.hit_box_2
ragebot.pistol.hit_box_3
ragebot.pistol.hit_box_4
ragebot.pistol.hit_box_5
ragebot.pistol.hit_box_6
ragebot.pistol.multipoint_1
ragebot.pistol.multipoint_2
ragebot.pistol.multipoint_3
ragebot.pistol.multipoint_4
ragebot.pistol.multipoint_6
ragebot.rifle.auto_stop
ragebot.rifle.early_auto_stop
ragebot.rifle.safe_priority
ragebot.rifle.dynamic_points
ragebot.rifle.double_tap_1
ragebot.rifle.double_tap_2
ragebot.rifle.hit_box_1
ragebot.rifle.hit_box_2
ragebot.rifle.hit_box_3
ragebot.rifle.hit_box_4
ragebot.rifle.hit_box_5
ragebot.rifle.hit_box_6
ragebot.smg.multipoint_1
ragebot.rifle.multipoint_2
ragebot.smg.multipoint_6
ragebot.rifle.multipoint_5
ragebot.smg.multipoint_5
ragebot.rifle.multipoint_6
ragebot.shotgun.auto_scope
ragebot.shotgun.dynamic_points
ragebot.shotgun.double_tap_1
ragebot.shotgun.double_tap_2
ragebot.shotgun.hit_box_2
ragebot.shotgun.hit_box_3
ragebot.shotgun.hit_box_4
ragebot.shotgun.hit_box_5
ragebot.shotgun.hit_box_6
ragebot.shotgun.multipoint_1
ragebot.shotgun.multipoint_2
ragebot.shotgun.multipoint_3
ragebot.shotgun.multipoint_4
ragebot.shotgun.multipoint_5
ragebot.shotgun.multipoint_6
ragebot.smg.auto_stop
ragebot.smg.auto_scope
ragebot.smg.early_auto_stop
ragebot.smg.safe_priority
ragebot.smg.dynamic_points
ragebot.smg.double_tap_1
ragebot.smg.double_tap_2
ragebot.smg.hit_box_1
ragebot.smg.hit_box_2
ragebot.smg.hit_box_3
ragebot.smg.hit_box_4
ragebot.smg.hit_box_5
ragebot.smg.hit_box_6
ragebot.smg.multipoint_3
chams.weapon_invisible.draw_chams
ragebot.smg.multipoint_4
glow.local.enabled
glow.team.enabled
glow.enemy.enabled
chams.real.draw_chams
chams.real.mat_param_1
chams.real.mat_param_2
chams.real.mat_param_3
chams.real.mat_param_4
chams.real.mat_param_5
chams.desync.draw_chams
chams.desync.mat_param_1
chams.desync.mat_param_2
chams.desync.mat_param_3
chams.desync.mat_param_4
chams.desync.mat_param_5
chams.enemy_backtrack.mat_param_5
chams.arms.mat_param_1
chams.arms.mat_param_2
chams.arms.mat_param_3
chams.arms.mat_param_4
chams.enemy_backtrack.mat_param_1
chams.arms.mat_param_5
esp.enemy.enabled
chams.on_shot.mat_param_2
chams.local_weapon.draw_chams
chams.local_weapon.mat_param_1
chams.local_weapon.mat_param_2
chams.local_weapon.mat_param_3
chams.local_weapon.mat_param_4
chams.local_weapon.mat_param_5
chams.weapon_visible.draw_chams
chams.weapon_visible.mat_param_1
chams.weapon_visible.mat_param_2
chams.weapon_visible.mat_param_3
chams.weapon_visible.mat_param_5
chams.weapon_invisible.mat_param_3
chams.weapon_invisible.mat_param_4
chams.weapon_invisible.mat_param_5
chams.enemy_visible.mat_param_1
chams.enemy_visible.mat_param_2
chams.enemy_visible.mat_param_3
chams.enemy_visible.mat_param_4
chams.enemy_visible.mat_param_5
chams.enemy_invisible.mat_param_1
chams.enemy_invisible.mat_param_2
chams.enemy_invisible.mat_param_4
chams.enemy_invisible.mat_param_5
chams.enemy_backtrack.draw_chams
chams.on_shot.draw_chams
chams.on_shot.mat_param_1
chams.on_shot.mat_param_3
chams.team_visible.draw_chams
chams.team_visible.mat_param_1
chams.team_visible.mat_param_2
chams.team_visible.mat_param_3
chams.team_visible.mat_param_4
chams.team_visible.mat_param_5
esp.enemy.armor_bar_upper
chams.team_invisible.draw_chams
chams.team_invisible.mat_param_2
chams.team_invisible.mat_param_3
chams.team_invisible.mat_param_4
chams.team_invisible.mat_param_5
esp.enemy.only_visible
esp.enemy.box.outline_upper
esp.enemy.skeleton
esp.team.health_bar_upper
esp.enemy.money
esp.enemy.health_bar_upper
esp.enemy.health_bar_inner
esp.enemy.armor_bar_inner
esp.team.enabled
esp.team.only_visible
esp.team.box.outline_upper
esp.team.box.outline_inner
esp.team.skeleton
esp.team.money
esp.team.health_bar_inner
esp.team.armor_bar_upper
esp.team.armor_bar_inner
```

## Integers

```
ragebot.double_tap_option
antiaims.yaw_offset
antiaims.jitter_offset
antiaims.leg_mode
antiaims.roll_antiaim
antiaims.desync_on_shot
antiaims.left_limit
chams.enemy_backtrack.main_style
antiaims.right_limit
misc.transparent_in_tperson
antiaims.anti_peek_mode
misc.viewmodel.fov
misc.camerafov
misc.no_scope_mode
misc.fog.min_distance
misc.fog.max_distance
misc.fake_lag.amount
misc.fake_lag.randomize
misc.third_person_distance
misc.buybot.primary
misc.buybot.secondary
misc.visual_interpolation_amount
misc.hit_sound_volume
misc.skybox
misc.hud.crosshire_dot_size
misc.hud.crosshire_line_size
misc.hud.crosshire_gap_size
misc.hud.crosshire_width_size
misc.hud.kill_list_time
ragebot.scout.accuracy_boost
ragebot.auto.min_damage
ragebot.auto.hit_chance
ragebot.auto.accuracy_boost
ragebot.auto.head_scale
ragebot.auto.body_scale
ragebot.scout.min_damage
ragebot.scout.hit_chance
ragebot.scout.head_scale
ragebot.scout.body_scale
ragebot.awp.min_damage
ragebot.awp.hit_chance
ragebot.awp.accuracy_boost
ragebot.awp.head_scale
ragebot.awp.body_scale
ragebot.deagle.min_damage
ragebot.deagle.hit_chance
ragebot.deagle.accuracy_boost
ragebot.deagle.head_scale
ragebot.deagle.body_scale
ragebot.revolver.min_damage
ragebot.revolver.hit_chance
ragebot.revolver.accuracy_boost
ragebot.revolver.head_scale
ragebot.revolver.body_scale
ragebot.pistol.min_damage
ragebot.pistol.hit_chance
ragebot.pistol.accuracy_boost
ragebot.pistol.head_scale
ragebot.pistol.body_scale
ragebot.rifle.min_damage
ragebot.rifle.hit_chance
ragebot.rifle.accuracy_boost
ragebot.rifle.head_scale
ragebot.rifle.body_scale
ragebot.shotgun.min_damage
ragebot.shotgun.hit_chance
ragebot.shotgun.accuracy_boost
chams.on_shot.main_style
ragebot.shotgun.head_scale
ragebot.shotgun.body_scale
ragebot.smg.min_damage
ragebot.smg.hit_chance
ragebot.smg.accuracy_boost
ragebot.smg.head_scale
ragebot.smg.body_scale
glow.local.style
glow.team.style
glow.enemy.style
glow.weapon.style
chams.real.main_style
chams.desync.main_style
chams.arms.main_style
chams.local_weapon.main_style
chams.weapon_visible.main_style
chams.weapon_invisible.main_style
esp.enemy.box.bbox
chams.enemy_visible.main_style
chams.enemy_invisible.main_style
esp.team.box.bbox
chams.team_visible.main_style
chams.team_invisible.main_style
```

## Floats

```
misc.viewmodel.x
misc.viewmodel.y
misc.viewmodel.z
misc.aspect_ratio
misc.client_impacts_duration
misc.server_impacts_duration
```

## Colors

```
misc.fog.color
misc.client_impacts
misc.server_impacts
misc.world_modulation
misc.prop_modulation
chams.team_visible.color3
misc.sky_modulation
chams.real.color
chams.real.color1
chams.real.color2
chams.real.color3
chams.real.color4
chams.real.color5
chams.desync.color
chams.desync.color1
chams.desync.color2
chams.desync.color3
chams.desync.color4
chams.desync.color5
chams.arms.color
chams.arms.color1
chams.arms.color2
chams.arms.color3
chams.arms.color4
chams.arms.color5
chams.local_weapon.color
chams.local_weapon.color1
chams.local_weapon.color2
chams.local_weapon.color3
chams.local_weapon.color4
chams.local_weapon.color5
chams.weapon_visible.color
chams.weapon_visible.color1
chams.weapon_visible.color2
chams.weapon_visible.color3
chams.weapon_visible.color4
chams.weapon_visible.color5
chams.weapon_invisible.color
chams.weapon_invisible.color1
chams.weapon_invisible.color2
chams.weapon_invisible.color3
chams.weapon_invisible.color4
chams.weapon_invisible.color5
chams.enemy_visible.color
chams.enemy_visible.color1
chams.enemy_visible.color2
chams.enemy_visible.color3
chams.team_invisible.color
chams.enemy_visible.color4
chams.enemy_visible.color5
chams.enemy_invisible.color
chams.enemy_invisible.color1
chams.enemy_invisible.color2
chams.enemy_invisible.color3
chams.enemy_invisible.color4
chams.enemy_invisible.color5
chams.enemy_backtrack.color
chams.enemy_backtrack.color1
chams.enemy_backtrack.color2
chams.enemy_backtrack.color3
chams.enemy_backtrack.color4
chams.enemy_backtrack.color5
chams.on_shot.color
chams.on_shot.color1
chams.on_shot.color2
chams.on_shot.color3
chams.on_shot.color4
chams.on_shot.color5
chams.team_visible.color
chams.team_visible.color1
chams.team_visible.color2
chams.team_visible.color4
chams.team_visible.color5
chams.team_invisible.color1
chams.team_invisible.color2
chams.team_invisible.color3
chams.team_invisible.color4
chams.team_invisible.color5
```

# https://spartan.top

## advanced.yml Example
```
gravity-simulation:
  check_check_speed_simulation: true
  minimum_gravity_difference: 0.0
more-packets:
  check_positive_balance: true
  check_positive_net: true
  check_positive_latency: true
  check_negative: true
speed-simulation:
  check_check_speed_simulation: true
  minimum_speed_difference: 1.0E-10
exploits:
  check_ground_spoof: true
  check_movement_spoof: true
  check_baritone: true
hit-reach:
  check_hitbox_raytrace: true
  check_simple: true
  check_throughblocks: true
fast-clicks:
  check_cps: true
  check_floor_tempo: true
  check_deviation: true
  check_skewness: true
  check_kurtosis: true
  check_variance: true
  check_bow_force: true
  check_bow_shots: true
  clicks_per_second_limit: 15
  check_bow_force§a: false
velocity:
  check_vertical: true
  check_horizontal: true
kill-aura:
  check_irregular: true
  check_hit_time: true
  check_move_direction_1: true
  check_move_direction_2: true
  check_move_length: true
  check_back_track: true
  detection:
    players: true
    entities: true
irregular-movements:
  check_food_sprint: true
  check_head_position: true
  check_elytra: false
  check_vehicle: true
x-ray:
  check_normal: true
  check_nether: true
  check_the_end: true
  check_custom: true
impossible-actions:
  check_scaffold_direction: true
  check_scaffold_up: true
  check_scaffold_yaw: true
  check_actions: true
  check_breaking: true
  check_interact: true
  check_tower: true
  check_scaffold_analysis: true
  check_auto_respawn: true
fast-break:
  check_delay: true
  max_breaks_per_second: 40
  indirect_surroundings_per_second: 15
block-reach:
  check_breaking: true
  check_interact: true
  check_place: true
  check_raytrace: true
  overall_distance: 7.0
  check_raytrace§a: false
no-swing:
  check_breaking: true
  check_damage: true
inventory-clicks:
  check_shift: true
  check_slow: true
  check_medium: true
  check_fast: true
impossible-inventory:
  check_auto_totem: true
  check_closed_inventory: true
  check_portal_inventory: true
  check_cursor_usage: true
  check_sneaking: true
  check_sleeping: true
  check_dead: true
  check_sprint_jumping: true
  check_walk_jumping: true
  check_jumping: true
fast-eat:
  check_interact: true
  check_eat: true
```
(There may be more, less or different options, please be aware)

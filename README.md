# panorama_convar_change_list

### Manifests and ConVar Changes
 Update | depot 731 | depot 732 | Changes
 ------ | --- | --- | -------
#1 | 102570140068509816 | 5375719036071832502 | https://github.com/neko-pm/panorama_convar_change_list/commit/4a25aa41286f8efdb470e23f994706e44fcd2b0a
#2 | 2766135964578633460 | 1185379324627243626 | https://github.com/neko-pm/panorama_convar_change_list/commit/d4912dedc897ff3458222d49ad24f97a3129bf38
#3 | 9044312674806966351 | 3149010582865414809 | https://github.com/neko-pm/panorama_convar_change_list/commit/5a05d094797990088a51d2aa05aa44e72be90d5e

### Credits
Information dumped with a slightly modified version of https://github.com/saul/csgo-cvar-unhide

### New Commands and ConVars
Name | Type | Default Value | Flags | Description
---- | ---- | ------------- | ----- | -----------
@panoram_debug_dead_pad                   | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_2d_translate_no_comp_layer      | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_box_shadow_no_comp_layer        | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_cache_command_list_repaint_threshold | convar   | 0.25     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_cache_command_list_size_threshold | convar   | 2048     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_clamp_fractional_pixel_positions | convar   | 1        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_classes_force_invalidate        | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | Force style invalidation of the entire panel subtree when adding / removing classes.
@panorama_clear_frames_on_device_restore  | convar   | 2        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_daisy_wheel                     | convar   | ABXY     | "FCVAR_DEVELOPMENTONLY" | Daisy wheel input mode: RS &#124; ABXY
@panorama_debug_font_selection            | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_debug_movies                    | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_debug_overlay_opacity           | convar   | 0.8      | "FCVAR_ARCHIVE"  | 
@panorama_disable_blur                    | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_box_shadow              | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_descendant_filtering    | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | Disable descendant selector filtering
@panorama_disable_draw_fancy_quad         | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_draw_text               | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_draw_text_shadow        | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_layer_cache             | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_layer_clear             | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_outershadow_layer_cache | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_render_callbacks        | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_disable_render_target_cache     | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_dragscroll_affordance           | convar   | 20       | "FCVAR_DEVELOPMENTONLY" | Minimum mouse movement in pixels before a move is treated as a drag scroll
@panorama_dragscroll_affordance_vr        | convar   | 100      | "FCVAR_DEVELOPMENTONLY" | Minimum mouse movement in pixels before a move is treated as a drag scroll in VR
@panorama_dragscroll_maxflickvelocity     | convar   | 8000     | "FCVAR_DEVELOPMENTONLY" | Maximum velocity for a drag scroll flick
@panorama_dragscroll_maxflickvelocity_vr  | convar   | 8000     | "FCVAR_DEVELOPMENTONLY" | Maximum velocity for a drag scroll flick in VR
@panorama_dragscroll_minflickvelocity     | convar   | 60       | "FCVAR_DEVELOPMENTONLY" | Minimum velocity that the mouse must be moving as mouse up time to qualify as a drag scroll flick
@panorama_dragscroll_minflickvelocity_vr  | convar   | 240      | "FCVAR_DEVELOPMENTONLY" | Minimum velocity that the mouse must be moving as mouse up time to qualify as a drag scroll flick in VR
@panorama_dragscroll_mintime              | convar   | 0.02     | "FCVAR_DEVELOPMENTONLY" | Minimum time that the mouse button must be down before a move is treated as a drag scroll
@panorama_dragscroll_mintime_vr           | convar   | 0.1      | "FCVAR_DEVELOPMENTONLY" | Minimum time that the mouse button must be down before a move is treated as a drag scroll in VR
@panorama_dragscroll_velocitymultiplier   | convar   | 0.5      | "FCVAR_DEVELOPMENTONLY" | Multiplier for flick velocity off of actual measured velocity
@panorama_dragscroll_velocitymultiplier_vr | convar   | 0.5      | "FCVAR_DEVELOPMENTONLY" | Multiplier for flick velocity off of actual measured velocity
@panorama_enable_motion_blur              | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_experimental_overdraw_prevention | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_fbo_alloc_batch                 | convar   | 10       | "FCVAR_DEVELOPMENTONLY" | 
@panorama_flush_buffers                   | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_force_fast_text_shadow          | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_force_sort_child_ops            | convar   | 0        | "FCVAR_CHEAT"    | 
@panorama_highlight_composition_layers    | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_input_debug_info                | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_joystick_axis_repeat_curve_time | convar   | 1.0      | "FCVAR_DEVELOPMENTONLY" | 
@panorama_joystick_axis_repeat_interval_end | convar   | 0.05     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_joystick_axis_repeat_interval_start | convar   | 0.22     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_joystick_button_repeat_curve_time | convar   | 1.2      | "FCVAR_DEVELOPMENTONLY" | 
@panorama_joystick_button_repeat_interval_end | convar   | 0.10     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_joystick_button_repeat_interval_start | convar   | 0.48     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_keep_panel_in_layer_cache       | convar   | 1        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_keep_text_in_font_cache         | convar   | 1        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_large_dispatch_event_queue      | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_max_fps                         | convar   | 120.0f   | "FCVAR_DEVELOPMENTONLY" | 
@panorama_max_free_fbo                    | convar   | 1000     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_max_oof_overlay_up_fps          | convar   | 4.0f     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_max_overlay_fps                 | convar   | 60.0f    | "FCVAR_DEVELOPMENTONLY" | 
@panorama_might_scroll_no_comp_layer      | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_min_comp_layer_cache_cost       | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_motion_blur_velocity_scale      | convar   | 0.04     | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_reload_animations               | convar   | 1        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_render_stats                    | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_render_stats_posx               | convar   | 50       | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_render_stats_posy               | convar   | 500      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_render_target_cache_max_size    | convar   | 31457280 | "FCVAR_DEVELOPMENTONLY" | 
@panorama_repaint_watch_id                | convar   |          | "FCVAR_DEVELOPMENTONLY" | 
@panorama_show_fps                        | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_simple_borders_no_comp_layer    | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_sound_pos                       | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_sound_pos_dist                  | convar   | 2.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_sound_pos_show                  | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_spew_layout_invalidates         | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_steampad_button_repeat_curve_time | convar   | .5       | "FCVAR_DEVELOPMENTONLY" | 
@panorama_steampad_button_repeat_interval_end | convar   | 0.035    | "FCVAR_DEVELOPMENTONLY" | 
@panorama_steampad_button_repeat_interval_start | convar   | .7       | "FCVAR_DEVELOPMENTONLY" | 
@panorama_style_flag_force_invalidate     | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | Force style invalidation of the entire panel subtree when adding / removing style flags.
@panorama_suspend_paint                   | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_track_render_commands           | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | 
@panorama_transform_parents_no_layer_for_perspective | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_transforms_no_comp_layer        | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_transition_time_factor          | convar   | 1.0      | "FCVAR_DEVELOPMENTONLY" | A float representing a scale factor for transitions. 1.0 is normal, 2.0 would be twice as fast as normal, 0.5 half as fast
@panorama_use_backbuffer_directly         | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
@panorama_volume_ambient                  | convar   | 0.48f    | "FCVAR_DEVELOPMENTONLY" | 
@panorama_volume_effects                  | convar   | 1.0f     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_volume_master                   | convar   | 1.0f     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_volume_movies                   | convar   | 1.0f     | "FCVAR_DEVELOPMENTONLY" | 
@panorama_vsync                           | convar   | 1        | "FCVAR_DEVELOPMENTONLY" | 
cl_inventory_debug_tooltip                | convar   | 0        | "FCVAR_CLIENTDLL", "FCVAR_RELEASE" | 
cl_mouseenable_buttons                    | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
cl_use_entity_as_targetid                 | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
console_history_size                      | convar   | 1000     | "FCVAR_DEVELOPMENTONLY" | 
debug_drawbox                             | cmd      |  | "FCVAR_CHEAT"    | Create debug box
debug_drawdisp_boundbox                   | cmd      |  | "FCVAR_CHEAT"    | Create debug boxes for invalid displacements
dump_panorama_css_properties              | cmd      |  |                  | Prints out all valid panorama CSS properties and their documentation
dump_panorama_css_properties_memstats     | cmd      |  |                  | Prints out mem stats of all valid panorama CSS properties
dump_panorama_events                      | cmd      |  |                  | print panorama event types and their documentation
dump_panorama_js_scopes                   | cmd      |  |                  | print panorama js scopes, such as classes, and their associated methods. (wiki table format)
dump_panorama_render_command_stats        | cmd      |  |                  | 
forceactivecontrollertype                 | convar   | -1       | "FCVAR_DEVELOPMENTONLY" | 
http_cache_size                           | convar   | 150      | "FCVAR_DEVELOPMENTONLY" | 
hud_alt_ticks                             | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
hud_dump_altticks                         | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | List HUD elements and their alt_tick usage
ime_hkl_info                              | cmd      |  | "FCVAR_DONTRECORD" | Spew IME HKL info.
ime_info                                  | cmd      |  | "FCVAR_DONTRECORD" | Spew IME info.
ime_supported_info                        | cmd      |  | "FCVAR_DONTRECORD" | Spew IME Supported info.
launch_warmup_map                         | cmd      |  | "FCVAR_CLIENTDLL", "FCVAR_DONTRECORD", "FCVAR_CLIENTCMD_CAN_EXECUTE" | Launches warmup map
mat_draw_resolution                       | convar   | 0        | "FCVAR_CHEAT"    | 
mat_flashlight_shadow_decal_indirectcolour_amount | convar   | 0.1      | "FCVAR_DEVELOPMENTONLY", "FCVAR_MATERIAL_SYSTEM_THREAD" | 
mat_flashlight_shadow_decal_max_alpha     | convar   | 0.2      | "FCVAR_DEVELOPMENTONLY", "FCVAR_MATERIAL_SYSTEM_THREAD" | 
pan_asynctext                             | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
pan_disabletextshadowcache                | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
pan_dx                                    | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CHEAT" | 
panorama_3dpanel_anim_fadeinout_time_scale | convar   | 2.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | temp scale factor for animation fade in/out time
panorama_3dpanel_anims_bookend            | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | default true. If all anims designed to follow on from each other
panorama_3dpanel_camera_preset_blend_time | convar   | 1.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | time to blend between camera presets
panorama_3dpanel_fxaa                     | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 0-off, 1-always use fxaa (not just as a fallback if scratch rt not large enough for SSAA)
panorama_3dpanel_fxaa_edge_threshold_Q    | convar   | .35      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | The minimum amount of local contrast required to apply algorithm: (0.063 - overkill, slower), (0.125 - high quality), (0.166 - default), (0.250 - low quality), (0.333 - too little, faster)
panorama_3dpanel_fxaa_edge_threshold_min_Q | convar   | 0.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | Trims the algorithm from processing darks: (0.0312 - visible limit, slower), (0.0625 - high quality, faster), (0.0833 - upper limit, the start of visible unfiltered edges). Special note: when using FXAA_GREEN_AS_LUMA, likely want to set this to zero
panorama_3dpanel_fxaa_subpixel_Q          | convar   | 0.75     | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | Effects sub-pixel AA quality and inversely sharpness (only used on FXAA Quality): (0.0 - off), (1.0 - upper limit, softer), default = 0.75
panorama_3dpanel_guided_intro_delay       | convar   | 0.1      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | time to blend between camera presets
panorama_3dpanel_pedestalmodel            | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_3dpanel_shadowdepthbias          | convar   | 0.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | depthbias to use when rendering flashlight depth
panorama_3dpanel_shadowslopescaledepthbias | convar   | 5.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | slopescaledepthbias to use when rendering flashlight depth
panorama_3dpanel_ssaa                     | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 0-off, 1-use ssaa if possible, will add (or fallback to) fxaa if scratch rt not large enough for 1.25x supersmapling in both dimensions
panorama_camera_inout_scale               | convar   | 0.1      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_camera_inout_scale_kb            | convar   | 1        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_camera_lookat_scale              | convar   | 0.1      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_camera_rotate_altitude_scale     | convar   | 0.004    | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_camera_rotate_azimuth_scale      | convar   | 0.004    | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_camera_rotate_radius_scale       | convar   | 1.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_debugger_saved_height            | convar   | 720      | "FCVAR_ARCHIVE"  | 
panorama_debugger_saved_width             | convar   | 1280     | "FCVAR_ARCHIVE"  | 
panorama_debugger_saved_xpos              | convar   | 0        | "FCVAR_ARCHIVE"  | 
panorama_debugger_saved_ypos              | convar   | 0        | "FCVAR_ARCHIVE"  | 
panorama_dump_deny_input                  | cmd      |  | "FCVAR_DEVELOPMENTONLY" | Dumps panels currently denying all input to the game
panorama_light_inout_scale                | convar   | 0.5      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_light_move_scale                 | convar   | 0.1      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_light_rotate_altitude_scale      | convar   | 0.004    | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_light_rotate_azimuth_scale       | convar   | 0.004    | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_loadout_rotate_drag              | convar   | 0.19     | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_loadout_rotate_frametime_multiplier | convar   | 4.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_loadout_rotate_grab_scale        | convar   | 0.5      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_loadout_rotate_intro_scale       | convar   | 0.5      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_loadout_rotate_scale             | convar   | 2.0      | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | 
panorama_play_movie_ambient_sound         | convar   | 1        | "FCVAR_DEVELOPMENTONLY" | 
player_wargames_list2_7_0_604             | convar   | mg_skirmish_flyingscoutsman, mg_skirmish_armsrace, mg_skirmish_demolition | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE" | 
r_disable_static_prop_loading             | convar   | 0        | "FCVAR_CHEAT"    | If non-zero when a map loads, static props won't be loaded
scoreboard_use_sf                         | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | Use scaleform scoreboard
snd_mainmenu_music_break_time_max         | convar   | 0        | "FCVAR_CLIENTDLL", "FCVAR_CHEAT" | Minimum amount of time to pause between playing main menu music
snd_mainmenu_music_break_time_min         | convar   | 0        | "FCVAR_CLIENTDLL", "FCVAR_CHEAT" | Minimum amount of time to pause between playing main menu music
snd_mainmusic_hrtf                        | convar   | 0.0      | "FCVAR_DEVELOPMENTONLY" | Makes main menu music sound like a radio
snd_mainmusic_hrtf_transition_speed       | convar   | 0.03     | "FCVAR_DEVELOPMENTONLY" | Makes main menu music sound like a radio
snd_music_volume_onetime_reset_2          | convar   | 0        | "FCVAR_HIDDEN", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
snd_musicvolume_fixed                     | convar   | 0.3      | "FCVAR_DEVELOPMENTONLY", "FCVAR_HIDDEN" | Overall music volume
snd_mvp_volume                            | convar   | 0.0      | "FCVAR_ARCHIVE", "FCVAR_RELEASE" | Relative volume of the MVP music.
snd_show_events                           | convar   | 0        | "FCVAR_DEVELOPMENTONLY" | Logs all sound events that are emitted
steamcontroller_flow_interval             | convar   | 7000     | "FCVAR_DEVELOPMENTONLY" | 
steamcontroller_flow_sensitivity          | convar   | 0.75     | "FCVAR_DEVELOPMENTONLY" | 
steamcontroller_haptic_intensity          | convar   | 320      | "FCVAR_DEVELOPMENTONLY" | 
sticky_tooltips                           | convar   | 0        | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | Don't ever hide tooltips. Helpful when debugging complicated tooltip layouts.
test_convar                               | convar   | 0        | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_CLIENTCMD_CAN_EXECUTE" | Skips the prompt when saving a buy favorite in the buy menu
ui_inventorysettings_recently_acknowledged | convar   |          | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_listen_casual        | convar   | random_classic | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_listen_competitive   | convar   | random_classic | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_listen_deathmatch    | convar   | random_classic | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_listen_scrimcomp2v2  | convar   | mg_de_inferno | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_listen_skirmish      | convar   | mg_skirmish_flyingscoutsman | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_official_casual      | convar   | mg_casualsigma | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_official_deathmatch  | convar   | mg_casualsigma | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_maps_official_survival    | convar   | mg_xl_enclave | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_mode_listen               | convar   | casual   | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_mode_official             | convar   | casual   | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_playsettings_warmup_map_name           | convar   | de_mirage | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_vanitysetting_itemid                   | convar   |          | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_vanitysetting_loadoutslot              | convar   |          | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_vanitysetting_model                    | convar   |          | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
ui_vanitysetting_team                     | convar   |          | "FCVAR_CLIENTDLL", "FCVAR_ARCHIVE", "FCVAR_RELEASE" | 
voice_status_test_toggle                  | cmd      |  | "FCVAR_DEVELOPMENTONLY", "FCVAR_CLIENTDLL" | Test voice and status notices

---
title: "Profiles (Settings)"
intro: "Each profile is available for full customization. In fact, each profile can become a separate application for the needs of the user."
versions: '*'
---
{% data reusables.general.article-not-complete %}


To start setting up an application profile:

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile)

![Profiles Settings Android](/assets/images/personal/profiles/profile_settings_android.png)

{% endandroid %}


{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %}

![Profiles Settings iOS](/assets/images/personal/profiles/profile_settings_ios.png)

{% endios %}



## Profile configuration

This section contains all the settings related to the appearance, navigation settings, map rendering, configure menu, and screen of a profile.

{% note %}
All settings affect the selected application profile only.
{% endnote %}


{% data reusables.general.android-ios-switcher %}

{% android %}

![Profiles Settings Android](/assets/images/personal/profiles/profile_settings_menu_android.png)

{% endandroid %}

{% ios %}

![Profiles Settings iOS](/assets/images/personal/profiles/profile_settings_menu_ios.png)

{% endios %}


### General settings

This section of settings contains settings of the cursor on the map and map view, settings of units & formats of map and profile data, settings of external input devices, and other sensors.


{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.general_settings_2 %}

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.general_settings_2 %}

{% endios %}

#### **Appearance**

In this section of the General settings menu, you can set parameters for the cursor on the map and map view for the chosen profile.

{% data reusables.general.android-ios-switcher %}

{% android %}

![Profiles General Settings Appearance Android](/assets/images/personal/profiles/profile_gs_appearance_android.png)

- {% data variables.android-values.choose_osmand_theme %} - sets a day or night theme for the application. This setting doesn't change ["Map mode"](/osmand/map/vector-maps#map-mode) parameter.
- {% data variables.android-values.rotate_map_to_bearing %} - allows [to set orientation the map view](/osmand/map/interact-with-map#map-orientation-modes).
- {% data variables.android-values.always_center_position_on_map %} - allows to use center or bottom screen position for the cursor (["My location"](/osmand/map/interact-with-map#my-location--zoom)). In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in the navigation mode.
- {% data variables.android-values.map_screen_orientation %} - sets the screen position for the OsmAnd application: {% data variables.android-values.map_orientation_portrait %}, {% data variables.android-values.map_orientation_landscape %}, {% data variables.android-values.map_screen_orientation %}.
- {% data variables.android-values.screen_control %} - opens [the screen control menu](/osmand/navigation/route-navigation#turn-on-screen), where you can select parameters for your device screen during navigation for keeping device battery consumption.

{% endandroid %}

{% ios %}

![Profiles General Settings Apperance iOS](/assets/images/personal/profiles/profile_gs_appearance_ios.png)

- {% data variables.ios-values.rotate_map_to_bearing %} - allows [to set orientation the map view](/osmand/map/interact-with-map#map-orientation-modes).
- {% data variables.ios-values.allow_3D_view%} - enables/disables 2.5D view of the map view. Use ["Gesture"](/osmand/map/interact-with-map#gestures) or ["My Location button"](/osmand/map/interact-with-map#my-location--zoom) for 3D view
- {% data variables.ios-values.always_center_position_on_map %} - allows to use center or bottom screen position for the cursor (["My location"](/osmand/map/interact-with-map#my-location--zoom)). In this mode the center of the map will be located slightly below the center of the device. It allows seeing more map information ahead of your movement which is usable in the navigation mode.

{% endios %}


#### **Units & formats**


In this section you can set parameters of units & formats for chosen application profile.

{% data reusables.general.android-ios-switcher %}

{% android %}


![Profiles General Settings Units & formats Android](/assets/images/personal/profiles/profile_gs_unitsformats_android.png)

| Parameter | Format | Note   |
|:------------|:---------------|:---------------|
|**{% data variables.android-values.driving_region %}**| {% data variables.android-values.driving_region_automatic %} | According to the device location |
|            | {% data variables.android-values.driving_region_europe_asia %}   | {% data variables.android-values.right_side_navigation %}, {% data variables.android-values.si_km_m %}  |
|            | {% data variables.android-values.driving_region_us %}   |  {% data variables.android-values.right_side_navigation %}, {% data variables.android-values.si_mi_feet %}  |
|            | {% data variables.android-values.driving_region_canada %}   | {% data variables.android-values.right_side_navigation %}, {% data variables.android-values.si_km_m %}   |
|            | {% data variables.android-values.driving_region_uk %}   |  {% data variables.android-values.left_side_navigation %}, {% data variables.android-values.si_mi_feet %}   |
|            | {% data variables.android-values.driving_region_japan %}   | {% data variables.android-values.left_side_navigation %}, {% data variables.android-values.si_km_m %}   |
|            | {% data variables.android-values.driving_region_australia %}   |  {% data variables.android-values.left_side_navigation %}, {% data variables.android-values.si_km_m %}  |
|**{% data variables.android-values.unit_of_length %}**| {% data variables.android-values.si_km_m %} | 1 km / 1000 m |
|          | {% data variables.android-values.si_mi_feet %} | 0.62 ml / 3281 f |
|          | {% data variables.android-values.si_mi_meters %} | 0.62 ml / 1000 m  |
|          | {% data variables.android-values.si_mi_yard %} |  0.62 ml / 1094 ya |
|          | {% data variables.android-values.si_nm %} | 0.54 nml |
|**{% data variables.android-values.coordinates_format %}**| {% data variables.android-values.dd_mm_mmmm_format %} | Example: 50.12333° 19.93233° (Lat Long) |
|          | {% data variables.android-values.dd_mm_mmm_format %} | Example: 50°7.393′ 19°55.941′ (Lat Long)  |
|          | {% data variables.android-values.dd_mm_ss_format %} | Example: 50°7′23.6″ 19°55′56.4″ (Lat Long) 23°27′30″ |
|          | {% data variables.android-values.navigate_point_format_utm %} | 34N 5552876 423678 (Zone Northing Easting) . [{% data variables.android-values.utm_format_descr %}](https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system) |
|          | {% data variables.android-values.navigate_point_format_mgrs %} | Example: 34U DA 23678 52873 . [{% data variables.android-values.mgrs_format_descr %}](https://en.wikipedia.org/wiki/Military_Grid_Reference_System)  |
|          | {% data variables.android-values.navigate_point_format_olc %} | Example:  9F2X4WFJ+7W ([Open Location Code](https://en.wikipedia.org/wiki/Open_Location_Code) represents area 9m x 14m)  |
|**{% data variables.android-values.coordinates_format %}**| Degrees 180° | All angular values have readings from 0° to 180° and from 0° to -180°.  |
|          | Degrees 360° | All angular values have readings from 0° to 360°.  |
|          | {% data variables.android-values.shared_string_milliradians %} | All angular values have [milliradian value](https://en.wikipedia.org/wiki/Milliradian).  |
|**{% data variables.android-values.default_speed_system %}**| {% data variables.android-values.si_kmh %} | 90 km/h  |
|          | {% data variables.android-values.si_mph %} | 55.92 mph  |
|          | {% data variables.android-values.si_m_s %} | 30 m/s |
|          | {% data variables.android-values.si_min_m %} | 1.073 min/m |
|          | {% data variables.android-values.si_min_km %} | 0.667 min/km |
|          | {% data variables.android-values.si_nm_h %} | 48.59 kn |

{% endandroid %}

{% ios %}

![Profiles General Settings Units & formats iOS](/assets/images/personal/profiles/profile_gs_unitsformats_ios.png)

| Parameter | Format | Note |
|:------------|:---------------|:---------------|
|**{% data variables.ios-values.driving_region %}**| {% data variables.ios-values.driving_region_automatic %} | According to the device location |
|            | {% data variables.ios-values.driving_region_europe_asia %}   | {% data variables.ios-values.right_side_navigation %}, {% data variables.ios-values.si_km_m %}  |
|            | {% data variables.ios-values.driving_region_us %}   |  {% data variables.ios-values.right_side_navigation %}, {% data variables.ios-values.si_mi_feet %}  |
|            | {% data variables.ios-values.driving_region_canada %}   | {% data variables.ios-values.right_side_navigation %}, {% data variables.ios-values.si_km_m %}   |
|            | {% data variables.ios-values.driving_region_uk %}   |  {% data variables.ios-values.left_side_navigation %}, {% data variables.ios-values.si_mi_feet %}   |
|            | {% data variables.ios-values.driving_region_japan %}   | {% data variables.ios-values.left_side_navigation %}, {% data variables.ios-values.si_km_m %}   |
|            | {% data variables.ios-values.driving_region_australia %}   |  {% data variables.ios-values.left_side_navigation %}, {% data variables.ios-values.si_km_m %}  |
|**{% data variables.ios-values.unit_of_length %}**| {% data variables.ios-values.si_km_m %} | 1 km / 1000 m |
|          | {% data variables.ios-values.si_mi_feet %} | 0.62 ml / 3281 f |
|          | {% data variables.ios-values.si_mi_meters %} | 0.62 ml / 1000 m |
|          | {% data variables.ios-values.si_mi_yard %} | 0.62 ml / 1094 ya |
|          | {% data variables.ios-values.si_nm %} | 0.54 nml |
|**{% data variables.ios-values.coords_format %}**| {% data variables.ios-values.navigate_point_format_D %} | Example: 50.12333° 19.93233° (Lat Long) |
|          | {% data variables.ios-values.navigate_point_format_DM %} | Example: 50°7.393′ 19°55.941′ (Lat Long)  |
|          | {% data variables.ios-values.navigate_point_format_DMS %} | Example: 50°7′23.6″ 19°55′56.4″ (Lat Long) 23°27′30″ |
|          | {% data variables.ios-values.navigate_point_format_UTM %} | 34N 5552876 423678 (Zone Northing Easting) . [{% data variables.ios-values.utm_format_descr %}](https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system) |
|          | {% data variables.ios-values.navigate_point_format_OLC %} | Example:  9F2X4WFJ+7W ([Open Location Code](https://en.wikipedia.org/wiki/Open_Location_Code) represents area 9m x 14m)  |
|**{% data variables.ios-values.angular_units %}**| Degrees 180° | All angular values have readings from 0° to 180° and from 0° to -180°.  |
|          | Degrees 360° | All angular values have readings from 0° to 360°.  |
|          | {% data variables.ios-values.shared_string_milliradians %} | All angular values have [milliradian value](https://en.wikipedia.org/wiki/Milliradian).  |
|**{% data variables.ios-values.default_speed_system %}**| {% data variables.ios-values.si_kmh %} | 90 km/h  |
|          | {% data variables.ios-values.si_mph %} | 55.92 mph  |
|          | {% data variables.ios-values.si_m_s %} | 30 m/s |
|          | {% data variables.ios-values.si_min_m %} | 1.073 min/m |
|          | {% data variables.ios-values.si_min_km %} | 0.667 min/km |
|          | {% data variables.ios-values.si_nm_h %} | 48.59 kn |

{% endios %}


#### **Other**

Additional settings for profile (like external devices and etc.)

{% data reusables.general.android-ios-switcher %}

{% android %}

You can enable/disable buttons and input devices for OsmAnd, on or off animations for navigation mode, use or not fullscreen mode, magnetic sensor, Kalman filter.

![Profiles General Settings Other Android](/assets/images/personal/profiles/profile_gs_other_android.png)

- {% data variables.android-values.use_volume_buttons_as_zoom %} - allows to use or not volume buttons of a device as [zoom](/osmand/map/interact-with-map#my-location--zoom).
- [{% data variables.android-values.use_kalman_filter_compass %}](/osmand/map/interact-with-map#extra-compass-settings) - allows to use or not [Kalman filter](https://en.wikipedia.org/wiki/Kalman_filter) for smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till.
- [{% data variables.android-values.use_magnetic_sensor %}](/osmand/map/interact-with-map#extra-compass-settings) - allows to use or not [Magnetic sensor](https://en.wikipedia.org/wiki/Kalman_filter) for smoothen rotation of the map with a slower rotation animation though it introduces a small delay (< 1 second) till.
- {% data variables.android-values.tap_on_map_to_hide_interface %} - use or not fullscreen mode of OsmAnd app on the device.
- [{% data variables.android-values.do_not_use_animations %}](/osmand/map/interact-with-map#disable-all-animations) - allows to switch on/off animation for navigation mode. 
- [{% data variables.android-values.external_input_device %}](/osmand/map/interact-with-map#external-input-device-buttons) - allows adding external input devices for control OsmAnd app by buttons of these devices. External input devices: {% data variables.android-values.sett_wunderlinq_ext_input %}, {% data variables.android-values.sett_generic_ext_input %}, {% data variables.android-values.sett_parrot_ext_input %}.

{% endandroid %}

{% ios %}

You can enable/disable buttons and input devices for OsmAnd.

- [{% data variables.ios-values.sett_ext_input %}](/osmand/map/interact-with-map#external-input-device-buttons) - allows adding external input devices for control OsmAnd app by buttons of these devices. External input devices: {% data variables.ios-values.sett_wunderlinq_ext_input %}, {% data variables.ios-values.sett_generic_ext_input %}.

{% endios %}

### Navigation settings

In this part, there are all settings for navigation mode of a profile.

{% note %}
This part of settings doesn't exist for "Browse map" profile.
{% endnote %}

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.routing_settings_2 %}

![Profiles Navigation Settings Android](/assets/images/personal/profiles/profile_navigation_settings_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.routing_settings_2 %}

![Profiles Navigation Settings iOS](/assets/images/personal/profiles/profile_navigation_settings_ios.png)

{% endios %}

#### **Navigation**

In this section you can set [routing and navigation parameters of your profile, map during navigation and vehicle parameters](/osmand/navigation).

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.android-values.nav_type_hint %} - governs how routes are calculated. These are rules for routing your profile. It means that your bicycle profile has Cycling navigation type for example. You can import the routing file from any cloud storage app by opening it in OsmAnd. More about [Routing.xml on our Github page](https://github.com/osmandapp/OsmAnd-resources/blob/master/routing/routing.xml).

{% data variables.android-values.route_parameters %} - controls which parameters will be used during routing and which parameters will be showed on the device screen. During navigation you can change some of these parameters in ["Navigation Options"](/osmand/navigation/route-navigation#navigation-options). Below list of parameters:

| Parameter | Description | Note |
|:------------|:---------------|:---------------|
|**{% data variables.android-values.nav_type_hint %}:**| {% data variables.android-values.select_nav_profile_dialog_message %} |     |
| {% data variables.android-values.shared_string_offline %} |  Offline routing uses sources of the device and calculation the route by using data of OsmAnd offline maps.  |  Navigation types ([OsmAnd routing](https://github.com/osmandapp/OsmAnd-resources/blob/master/routing/routing.xml)) by default: [{% data variables.android-values.app_mode_boat %}](/osmand/navigation/boat-navigation#boat), [{% data variables.android-values.rendering_value_bicycle_name %}](/osmand/navigation/route-navigation), [{% data variables.android-values.routing_profile_direct_to %}](/osmand/navigation/boat-navigation#direct-to-point), [{% data variables.android-values.rendering_value_car_name %}](/osmand/navigation/route-navigation), [{% data variables.android-valuess.rendering_value_pedestrian_name %}](/osmand/navigation/route-navigation), [{% data variables.android-values.app_mode_public_transport %}](/osmand/map/public-transport), [{% data variables.android-values.routing_profile_ski %}](/osmand/plugins/ski-maps), [{% data variables.android-values.routing_profile_straightline %}](/osmand/navigation/boat-navigation#straight-line), [{% data variables.android-values.horseback_riding %}](/osmand/navigation/route-navigation).            |
| {% data variables.android-values.shared_string_online %} |  Online routing builds the route servers' resources online by the Internet connection. |   List of online routing providers. Here you can add an online routing engine: ([Graphhopper](https://graphhopper.com/), [OSRM](http://project-osrm.org/), [Openrouteservice](https://openrouteservice.org/), GPX.   |
| **{% data variables.android-values.route_parameters %}:** |  allows setting routing for any cases and showing additional info about roads.   |              |
| "{% data variables.android-values.fast_route_mode %}" |  {% data variables.android-values.fast_route_mode_descr %}    |              |
| "{% data variables.android-values.routing_attr_driving_style_name %}"   |  select driving puprose to get shorter, faster, safer or unpaved route. | "{% data variables.android-values.routing_attr_driving_style_prefer_unpaved_name %}": prefer unpaved over paved roads for routing.<br>  "{% data variables.android-values.routing_attr_driving_style_safety_name %}": prefer safer roads for routing.<br> "{% data variables.android-values.routing_attr_driving_style_balance_name %}": prefer faster way for routing.<br>  "{% data variables.android-values.routing_attr_driving_style_speed_name %}": prefer shorter way for routing.<br>     |
| "{% data variables.android-values.impassable_road %}" |  avoid certain routes and road types for routing:    |  Each navigation type has its own set of avoiding.  |
|                 |  "{% data variables.android-values.routing_attr_avoid_unpaved_name %}"    |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_stairs_name %}"    |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_borders_name %}"    |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_footways_name %}"     |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_tunnels_name %}"    |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_sett_name %}"|              |
|                 |  "{% data variables.android-values.routing_attr_avoid_toll_name %}"|              |
|                 |   "{% data variables.android-values.routing_attr_avoid_low_emission_zone_name %}"|               |
|                 |  "{% data variables.android-values.routing_attr_avoid_shuttle_train_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_motorway_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_ice_roads_fords_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_train_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_subway_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_ferries_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_tram_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_bus_name %}" |              |
|                 |  "{% data variables.android-values.routing_attr_avoid_share_taxi_name %}" |              |
| "{% data variables.android-values.prefer_in_routing_title %}" |  {% data variables.android-values.routing_attr_driving_style_prefer_unpaved_description %}  |    |
| "{% data variables.android-values.routing_attr_short_way_name %}" |  {% data variables.android-values.routing_attr_short_way_description %}  |    |
| "{% data variables.android-values.routing_attr_allow_streams_name %}" |  allows streams and drains for boat navigation type.  | Boat navigation type |
| "{% data variables.android-values.routing_attr_allow_intermittent_name %}" |  allows intermittent water ways for boat navigation type.  | Boat navigation type    |
| "{% data variables.android-values.routing_attr_max_num_changes_name %}" |  specify upper limit of changes of for public transport.  | Public transport navigation type    |
| "{% data variables.android-values.routing_attr_allow_motorway_name %}" |  {% data variables.android-values.routing_attr_allow_motorway_description %}  | Cycling |
| "{% data variables.android-values.routing_attr_allow_private_name %}" |  {% data variables.android-values.routing_attr_allow_private_description %}  |    |
| "{% data variables.android-values.routing_attr_height_obstacles_name %}" |  allows choosing relief parameters for the routing. The routing could avoid strong uphills:   |   Cycling routing |
|   | "{% data variables.android-values.routing_attr_relief_smoothness_factor_more_plains_name %}"  | Routing could avoid strong uphills.    | 
|   | "{% data variables.android-values.routing_attr_relief_smoothness_factor_plains_name %}"  | Routing could avoid strong uphills.    | 
|   | "{% data variables.android-values.routing_attr_relief_smoothness_factor_hills_name %}"  | Routing could avoid strong uphills.    |  
| "{% data variables.android-values.temporary_conditional_routing %}" |  {% data variables.android-values.temporary_conditional_routing_descr %}. Data from OpenStreetMap. |    |
| "{% data variables.android-values.recalculate_route %}" | allows to recalculate the route by the next cases:    |    |
|   | "{% data variables.android-values.route_recalculation_dist_title %}"    |  {% data variables.android-values.recalculate_route_in_deviation %}. {% data variables.android-values.select_distance_route_will_recalc %}  |
|   | "{% data variables.android-values.in_case_of_reverse_direction %}"   |  The route will be recalculated if the direction is changed to reverse. |
| "{% data variables.android-values.development %}" | using live updates and the initial part for calculation the route    |    |
|   | "{% data variables.android-values.use_live_routing %}"    |  Enable navigation for [OsmAnd Live changes](/osmand/personal/maps#osmand-live).  |
|   | "{% data variables.android-values.use_fast_recalculation %}"   |  {% data variables.android-values.use_fast_recalculation_desc %} |
|   | "{% data variables.android-values.use_two_phase_routing %}"   |  {% data variables.android-values.complex_routing_descr %} |
| **{% data variables.android-values.screen_alerts %}** | showing or not alerts on the screen like a widget. Alerts shown bottom left during navigation. | [Types of alert widgets](/osmand/widgets/nav-widgets#alert-widget)   |
| **{% data variables.android-values.voice_announcements %}** | on/off and settings of [voice guidance](/osmand/navigation/voice-navigation) during navigation.    |  Configure to announce street names, traffic warnings (forced stops, speed bumps), speed camera warnings, speed limits.  |
| **{% data variables.android-values.vehicle_parameters %}** | specified vehicle parameters may affect routing:   |   |
|     | {% data variables.android-values.default_speed_setting_title %}  | {% data variables.android-values.default_speed_setting_descr %}.  |
|     | {% data variables.android-values.routing_attr_weight_name %}   | {% data variables.android-values.weight_limit_description %}   |
|     | {% data variables.android-values.routing_attr_height_name %}  | {% data variables.android-values.height_limit_description %}   |
|     | {% data variables.android-values.routing_attr_length_name %}  | {% data variables.android-values.lenght_limit_description %}   |
|     | {% data variables.android-values.routing_attr_width_name %} | {% data variables.android-values.width_limit_description %}   |
| **{% data variables.android-values.customize_route_line %}** | Change color and width for the route line during [navigation](/osmand/navigation).   | [Pro feature](/osmand/purchases/android#free-and-paid-features)  |
|     | {% data variables.android-values.shared_string_color %} | Using color by: Map style, Custom, Altitude, Slope, Road type, Surface, Smoothness, Winter and ice roads,Surface firmness.  |
|     | {% data variables.android-values.shared_string_width %} | Using width by: Map style, Thin, Medium, Bold, Custom.  |

{% endandroid %}


{% ios %}

{% data variables.ios-values.nav_type_title %} - governs how routes are calculated. These are rules for routing your profile. It means that your bicycle profile has Cycling navigation type for example. You can import the routing file from any cloud storage app by opening it in OsmAnd. More about [Routing.xml on our Github page](https://github.com/osmandapp/OsmAnd-resources/blob/master/routing/routing.xml).

{% data variables.ios-values.route_parameters %} - controls which parameters will be used during routing and which parameters will be showed on the device screen. During navigation you can change some of these parameters in ["Navigation Options"](/osmand/navigation/route-navigation#navigation-options). Below list of parameters:

| Parameter | Description | Note |
|:------------|:---------------|:---------------|
|**{% data variables.ios-values.nav_type_title %}**| choose your Navigation type which controls how routes are calcualted.  | Navigation types ([OsmAnd routing](https://github.com/osmandapp/OsmAnd-resources/blob/master/routing/routing.xml)) by default: [{% data variables.ios-values.app_mode_boat %}](/osmand/navigation/boat-navigation#boat), [{% data variables.ios-values.m_style_bicycle %}](/osmand/navigation/route-navigation), [{% data variables.ios-values.nav_type_direct_to %}](/osmand/navigation/boat-navigation#direct-to-point), [{% data variables.ios-values.m_style_car %}](/osmand/navigation/route-navigation), [{% data variables.ios-values.rendering_value_pedestrian_name %}](/osmand/navigation/route-navigation), [{% data variables.ios-values.m_style_pulic_transport %}](/osmand/map/public-transport), [{% data variables.ios-values.nav_type_ski %}](/osmand/plugins/ski-maps), [{% data variables.ios-values.nav_type_straight_line %}](/osmand/navigation/boat-navigation#straight-line). |
| **{% data variables.ios-values.route_parameters %}:** |  allows setting routing for any cases and showing additional info about roads.   |              |
| "{% data variables.ios-values.recalculate_route %}" |  {% data variables.ios-values.route_recalculation_descr %}    |              |
| "{% data variables.ios-values.recalculate_wrong_dir %}"  |  the route will be recalculated if you are moving to the start point.   |              |
| "{% data variables.ios-values.routing_attr_driving_style_name %}"   |  select driving puprose to get shorter, faster, safer or unpaved route. | "{% data variables.ios-values.routing_attr_driving_style_prefer_unpaved_name %}": prefer unpaved over paved roads for routing.<br>  "{% data variables.ios-values.routing_attr_driving_style_safety_name %}": prefer safer roads for routing.<br> "{% data variables.ios-values.routing_attr_driving_style_balance_name %}": prefer faster way for routing.<br>  "{% data variables.ios-values.routing_attr_driving_style_speed_name %}": prefer shorter way for routing.<br>     |
| "{% data variables.ios-values.impassable_road %}" |  avoid certain routes and road types for routing:    |   Navigation types and notes           |
|                 |  "{% data variables.ios-values.routing_attr_avoid_unpaved_name %}"    |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_stairs_name %}"    |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_borders_name %}"    |              |
|                 |  "Avoid footways"    |              |
|                 |  "Avoid tunnels"    |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_sett_name %}"|              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_toll_name %}"|              |
|                 |  "Avoid low emissions zones"    |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_shuttle_train_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_motorway_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_ice_roads_fords_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_train_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_subway_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_ferries_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_tram_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_bus_name %}" |              |
|                 |  "{% data variables.ios-values.routing_attr_avoid_share_taxi_name %}" |              |
| "{% data variables.ios-values.routing_attr_relief_smoothness_factor_name %}" |  allows choosing relief parameters for the routing. The routing could avoid strong uphills:   |   Cycling routing |
|   | "{% data variables.ios-values.routing_attr_relief_smoothness_factor_more_plains_name %}"  | Routing could avoid strong uphills.    | 
|   | "{% data variables.ios-values.routing_attr_relief_smoothness_factor_plains_name %}"  | Routing could avoid strong uphills.    | 
|   | "{% data variables.ios-values.routing_attr_relief_smoothness_factor_hills_name %}"  | Routing could avoid strong uphills.    |  
| "{% data variables.ios-values.routing_attr_height_obstacles_name %}" |  Using elevation fluctuation for routing.  |    |
| "{% data variables.ios-values.routing_attr_allow_motorway_name %}" |  using Motorways for routing  |   Cycling routing |
| "{% data variables.ios-values.routing_attr_allow_private_name %}" |  ignore the Private Access restriction for routing  |    |
| "{% data variables.ios-values.consider_limitations_param %}" |  using temporaty limitations for routing from OpenStreetMap data  |    |
| "{% data variables.ios-values.road_speeds %}" |  setting the minimum and the maximum travel speed for all roads in the route.  |    |
| **{% data variables.ios-values.voice_announces %}** | on/off and settings of [voice guidance](/osmand/navigation/voice-navigation) during navigation.    |  {% data variables.ios-values.speak_descr %}  |
| **{% data variables.ios-values.screen_alerts %}** | showing or not alerts on the screen like a widget.  | [Types of alert widgets](/osmand/widgets/nav-widgets#alert-widget)   |
| **{% data variables.ios-values.vehicle_parameters %}** | specified vehicle parameters may affect routing:   |   |
|     | {% data variables.ios-values.default_speed %}  | {% data variables.ios-values.default_speed_dialog_msg %}   |
|     | {% data variables.ios-values.routing_attr_weight_name %}   | {% data variables.ios-values.weight_limit_description %}   |
|     | {% data variables.ios-values.routing_attr_height_name %}  | {% data variables.ios-values.height_limit_description %}   |
|     | {% data variables.ios-values.routing_attr_length_name %}  | {% data variables.ios-values.lenght_limit_description %}   |
|     | {% data variables.ios-values.routing_attr_width_name %} | {% data variables.ios-values.width_limit_description %}   |

{% endios %}

#### **Other**

Parameters for "Map during navigation" and others:

{% data reusables.general.android-ios-switcher %}

{% android %}

| Parameter | Description | Note |
|:------------|:---------------|:---------------|
| **{% data variables.android-values.map_during_navigation %}:** |  Change map behavior during navigation.   |              |
| "{% data variables.android-values.choose_auto_follow_route %}" |  {% data variables.android-values.choose_auto_follow_route_descr %}.   |  Value: Never, 5 sec, 10 sec, 15 sec, 20 sec, 25 sec, 30 sec, 45 sec, 60 sec, 50 sec.|
| "{% data variables.android-values.auto_zoom_map %}"  |  {% data variables.android-values.auto_zoom_map_descr %}.   | Value: {% data variables.android-values.auto_zoom_none %}, {% data variables.android-values.auto_zoom_farthest %}, {% data variables.android-values.auto_zoom_far %}, {% data variables.android-values.auto_zoom_close %}. |
| "{% data variables.android-values.map_orientation_change_in_accordance_with_speed %}"  |  [{% data variables.android-values.map_orientation_change_in_accordance_with_speed_descr %}](/osmand/map/interact-with-map#map-orientation-modes).   | Value: 0 km/h, 5 km/h, 7 km/h, 10 km/h, 15 km/h, 20 km/h.    |
| "{% data variables.android-values.snap_to_road %}"  |  {% data variables.android-values.snap_to_road_descr %}.   |    |
| **{% data variables.android-values.animate_my_location %}** |  {% data variables.android-values.animate_my_location_desc %}   |              |

{% endandroid %}

{% ios %}

| Parameter | Description | Note |
|:------------|:---------------|:---------------|
| **Map during navigation:** |  Change map behavior during navigation.   |              |
| "{% data variables.ios-values.choose_auto_follow_route %}" |  {% data variables.ios-values.choose_auto_center_map_view_descr %}.   |  Value: Never, 5 sec, 10 sec, 15 sec, 20 sec, 25 sec, 30 sec, 45 sec, 60 sec, 50 sec.|
| "{% data variables.ios-values.auto_zoom_map %}"  |  {% data variables.ios-values.auto_zoom_map_descr %}.   | Value: {% data variables.ios-values.auto_zoom_none %}, {% data variables.ios-values.auto_zoom_farthest %}, {% data variables.ios-values.auto_zoom_far %}, {% data variables.ios-values.auto_zoom_close %}. |
| "{% data variables.ios-values.map_orientation_change_in_accordance_with_speed %}"  |  [{% data variables.ios-values.map_orientation_change_in_accordance_with_speed_descr %}](/osmand/map/interact-with-map#map-orientation-modes).   | Value: 0 km/h, 5 km/h, 7 km/h, 10 km/h, 15 km/h, 20 km/h.    |
| "{% data variables.ios-values.snap_to_road %}"  |  {% data variables.ios-values.snap_to_road_descr %}.   |    |

{% endios %}


### Configure map

Here you can set parameters for [{% data variables.android-values.configure_map %}](/osmand/map/configure-map-menu) of chosen profile

[{% data variables.android-values.configure_map %}](/osmand/map/configure-map-menu) menu is a central place where you could configure map display for your profile needs, i.e. highlight [Favorite points](/osmand/personal/favorites), [Navigation markers](/osmand/personal/markers) or special [Points of Interests](/osmand/map/point-layers-on-map#points-of-interest-poi) on the map; display specific routes or 3rd party GPX files; [overlay the map with relief information](/osmand/plugins/contour-lines), [satellite imagery or any other available raster map](/osmand/map/raster-maps); display [public transport information](/osmand/map/public-transport) and [change the map style](/osmand/map/vector-maps#default-map-styles).

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.configure_map %}

Set parameters for [Configure map](/osmand/map/configure-map-menu) menu for chosen profile.

![Profiles Configure map Settings Android](/assets/images/personal/profiles/profile_configure_map_settings_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.configure_map %}

Set parameters for [Configure map](/osmand/map/configure-map-menu) menu for chosen profile.

![Profiles Configure map Settings iOS](/assets/images/personal/profiles/profile_configure_map_settings_ios.png)

{% endios %}


### Configure screen

Here you can set parameters for [{% data variables.android-values.map_widget_config %}](/osmand/widgets/configure-screen) of chosen profile.

[{% data variables.android-values.map_widget_config %}](/osmand/widgets/configure-screen) is a menu that allows to configure what widgets will be displayed over the map. It allows you to enable and configure [Quick action](/osmand/widgets/quick-action), [Informational](/osmand/widgets/info-widgets) & [Navigational](/osmand/widgets/nav-widgets) widgets and other elements.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.layer_map_appearance %}

Set parameters for [Configure screen](/osmand/widgets/configure-screen) menu for chosen profile.

![Profiles Configure screen Settings Android](/assets/images/personal/profiles/profile_configure_screen_settings_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.layer_map_appearance %}

Set parameters for [Configure screen](/osmand/widgets/configure-screen) menu for chosen profile.

![Profiles Configure screen Settings iOS](/assets/images/personal/profiles/profile_configure_screen_settings_ios.png)

{% endios %}

### Profile appearance

You can choose the color of the profile elements, its icon and name, also assign icons on the map for movement and without.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.profile_appearance %}

| Parameter | Description | Note |
|:------------|:---------------|:---------------|
| "{% data variables.android-values.profile_name_hint %}"| entering a profile name |     |
| "{% data variables.android-values.profile_appearance %}"| changing color and label for chosen profile: |     |
|       | "{% data variables.android-values.select_color %}" |  choosing color for a profile icon and menu   |
|       | "{% data variables.android-values.select_icon_profile_dialog_title %}" | choosing label for a profile icon    |
|       | ![Profile Appearance Android](/assets/images/personal/profiles/profile_appearance_android.png) |   |
| "{% data variables.android-values.appearance_on_the_map %}"| changing position icons: |     |
|       | "{% data variables.android-values.select_map_icon %}" |  choosing label for a profile icon without moving   |
|       | ![Profile Appearance at rest Android](/assets/images/personal/profiles/profile_appearance_atrest_android.png) |   |
|       | "{% data variables.android-values.select_navigation_icon %}" |  choosing label for a profile icon while moving   |
|       | ![Profile Appearance on the map Android](/assets/images/personal/profiles/profile_appearance_moving_android.png) |   |


{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.profile_appearance %}

| Parameter | Description | Note |
|:------------|:---------------|:---------------|
| "{% data variables.ios-values.fav_name %}"| entering a profile name |     |
| "{% data variables.ios-values.map_settings_appearance %}"| changing color and label for chosen profile: |     |
|       | "{% data variables.ios-values.select_color %}" |  choosing color for a profile icon and menu   |
|       | "{% data variables.ios-values.select_icon %}" | choosing label for a profile icon    |
|       | ![Profile Appearance iOS](/assets/images/personal/profiles/profile_appearance_ios.png) |   |
| "{% data variables.ios-values.appearance_on_map %}"| changing position icons: |     |
|       | "{% data variables.ios-values.position_icon_at_rest %}" |  choosing label for a profile icon without moving   |
|       | "{% data variables.ios-values.position_icon_while_moving %}" |  choosing label for a profile icon while moving    |
|       | ![Profile Appearance on the map iOS](/assets/images/personal/profiles/profile_appearance_onthemap_ios.png) |   |

{% endios %}

### UI Customization

Customize the quantity of items in ["{% data variables.android-values.shared_string_drawer %}"](/osmand/start-with/main-menu#main-menu-drawer), ["{% data variables.android-values.configure_map %}"](/osmand/map/configure-map-menu) and ["{% data variables.android-values.context_menu_actions %}"](/osmand/map/map-context-menu).

{% note %}
Turn off unused [plugins](/osmand/plugins) for hide all their controls.
{% endnote %}

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} → {% data variables.android-values.ui_customization %}

Under each menu there is the info about items quantity / active items.

![Profile UI Customization Android](/assets/images/personal/profiles/profile_ui_customization_android.png)


**Drawer**

In this part of the menu you reorder or hide items from the [Drawer](/osmand/start-with/main-menu#main-menu-drawer).

| Actions | Note |
|:---------------|:---------------|
| "Minus" | These items are hidden from the menu, but the represented options or plugins will continue to work.  |
| "Moving" | These items are moved to other positions in the menu.  |
| ![Profile Drawer Android](/assets/images/personal/profiles/profile_drawer_moving_android.png) |   |
| "Reset" | These items are reset from the "Hidden" part of the menu to the visible. |
| ![Profile Reset Android](/assets/images/personal/profiles/profile_drawer_reset_item_android.png) |   |
| "{% data variables.android-values.reset_to_default %}" | resetting the "Drawer" menu to default. |
| "{% data variables.android-values.copy_from_other_profile %}" | coping the "Drawer" menu from another profile.  |
| ![Profile Copy Android](/assets/images/personal/profiles/profile_drawer_reset_copy_android.png) |   |

**Configure map**

In this part of the menu you reorder or hide items from the [Configure map](/osmand/map/configure-map-menu) menu.

| Actions | Note |
|:---------------|:---------------|
| "Minus" | These items are hidden from the menu, but the represented options or plugins will continue to work.  |
| "Moving" | These items are moved to other positions in the menu.  |
| ![Profile Configure map menu Android](/assets/images/personal/profiles/profile_configure_moving_android.png) |   |
| "Reset" | These items are reset from the "Hidden" part of the menu to the visible. |
| ![Profile Configure map menu Reset Android](/assets/images/personal/profiles/profile_configure_reset_item_android.png) |   |
| "{% data variables.android-values.reset_to_default %}" | resetting the "Configure map" menu to default. |
| "{% data variables.android-values.copy_from_other_profile %}" | coping the "Configure map" menu from another profile.  |
| ![Profile Configure map menu Copy Android](/assets/images/personal/profiles/profile_configure_reset_copy_android.png) |   |


**Context menu actions**

In this part of the menu you reorder or hide items from the [Context menu actions](/osmand/map/map-context-menu) menu.

| Actions | Note |
|:---------------|:---------------|
| "Minus" | These items are hidden from the menu, but the represented options or plugins will continue to work.  |
| "Moving" | These items are moved to other positions in the menu.  |
| ![Profile Configure map menu Android](/assets/images/personal/profiles/profile_context_moving_android.png) |   |
| "Reset" | These items are reset from the "Hidden" part of the menu to the visible. |
| ![Profile Configure map menu Reset Android](/assets/images/personal/profiles/profile_context_reset_item_android.png) |   |
| "{% data variables.android-values.reset_to_default %}" | resetting the "Context menu actions" menu to default. |
| "{% data variables.android-values.copy_from_other_profile %}" | coping the "Context menu actions" menu from another profile.  |
| ![Profile Configure map menu Copy Android](/assets/images/personal/profiles/profile_context_reset_copy_android.png) |   |

{% endandroid %}


## Plugin settings

[Plugins](https://docs.osmand.net/en/main@latest/osmand/plugins) are a collection of settings that can be enabled with one click. Plugins also unlock additional functions of the application, they can be either [paid or free](/osmand/purchases). Some plugins have their own settings. Among other things, you can enable or disable plugins for each profile separately.

{% note %}
Plugins must be enabled in [the Plugin list](/osmand/plugins) for activating it in the setting list for the profile.
{% endnote %}

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %}

![Profile Settings Plugins Android](/assets/images/personal/profiles/profile_plugins_android.png)

{% endandroid %}

{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.plugins %}

![Profile Settings Plugins iOS](/assets/images/personal/profiles/profile_plugins_ios.png)

{% endios %}

### Trip recording

This menu opens [the trip recording settings](/osmand/plugins/trip-recording#trip-recording-plugin-settings) for the selected profile. Where you can choose any parameters for recording your trip.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %} → {% data variables.android-values.record_plugin_name %}

{% endandroid %}


{% ios %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.sett_settings %} → {% data variables.ios-values.app_profiles %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.track_recording %}

{% endios %}

### Audio / Video notes

This menu opens [audio-video plugin settings](/osmand/plugins/audio-video-notes#plugin-settings) for the selected profile. Where you can choose any parameters for your needed.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %} → {% data variables.android-values.audionotes_plugin_name %}

{% endandroid %}

{% ios %}

{% note %}
Not exist for iOS version.
{% endnote %}

{% endios %}

### OpenStreetMap editing

This menu opens [the OpenStreetMap editing plugin settings](/osmand/plugins/osm-editing#plugin-settings) for the selected profile. Where you can input your data for starting OSM edit.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %} → {% data variables.android-values.osm_editing_plugin_name %}

{% endandroid %}

{% ios %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %} → {% data variables.android-values.product_title_osm_editing %}

{% endios %}

### OpenPlaceReviews

This menu opens [the OpenPlaceReviews plugin settings](/osmand/plugins/openplacereviews#plugin-settings) for the selected profile. Where you can input your data for starting added reviews of any places.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %} → {% data variables.android-values.open_place_reviews %}

{% endandroid %}

{% ios %}

{% note %}
Not exist for iOS version.
{% endnote %}

{% endios %}

### Accesibility

This menu opens [Accessibility plugin settings](/osmand/plugins/accessibility) for the selected profile. Where you can choose any parameters for your needed.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %} → {% data variables.android-values.shared_string_accessibility %}

{% endandroid %}

{% ios %}

{% note %}
Not exist for iOS version.
{% endnote %}

{% endios %}

### OsmAnd development

This menu opens [Development plugin settings](/osmand/plugins/accessibility) for the selected profile. Settings for development and debugging features, like navigation simulation, rendering performance, or voice prompting. Intended for developers, not needed for normal app use.

{% data reusables.general.android-ios-switcher %}

{% android %}

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.configure_profile %} (Browse map or any other profile) → {% data variables.android-values.plugins_settings %} → {% data variables.android-values.development %}

{% endandroid %}

{% ios %}

{% note %}
Not exist for iOS version.
{% endnote %}

{% endios %}

## Actions

Actions with chosen profile: export, copy from another profile, reset to default, delete profile:

{% data reusables.general.android-ios-switcher %}

{% android %}

![Profiles Actions Settings Android](/assets/images/personal/profiles/profile_actions_settings_android.png)

- {% data variables.android-values.export_profile %}
- {% data variables.android-values.copy_from_other_profile %}
- {% data variables.android-values.map_widget_reset %}
- {% data variables.android-values.profile_alert_delete_title %}

{% endandroid %}

{% ios %}

![Profiles Actions Settings iOS](/assets/images/personal/profiles/profile_actions_settings_ios.png)
- {% data variables.android-values.export_profile %}
- {% data variables.android-values.copy_from_other_profile %}
- {% data variables.android-values.map_widget_reset %}
- {% data variables.android-values.profile_alert_delete_title %}

{% endios %}

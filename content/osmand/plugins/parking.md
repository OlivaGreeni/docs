---
title: "{% data variables.android-values.osmand_parking_plugin_name %}"
intro: "It keeps the information about the exact location of your car and helps you keep track of time."
versions: '*'
---
{% data reusables.general.article-not-complete %}

Parking plugin is a free plugin working with the main OsmAnd Maps and Navigation app. It keeps the information about the exact location of your car and helps you keep track of time. All you have to do is set the type of parking you are using (with or without a time limit) and set the alarm if needed.

![Pakring plugin view Android](/assets/images/plugins/parking/parking_plugin_view_android.png) ![Pakring plugin view iOS](/assets/images/plugins/parking/parking_plugin_view_ios.png)


## Enable / Disable Plugin

Before starting to use or not option for marking a parking postion on the map you need to Enable / Disable plugin:

{% data variables.product.android_button_seq %} {% data variables.android-values.shared_string_menu %} → {% data variables.android-values.plugins_menu_group: %} → {% data variables.android-values.osmand_parking_plugin_name %}

{% data variables.product.ios_button_seq %} {% data variables.ios-values.menu %} → {% data variables.ios-values.plugins %} → {% data variables.ios-values.product_title_parking %}

![Pakring plugin Android](/assets/images/plugins/parking/parking_plugin_android.png) ![Pakring plugin iOS](/assets/images/plugins/parking/parking_plugin_ios.png)


## Parking point on the map

To mark parking place on the map user has to:

Step 1: Zoom in the map 

Step 2: Make the long tap on the map  

Step 3: Click [‘Actions’ button ](/osmand/map/map-context-menu#-add--delete-parking-point) and choose ‘Mark as parking location’ 

![Action Parking Android](/assets/images/map/action_parking_android.png) ![Action Parking iOS](/assets/images/map/action_parking_ios.png)

Step 4: Choose one of the parking options Time-unlimited or Time-limited parking.

The following menu will show the configurations of the parking spot such as parking time and date, information about parking limitation, distance from the current location to the parking spot.

![Action Parking set point Android](/assets/images/plugins/parking/parking_set_android.png) ![Action Parking set point iOS](/assets/images/plugins/parking/parking_set_ios.png)

## Parking widget 

[Parking widget](/osmand/widgets/info-widgets#-parking-widget) shows distance from user position or center map to Parking place.

Clicking to the widget moves map view to the parking position.

![Parking widget Android](/assets/images/plugins/parking/parking_widget_android.png) ![Parking widget iOS](/assets/images/plugins/parking/parking_widget_ios.png)

## Delete parking point

User can delete the parking location marker anytime. Click to the parking point and ‘Delete’ button in [Map Context menu](/osmand/map/map-context-menu#-add--delete-parking-point).

It will be removed from the map and from the calendar if such option has been chosen earlier.

![Action Delete Parking Android](/assets/images/map/context_menu_limited_parking.png) ![Action Delete Parking iOS](/assets/images/map/context_menu_limited_parking_ios.png)

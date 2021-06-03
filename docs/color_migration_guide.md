# Color migration

Some colors and color attribute has been removed, here is the list and what has to be used now.

This file can help Element Android forks maintainers to migrate their code.

- ?riotx_background -> ?android:colorBackground
- riotx_background_light -> element_background_light
- riotx_background_dark -> element_background_dark
- riotx_background_black -> element_background_black

- riotx_accent -> ?colorPrimary
- riotx_positive_accent -> ?colorPrimary
- riotx_accent_alpha25 -> color_primary_alpha25
- riotx_notice -> ?colorError
- riotx_destructive_accent -> ?colorError
- vector_error_color -> ?colorError
- vector_warning_color -> ?colorError

- riotx_bottom_sheet_background -> ?colorSurface
- riotx_alerter_background -> ?colorSurface

- riotx_username_1 -> element_name_01
- riotx_username_2 -> element_name_02
- riotx_username_3 -> element_name_03
- riotx_username_4 -> element_name_04
- riotx_username_5 -> element_name_05
- riotx_username_6 -> element_name_06
- riotx_username_7 -> element_name_07
- riotx_username_8 -> element_name_08

- riotx_avatar_fill_1 -> element_room_01
- riotx_avatar_fill_2 -> element_room_02
- riotx_avatar_fill_3 -> element_room_03

- white -> @android:color/white
- black -> @android:color/black or emoji_color

- riotx_list_bottom_sheet_divider_color -> ?element_header_background
- vctr_list_header_background_color -> ?element_header_background
- vctr_list_divider_color -> ?element_header_background
- list_divider_color -> ?element_header_background
- riotx_header_panel_text_secondary -> ?element_header_background
- riotx_header_panel_background -> ?element_header_background
- vctr_home_drawer_header_background -> ?element_header_background
- riotx_header_panel_border_mobile -> ?element_header_background

- link_color_light -> element_link_light
- link_color_dark -> element_link_dark

- vctr_toolbar_primary_text_color -> riotx_text_primary
- vctr_toolbar_secondary_text_color -> riotx_text_primary

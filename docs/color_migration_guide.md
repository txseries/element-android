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

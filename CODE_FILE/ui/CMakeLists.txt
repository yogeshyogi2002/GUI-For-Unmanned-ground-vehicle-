SET(SOURCES screens/ui_Screen1.c
    screens/ui_Screen2.c
    screens/ui_Screen3.c
    screens/ui_Screen4.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_pentagon_logo_png.c
    images/ui_img_settings_png.c
    images/ui_img_battery_2_png.c
    fonts/ui_font_Font16.c)

add_library(ui ${SOURCES})

SET(SOURCES ui_Screen1.c
    ui.c
    ui_comp_hook.c
    ui_helpers.c
    ui_img_3_95inch_png.c
    ui_img_temp_png.c
    ui_img_hum_png.c
    ui_img_co2_png.c
    ui_img_tvoc_png.c
    ui_img_makerfabs3_png.c)

add_library(ui ${SOURCES})

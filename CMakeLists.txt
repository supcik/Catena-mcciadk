# MCCI® ADK.
# A version of the MCCI XDK adapted for use on Catena®-like Arduinos
# by MCCI Corporation.
# https://github.com/mcci-catena/Catena-mcciadk
# MIT License

cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS
    src/lib/mcciadklib_stringcomparecaseinsensitive.c
    src/lib/mcciadklib_formatdumpline.c
    src/lib/mcciadklib_buffertoulong.c
    src/lib/mcciadklib_multiszindex.c
    src/lib/mcciadklib_snprintf.c
    src/lib/mcciadklib_safecopystring.c

    INCLUDE_DIRS src)

project(Catena-mcciadk)

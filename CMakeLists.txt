add_library(imgui STATIC
        imconfig.h
        imgui.h
        imgui.cpp
        imgui_demo.cpp
        imgui_draw.cpp
        imgui_internal.h
        imgui_tables.cpp
        imgui_widgets.cpp
        imstb_rectpack.h
        imstb_textedit.h
        imstb_truetype.h)
target_include_directories(imgui PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
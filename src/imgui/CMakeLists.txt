cmake_minimum_required(VERSION 3.8...4.4)
project(imgui)

#------ sources ------
set( IMGUI_SRC
	imconfig.h
	imgui.cpp
	imgui_demo.cpp
	imgui_draw.cpp
	imgui_impl_dx12.cpp
	imgui_impl_dx12.h
	imgui_impl_win32.cpp
	imgui_impl_win32.h
	imgui_internal.h
	imgui_tables.cpp
	imgui_widgets.cpp
	imstb_rectpack.h
	imstb_textedit.h
	imstb_truetype.h
)

#------ target -----
add_library( imgui STATIC ${IMGUI_SRC} )
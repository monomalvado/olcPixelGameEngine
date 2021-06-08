cmake_minimum_required(VERSION 3.19)
project(olcPixelGameEngine)

set(CMAKE_CXX_STANDARD 17)

include_directories(C:/Developer/C_CPP/asio-1.18.2/include)
include_directories(C:/Developer/C_CPP/projects/freetype-windows-binaries-2.10.4/include)
link_directories(C:/Developer/C_CPP/projects/freetype-windows-binaries-2.10.4/win64)

add_library(${PROJECT_NAME}
        olcPixelGameEngine.cpp
)
link_libraries(
        user32 gdi32 opengl32 gdiplus Shlwapi dwmapi # Windows API stuff
        dinput8 dxguid ole32 oleaut32 # Gamepad Extension
        freetype # For TTF Extension
)

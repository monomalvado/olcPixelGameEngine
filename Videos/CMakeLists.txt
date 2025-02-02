cmake_minimum_required(VERSION 3.19)

set(CMAKE_CXX_STANDARD 17)


add_executable(DungeonWarping
        Videos/OneLoneCoder_PGE_DungeonWarping.cpp)
add_executable(Engine3D
        Videos/OneLoneCoder_PGE_olcEngine3D.cpp)
add_executable(IsometricTiles
        Videos/OneLoneCoder_PGE_IsometricTiles.cpp)
add_executable(Mandlebrot
        Videos/OneLoneCoder_PGE_Mandelbrot.cpp)
add_executable(MMO_Client
        Videos/Networking/Parts3&4/MMO_Client.cpp)
add_executable(MMO_Server
        Videos/Networking/Parts3&4/MMO_Server.cpp)
add_executable(PathFinding
        Videos/OneLoneCoder_PGE_PathFinding_WaveProp.cpp)
add_executable(RayCasting
        Videos/OneLoneCoder_PGE_RayCastDDA.cpp)
add_executable(RetroMenu
        Videos/OneLoneCoder_PGE_RetroMenu.cpp)
add_executable(SlidingBlock
        Videos/OneLoneCoder_PGE_SlidingBlockPuzzle.cpp)
add_executable(SoundTest
        Videos/OneLoneCoder_PGE_SoundTest.cpp)
add_executable(SpriteTransforms
        Videos/OneLoneCoder_PGE_SpriteTransforms.cpp)

add_executable(CarCrimeCityPart1
        Videos/CarCrimeCity/Part1/OneLoneCoder_CarCrimeCity1.cpp)

add_executable(CarCrimeCityPart2
        Videos/CarCrimeCity/Part2/cAutomata.cpp
        Videos/CarCrimeCity/Part2/cCarCrimeCity.cpp
        Videos/CarCrimeCity/Part2/cCell.cpp
        Videos/CarCrimeCity/Part2/cCell_Building.cpp
        Videos/CarCrimeCity/Part2/cCell_Plane.cpp
        Videos/CarCrimeCity/Part2/cCell_Road.cpp
        Videos/CarCrimeCity/Part2/cCell_Water.cpp
        Videos/CarCrimeCity/Part2/cCityMap.cpp
        Videos/CarCrimeCity/Part2/cGameSettings.cpp
        Videos/CarCrimeCity/Part2/olcPixelGameEngine.cpp
        Videos/CarCrimeCity/Part2/main.cpp
        )
target_link_libraries(
        CarCrimeCityPart2
        user32 gdi32 opengl32 gdiplus Shlwapi dwmapi
        dinput8 dxguid ole32 oleaut32
)
# ---------------------- cmake setup

cmake_minimum_required(VERSION 3.6)

# --- add files to volume target in parent directory

target_sources(volume PRIVATE
volume/ellipsoid/ellipsoid.c
volume/ellipsoid/ellipsoid.h
)

add_subdirectory(intersectCoord)
add_subdirectory(cacheUpdateCoord)
add_subdirectory(cacheReset)

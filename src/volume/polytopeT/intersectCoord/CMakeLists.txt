# ---------------------- cmake setup

cmake_minimum_required(VERSION 3.6)

# --- add files to volume target in parent directory

target_sources(volume PRIVATE
volume/polytopeT/intersectCoord/intersectCoord.h
volume/polytopeT/intersectCoord/intersectCoord.c
)


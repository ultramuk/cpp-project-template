# =============================================================================
# Add External Package: Catch2
# =============================================================================
# This script adds the Catch2 library as an external package.

include(${CMAKE_SOURCE_DIR}/cmake/library/add_external_package.cmake)

add_external_package(
  REPOSITORY_URL "https://github.com/catchorg/Catch2.git"
  REPOSITORY_TAG "v3.8.1"
  LIBRARIES catch2::catch2
)

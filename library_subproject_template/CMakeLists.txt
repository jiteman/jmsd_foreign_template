cmake_minimum_required( VERSION 3.7.1 )

project( library_subproject_template )

include( ${JMSD_CMAKE_SETTINGS_PATH}/verbosity/project-group-header.cmake )

add_subdirectory( base_library_template )
add_subdirectory( derived_library_template )

include( ${JMSD_CMAKE_SETTINGS_PATH}/verbosity/project-group-footer.cmake )

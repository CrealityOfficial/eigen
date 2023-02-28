if(CC_INSTALL_EIGEN)
	__install_directory_specif(${CMAKE_CURRENT_SOURCE_DIR}/ eigen)
endif()

add_library(eigen INTERFACE)
set_property(TARGET eigen PROPERTY INTERFACE_INCLUDE_DIRECTORIES ${CMAKE_CURRENT_SOURCE_DIR})
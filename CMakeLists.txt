__add_include_interface(eigen INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

if(CC_INSTALL_EIGEN)
	__install_directory_specif(${CMAKE_CURRENT_SOURCE_DIR}/ eigen)
endif()
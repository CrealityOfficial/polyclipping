__add_real_target(polyclipping lib SOURCE polyclipping/clipper.hpp
										  polyclipping/clipper.cpp
								   INTERFACE
										  ${CMAKE_CURRENT_SOURCE_DIR}
										  )
										  
if(CC_INSTALL_POLYCLIPPING)
	__install_directory_specif(${CMAKE_CURRENT_SOURCE_DIR}/ polyclipping)
endif()
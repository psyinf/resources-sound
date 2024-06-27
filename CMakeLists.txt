project(resources-sound)
set(INSTALL_PATH "." CACHE STRING "destination directory for the resources")
install(DIRECTORY
		data
	DESTINATION
		${INSTALL_PATH}
	COMPONENT
		${RUNTIME_COMPONENT}
)
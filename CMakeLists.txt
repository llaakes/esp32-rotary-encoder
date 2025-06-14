#idf_component_register(SRCS "rotary_encoder.c" INCLUDE_DIRS include)

set(COMPONENT_ADD_INCLUDEDIRS include)
set(COMPONENT_SRCS "rotary_encoder.c")
set(COMPONENT_REQUIRES "driver")
register_component()

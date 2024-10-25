set(COMPONENT_SRCS
  hsu/src/pn532-hsu.c
)

set(COMPONENT_ADD_INCLUDEDIRS
  inc/
  hsu/include
)

set(COMPONENT_REQUIRES driver)

register_component()
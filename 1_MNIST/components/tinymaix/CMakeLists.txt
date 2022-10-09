set(SRCS_TINYMAIX 
    src/tm_layers_fp8.c
    src/tm_layers_O1.c
    src/tm_layers.c
    src/tm_model.c
    src/tm_stat.c
    )

set(INCLUDE_TINYMAIX 
    "tmdl/"
    "src/"
    "include/")

idf_component_register(
    SRCS ${SRCS_TINYMAIX}
    INCLUDE_DIRS ${INCLUDE_TINYMAIX}
)
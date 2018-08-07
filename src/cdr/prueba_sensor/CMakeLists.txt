px4_add_module(
    MODULE cdr__prueba_sensor
    MAIN prueba_sensor
    STACK_MAIN 2000
    SRCS
        prueba_sensor.c
    DEPENDS
        platforms__common
    )

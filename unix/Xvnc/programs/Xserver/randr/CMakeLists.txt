include_directories(../mi ../render)

handle_type_puns()

add_library(randr STATIC
	randr.c
	rrcrtc.c
	rrdispatch.c
	rrinfo.c
	rrmode.c
	rroutput.c
	rrpointer.c
	rrproperty.c
	rrscreen.c
	rrsdispatch.c
	rrtransform.c)

include ../../common/SERIAL.defs

##### User configurable options #####

OPTFLAGS    = $(DEFAULT_OPT_FLAGS) -restrict
#description: change above into something that is a decent optimization on you system

#uncomment any of the following flags (and change values) to change defaults

RESTRICTFLAG = -DRESTRICT_KEYWORD
#description: the "restrict" keyword can be used on IA platforms to disambiguate  
#             data accessed through pointers

#DEBUGFLAG   = -DVERBOSE
#description: default diagnostic style is silent

USERFLAGS    = -strict-ansi -vec-report3 -restrict
#description: parameter to specify optional flags

#set the following variables for custom libraries and/or other objects
EXTOBJS      = 
LIBS         =
LIBPATHS     = 
INCLUDEPATHS = 

### End User configurable options ###

TUNEFLAGS    = $(DEBUGFLAG) $(USERFLAGS) $(RESTRICTFLAG)
PROGRAM      = transpose
OBJS         = $(PROGRAM).o $(COMOBJS)

include ../../common/make.common

# For Mac.
CFLAGS += -I/opt/homebrew/include
LDFLAGS += -L/opt/homebrew/lib

all:
	env LIBS="-lSDL2 -lSDL2_ttf -lSDL2_image -lSDL2_mixer" CFLAGS="$(CFLAGS)" \
	    LDFLAGS="$(LDFLAGS)" mys run

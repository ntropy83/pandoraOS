
TARGET=init
CSOURCES = $(shell echo *.c)
OBJECTS = $(CSOURCES:.c=_c.o)

LDFLAGS = -L$(MYOS_PATH)/lib
LDFLAGSEND = -lmy

all: $(TARGET)

$(TARGET): $(OBJECTS)
	$(CC) $(LDFLAGS) $(FLAGS) -o $(TARGET) $(OBJECTS) $(LDFLAGSEND)

include ../base.mk

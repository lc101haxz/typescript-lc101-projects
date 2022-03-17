SRCS = parts1-5.ts SpaceLocation.ts
OBJS = $(SRCS:.ts=.js)

all: target

target:
	tsc $(SRCS)

test: target
	node parts1-5.js

clean:
	rm -f $(OBJS)


include ../../GDALmake.opt

OBJ	=	rasterlitedataset.o rasterlitecreatecopy.o rasterliteoverviews.o

CPPFLAGS	:=	 $(CPPFLAGS) -iquote ../../ogr -iquote ../mem

default:	$(OBJ:.o=.$(OBJ_EXT))

clean:
	rm -f *.o $(O_OBJ)

install-obj:	$(O_OBJ:.o=.$(OBJ_EXT))

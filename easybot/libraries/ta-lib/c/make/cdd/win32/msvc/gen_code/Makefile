#############################################################################
# Makefile for building gen_code
# Generated by tmake;
#     Project: gen_code/gen_code
#    Template: app
#############################################################################

####### Compiler, tools and options

CC	=	cl
CXX	=	cl
CFLAGS	=	-nologo -W3 -MDd -Zi -DTA_GEN_CODE -DTA_DEBUG -D_DEBUG -DWIN32 -D_MBCS -D_LIB -DQT_THREAD_SUPPORT
CXXFLAGS=	-nologo -W3 -MDd -Zi -DTA_GEN_CODE -DTA_DEBUG -D_DEBUG -DWIN32 -D_MBCS -D_LIB -DQT_THREAD_SUPPORT
INCPATH	=	-I"..\..\..\..\..\include" -I"..\..\..\..\..\src\ta_common" -I"..\..\..\..\..\src\ta_abstract" -I"..\..\..\..\..\src\ta_abstract\tables" -I"..\..\..\..\..\src\ta_abstract\frames"
LINK	=	link
LFLAGS	=	/NOLOGO /DEBUG /SUBSYSTEM:console
LIBS	=	..\..\..\..\..\lib\ta_common_cdd.lib
MOC	=	moc
UIC	=	uic

ZIP	=	zip -r -9

####### Files

HEADERS =	
SOURCES =	..\..\..\..\..\src\tools\gen_code\gen_code.c \
		..\..\..\..\..\src\ta_abstract\ta_abstract.c \
		..\..\..\..\..\src\ta_abstract\ta_def_ui.c \
		..\..\..\..\..\src\ta_abstract\tables\table_a.c \
		..\..\..\..\..\src\ta_abstract\tables\table_b.c \
		..\..\..\..\..\src\ta_abstract\tables\table_c.c \
		..\..\..\..\..\src\ta_abstract\tables\table_d.c \
		..\..\..\..\..\src\ta_abstract\tables\table_e.c \
		..\..\..\..\..\src\ta_abstract\tables\table_f.c \
		..\..\..\..\..\src\ta_abstract\tables\table_g.c \
		..\..\..\..\..\src\ta_abstract\tables\table_h.c \
		..\..\..\..\..\src\ta_abstract\tables\table_i.c \
		..\..\..\..\..\src\ta_abstract\tables\table_j.c \
		..\..\..\..\..\src\ta_abstract\tables\table_k.c \
		..\..\..\..\..\src\ta_abstract\tables\table_l.c \
		..\..\..\..\..\src\ta_abstract\tables\table_m.c \
		..\..\..\..\..\src\ta_abstract\tables\table_n.c \
		..\..\..\..\..\src\ta_abstract\tables\table_o.c \
		..\..\..\..\..\src\ta_abstract\tables\table_p.c \
		..\..\..\..\..\src\ta_abstract\tables\table_q.c \
		..\..\..\..\..\src\ta_abstract\tables\table_r.c \
		..\..\..\..\..\src\ta_abstract\tables\table_s.c \
		..\..\..\..\..\src\ta_abstract\tables\table_t.c \
		..\..\..\..\..\src\ta_abstract\tables\table_u.c \
		..\..\..\..\..\src\ta_abstract\tables\table_v.c \
		..\..\..\..\..\src\ta_abstract\tables\table_w.c \
		..\..\..\..\..\src\ta_abstract\tables\table_x.c \
		..\..\..\..\..\src\ta_abstract\tables\table_y.c \
		..\..\..\..\..\src\ta_abstract\tables\table_z.c
OBJECTS =	..\..\..\..\..\temp\cdd\gen_code\gen_code.obj \
		..\..\..\..\..\temp\cdd\gen_code\ta_abstract.obj \
		..\..\..\..\..\temp\cdd\gen_code\ta_def_ui.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_a.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_b.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_c.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_d.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_e.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_f.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_g.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_h.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_i.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_j.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_k.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_l.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_m.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_n.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_o.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_p.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_q.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_r.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_s.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_t.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_u.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_v.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_w.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_x.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_y.obj \
		..\..\..\..\..\temp\cdd\gen_code\table_z.obj
INTERFACES =	
UICDECLS =	
UICIMPLS =	
SRCMOC	=	
OBJMOC	=	
DIST	=	
TARGET	=	..\..\..\..\..\bin\gen_code.exe
INTERFACE_DECL_PATH = .

####### Implicit rules

.SUFFIXES: .cpp .cxx .cc .c

.cpp.obj:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fo$@ $<

.cxx.obj:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fo$@ $<

.cc.obj:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -Fo$@ $<

.c.obj:
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo$@ $<

####### Build rules

all: $(TARGET)

$(TARGET): $(UICDECLS) $(OBJECTS) $(OBJMOC) 
	$(LINK) $(LFLAGS) /OUT:$(TARGET) @<<
	    $(OBJECTS) $(OBJMOC) $(LIBS)
<<

moc: $(SRCMOC)

tmake: ../cdd/win32/msvc/gen_code/Makefile

../cdd/win32/msvc/gen_code/Makefile: gen_code/gen_code.pro
	tmake gen_code/gen_code.pro -o ../cdd/win32/msvc/gen_code/Makefile

dist:
	$(ZIP) gen_code/gen_code.zip gen_code/gen_code.pro $(SOURCES) $(HEADERS) $(DIST) $(INTERFACES)

clean:
        -del ..\..\..\..\..\temp\cdd\gen_code\gen_code.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\ta_abstract.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\ta_def_ui.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_a.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_b.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_c.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_d.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_e.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_f.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_g.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_h.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_i.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_j.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_k.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_l.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_m.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_n.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_o.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_p.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_q.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_r.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_s.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_t.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_u.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_v.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_w.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_x.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_y.obj
	-del ..\..\..\..\..\temp\cdd\gen_code\table_z.obj
	-del $(TARGET)
	-del ../../../../../bin/*.map
	-del ../../../../../bin/*._xe
	-del ../../../../../bin/*.tds
	-del ../../../../../bin/*.pdb
	-del ../../../../../bin/*.pbo
	-del ../../../../../bin/*.pbi
	-del ../../../../../bin/*.pbt
	-del ../../../../../temp/cdd/*.pch
	-del ../../../../../temp/cdd/*.idb
	-del ../../../../../temp/cdd/gen_code/*.pch
	-del ../../../../../temp/cdd/gen_code/*.idb
	-del ../../../../../temp/cdd/gen_code/*.obj
        -del gen_code.pdb
	-del vc*.pdb
	-del gen_code.ilk

####### Compile

..\..\..\..\..\temp\cdd\gen_code\gen_code.obj: ..\..\..\..\..\src\tools\gen_code\gen_code.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\gen_code.obj ..\..\..\..\..\src\tools\gen_code\gen_code.c

..\..\..\..\..\temp\cdd\gen_code\ta_abstract.obj: ..\..\..\..\..\src\ta_abstract\ta_abstract.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\ta_abstract.obj ..\..\..\..\..\src\ta_abstract\ta_abstract.c

..\..\..\..\..\temp\cdd\gen_code\ta_def_ui.obj: ..\..\..\..\..\src\ta_abstract\ta_def_ui.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\ta_def_ui.obj ..\..\..\..\..\src\ta_abstract\ta_def_ui.c

..\..\..\..\..\temp\cdd\gen_code\table_a.obj: ..\..\..\..\..\src\ta_abstract\tables\table_a.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_a.obj ..\..\..\..\..\src\ta_abstract\tables\table_a.c

..\..\..\..\..\temp\cdd\gen_code\table_b.obj: ..\..\..\..\..\src\ta_abstract\tables\table_b.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_b.obj ..\..\..\..\..\src\ta_abstract\tables\table_b.c

..\..\..\..\..\temp\cdd\gen_code\table_c.obj: ..\..\..\..\..\src\ta_abstract\tables\table_c.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_c.obj ..\..\..\..\..\src\ta_abstract\tables\table_c.c

..\..\..\..\..\temp\cdd\gen_code\table_d.obj: ..\..\..\..\..\src\ta_abstract\tables\table_d.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_d.obj ..\..\..\..\..\src\ta_abstract\tables\table_d.c

..\..\..\..\..\temp\cdd\gen_code\table_e.obj: ..\..\..\..\..\src\ta_abstract\tables\table_e.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_e.obj ..\..\..\..\..\src\ta_abstract\tables\table_e.c

..\..\..\..\..\temp\cdd\gen_code\table_f.obj: ..\..\..\..\..\src\ta_abstract\tables\table_f.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_f.obj ..\..\..\..\..\src\ta_abstract\tables\table_f.c

..\..\..\..\..\temp\cdd\gen_code\table_g.obj: ..\..\..\..\..\src\ta_abstract\tables\table_g.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_g.obj ..\..\..\..\..\src\ta_abstract\tables\table_g.c

..\..\..\..\..\temp\cdd\gen_code\table_h.obj: ..\..\..\..\..\src\ta_abstract\tables\table_h.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_h.obj ..\..\..\..\..\src\ta_abstract\tables\table_h.c

..\..\..\..\..\temp\cdd\gen_code\table_i.obj: ..\..\..\..\..\src\ta_abstract\tables\table_i.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_i.obj ..\..\..\..\..\src\ta_abstract\tables\table_i.c

..\..\..\..\..\temp\cdd\gen_code\table_j.obj: ..\..\..\..\..\src\ta_abstract\tables\table_j.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_j.obj ..\..\..\..\..\src\ta_abstract\tables\table_j.c

..\..\..\..\..\temp\cdd\gen_code\table_k.obj: ..\..\..\..\..\src\ta_abstract\tables\table_k.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_k.obj ..\..\..\..\..\src\ta_abstract\tables\table_k.c

..\..\..\..\..\temp\cdd\gen_code\table_l.obj: ..\..\..\..\..\src\ta_abstract\tables\table_l.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_l.obj ..\..\..\..\..\src\ta_abstract\tables\table_l.c

..\..\..\..\..\temp\cdd\gen_code\table_m.obj: ..\..\..\..\..\src\ta_abstract\tables\table_m.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_m.obj ..\..\..\..\..\src\ta_abstract\tables\table_m.c

..\..\..\..\..\temp\cdd\gen_code\table_n.obj: ..\..\..\..\..\src\ta_abstract\tables\table_n.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_n.obj ..\..\..\..\..\src\ta_abstract\tables\table_n.c

..\..\..\..\..\temp\cdd\gen_code\table_o.obj: ..\..\..\..\..\src\ta_abstract\tables\table_o.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_o.obj ..\..\..\..\..\src\ta_abstract\tables\table_o.c

..\..\..\..\..\temp\cdd\gen_code\table_p.obj: ..\..\..\..\..\src\ta_abstract\tables\table_p.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_p.obj ..\..\..\..\..\src\ta_abstract\tables\table_p.c

..\..\..\..\..\temp\cdd\gen_code\table_q.obj: ..\..\..\..\..\src\ta_abstract\tables\table_q.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_q.obj ..\..\..\..\..\src\ta_abstract\tables\table_q.c

..\..\..\..\..\temp\cdd\gen_code\table_r.obj: ..\..\..\..\..\src\ta_abstract\tables\table_r.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_r.obj ..\..\..\..\..\src\ta_abstract\tables\table_r.c

..\..\..\..\..\temp\cdd\gen_code\table_s.obj: ..\..\..\..\..\src\ta_abstract\tables\table_s.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_s.obj ..\..\..\..\..\src\ta_abstract\tables\table_s.c

..\..\..\..\..\temp\cdd\gen_code\table_t.obj: ..\..\..\..\..\src\ta_abstract\tables\table_t.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_t.obj ..\..\..\..\..\src\ta_abstract\tables\table_t.c

..\..\..\..\..\temp\cdd\gen_code\table_u.obj: ..\..\..\..\..\src\ta_abstract\tables\table_u.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_u.obj ..\..\..\..\..\src\ta_abstract\tables\table_u.c

..\..\..\..\..\temp\cdd\gen_code\table_v.obj: ..\..\..\..\..\src\ta_abstract\tables\table_v.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_v.obj ..\..\..\..\..\src\ta_abstract\tables\table_v.c

..\..\..\..\..\temp\cdd\gen_code\table_w.obj: ..\..\..\..\..\src\ta_abstract\tables\table_w.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_w.obj ..\..\..\..\..\src\ta_abstract\tables\table_w.c

..\..\..\..\..\temp\cdd\gen_code\table_x.obj: ..\..\..\..\..\src\ta_abstract\tables\table_x.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_x.obj ..\..\..\..\..\src\ta_abstract\tables\table_x.c

..\..\..\..\..\temp\cdd\gen_code\table_y.obj: ..\..\..\..\..\src\ta_abstract\tables\table_y.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_y.obj ..\..\..\..\..\src\ta_abstract\tables\table_y.c

..\..\..\..\..\temp\cdd\gen_code\table_z.obj: ..\..\..\..\..\src\ta_abstract\tables\table_z.c
	$(CC) -c $(CFLAGS) $(INCPATH) -Fo..\..\..\..\..\temp\cdd\gen_code\table_z.obj ..\..\..\..\..\src\ta_abstract\tables\table_z.c


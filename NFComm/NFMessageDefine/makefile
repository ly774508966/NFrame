#------------------------------------------------------------------------------#
# This makefile was generated by 'cbp2make' tool rev.147                       #
#------------------------------------------------------------------------------#


WORKDIR = `pwd`

CC = gcc
CXX = g++
AR = ar
LD = g++
WINDRES = windres

INC = 
CFLAGS = 
RESINC = 
LIBDIR = 
LIB = 
LDFLAGS = 
SolutionDir = ../../

INC_DEBUG_X64 = $(INC) -I$(SolutionDir) -I$(SolutionDir)/Dependencies/ -I$(SolutionDir)/Dependencies/boost_1_53_0 -I$(SolutionDir)/Dependencies/protobuf-2.5.0/src
CFLAGS_DEBUG_X64 = $(CFLAGS) -std=c++11 -g -fPIC -D_DEBUG
RESINC_DEBUG_X64 = $(RESINC)
RCFLAGS_DEBUG_X64 = $(RCFLAGS)
LIBDIR_DEBUG_X64 = $(LIBDIR)
LIB_DEBUG_X64 = $(LIB)
LDFLAGS_DEBUG_X64 = $(LDFLAGS)
OBJDIR_DEBUG_X64 = .objs
DEP_DEBUG_X64 = 
OUT_DEBUG_X64 = $(SolutionDir)/_Out/Comm/Debug/NFMessageDefine_d.a

INC_RELEASE_X64 = $(INC) -I$(SolutionDir) -I$(SolutionDir)/Dependencies/ -I$(SolutionDir)/Dependencies/boost_1_53_0 -I$(SolutionDir)/Dependencies/protobuf-2.5.0/src
CFLAGS_RELEASE_X64 = $(CFLAGS) -std=c++11 -fPIC -DNDEBUG
RESINC_RELEASE_X64 = $(RESINC)
RCFLAGS_RELEASE_X64 = $(RCFLAGS)
LIBDIR_RELEASE_X64 = $(LIBDIR)
LIB_RELEASE_X64 = $(LIB)
LDFLAGS_RELEASE_X64 = $(LDFLAGS)
OBJDIR_RELEASE_X64 = .objs
DEP_RELEASE_X64 = 
OUT_RELEASE_X64 = $(SolutionDir)/_Out/Comm/Release/NFMessageDefine.a

OBJ_DEBUG_X64 = $(OBJDIR_DEBUG_X64)/NFSLGDefine.pb.o $(OBJDIR_DEBUG_X64)/NFMsgShare.pb.o $(OBJDIR_DEBUG_X64)/NFMsgPreGame.pb.o $(OBJDIR_DEBUG_X64)/NFMsgDefine.o $(OBJDIR_DEBUG_X64)/NFDefine.pb.o $(OBJDIR_DEBUG_X64)/NFMsgBaseEx.pb.o $(OBJDIR_DEBUG_X64)/NFMsgBase.pb.o $(OBJDIR_DEBUG_X64)/NFFleetingDefine.pb.o

OBJ_RELEASE_X64 = $(OBJDIR_RELEASE_X64)/NFSLGDefine.pb.o $(OBJDIR_RELEASE_X64)/NFMsgShare.pb.o $(OBJDIR_RELEASE_X64)/NFMsgPreGame.pb.o $(OBJDIR_RELEASE_X64)/NFMsgDefine.o $(OBJDIR_RELEASE_X64)/NFDefine.pb.o $(OBJDIR_RELEASE_X64)/NFMsgBaseEx.pb.o $(OBJDIR_RELEASE_X64)/NFMsgBase.pb.o $(OBJDIR_RELEASE_X64)/NFFleetingDefine.pb.o

all: debug_x64 release_x64

clean: clean_debug_x64 clean_release_x64

before_debug_x64: 
	test -d $(SolutionDir)/_Out/Comm/Debug || mkdir -p $(SolutionDir)/_Out/Comm/Debug
	test -d $(OBJDIR_DEBUG_X64) || mkdir -p $(OBJDIR_DEBUG_X64)

after_debug_x64: 

debug_x64: before_debug_x64 out_debug_x64 after_debug_x64

out_debug_x64: before_debug_x64 $(OBJ_DEBUG_X64) $(DEP_DEBUG_X64)
	$(AR) rcs $(OUT_DEBUG_X64) $(OBJ_DEBUG_X64)

$(OBJDIR_DEBUG_X64)/NFSLGDefine.pb.o: NFSLGDefine.pb.cc
	$(CC) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFSLGDefine.pb.cc -o $(OBJDIR_DEBUG_X64)/NFSLGDefine.pb.o

$(OBJDIR_DEBUG_X64)/NFMsgShare.pb.o: NFMsgShare.pb.cc
	$(CC) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFMsgShare.pb.cc -o $(OBJDIR_DEBUG_X64)/NFMsgShare.pb.o

$(OBJDIR_DEBUG_X64)/NFMsgPreGame.pb.o: NFMsgPreGame.pb.cc
	$(CC) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFMsgPreGame.pb.cc -o $(OBJDIR_DEBUG_X64)/NFMsgPreGame.pb.o

$(OBJDIR_DEBUG_X64)/NFMsgDefine.o: NFMsgDefine.cpp
	$(CXX) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFMsgDefine.cpp -o $(OBJDIR_DEBUG_X64)/NFMsgDefine.o

$(OBJDIR_DEBUG_X64)/NFDefine.pb.o: NFDefine.pb.cc
	$(CC) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFDefine.pb.cc -o $(OBJDIR_DEBUG_X64)/NFDefine.pb.o

$(OBJDIR_DEBUG_X64)/NFMsgBaseEx.pb.o: NFMsgBaseEx.pb.cc
	$(CC) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFMsgBaseEx.pb.cc -o $(OBJDIR_DEBUG_X64)/NFMsgBaseEx.pb.o

$(OBJDIR_DEBUG_X64)/NFMsgBase.pb.o: NFMsgBase.pb.cc
	$(CC) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFMsgBase.pb.cc -o $(OBJDIR_DEBUG_X64)/NFMsgBase.pb.o

$(OBJDIR_DEBUG_X64)/NFFleetingDefine.pb.o: NFFleetingDefine.pb.cc
	$(CC) $(CFLAGS_DEBUG_X64) $(INC_DEBUG_X64) -c NFFleetingDefine.pb.cc -o $(OBJDIR_DEBUG_X64)/NFFleetingDefine.pb.o

clean_debug_x64: 
	rm -f $(OBJ_DEBUG_X64) $(OUT_DEBUG_X64)
	rm -rf $(SolutionDir)/_Out/Comm/Debug
	rm -rf $(OBJDIR_DEBUG_X64)

before_release_x64: 
	test -d $(SolutionDir)/_Out/Comm/Release || mkdir -p $(SolutionDir)/_Out/Comm/Release
	test -d $(OBJDIR_RELEASE_X64) || mkdir -p $(OBJDIR_RELEASE_X64)

after_release_x64: 

release_x64: before_release_x64 out_release_x64 after_release_x64

out_release_x64: before_release_x64 $(OBJ_RELEASE_X64) $(DEP_RELEASE_X64)
	$(AR) rcs $(OUT_RELEASE_X64) $(OBJ_RELEASE_X64)

$(OBJDIR_RELEASE_X64)/NFSLGDefine.pb.o: NFSLGDefine.pb.cc
	$(CC) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFSLGDefine.pb.cc -o $(OBJDIR_RELEASE_X64)/NFSLGDefine.pb.o

$(OBJDIR_RELEASE_X64)/NFMsgShare.pb.o: NFMsgShare.pb.cc
	$(CC) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFMsgShare.pb.cc -o $(OBJDIR_RELEASE_X64)/NFMsgShare.pb.o

$(OBJDIR_RELEASE_X64)/NFMsgPreGame.pb.o: NFMsgPreGame.pb.cc
	$(CC) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFMsgPreGame.pb.cc -o $(OBJDIR_RELEASE_X64)/NFMsgPreGame.pb.o

$(OBJDIR_RELEASE_X64)/NFMsgDefine.o: NFMsgDefine.cpp
	$(CXX) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFMsgDefine.cpp -o $(OBJDIR_RELEASE_X64)/NFMsgDefine.o

$(OBJDIR_RELEASE_X64)/NFDefine.pb.o: NFDefine.pb.cc
	$(CC) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFDefine.pb.cc -o $(OBJDIR_RELEASE_X64)/NFDefine.pb.o

$(OBJDIR_RELEASE_X64)/NFMsgBaseEx.pb.o: NFMsgBaseEx.pb.cc
	$(CC) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFMsgBaseEx.pb.cc -o $(OBJDIR_RELEASE_X64)/NFMsgBaseEx.pb.o

$(OBJDIR_RELEASE_X64)/NFMsgBase.pb.o: NFMsgBase.pb.cc
	$(CC) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFMsgBase.pb.cc -o $(OBJDIR_RELEASE_X64)/NFMsgBase.pb.o

$(OBJDIR_RELEASE_X64)/NFFleetingDefine.pb.o: NFFleetingDefine.pb.cc
	$(CC) $(CFLAGS_RELEASE_X64) $(INC_RELEASE_X64) -c NFFleetingDefine.pb.cc -o $(OBJDIR_RELEASE_X64)/NFFleetingDefine.pb.o

clean_release_x64: 
	rm -f $(OBJ_RELEASE_X64) $(OUT_RELEASE_X64)
	rm -rf $(SolutionDir)/_Out/Comm/Release
	rm -rf $(OBJDIR_RELEASE_X64)

.PHONY: before_debug_x64 after_debug_x64 clean_debug_x64 before_release_x64 after_release_x64 clean_release_x64


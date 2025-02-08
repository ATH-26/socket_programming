# Compiler settings
CXX = g++
CXXFLAGS = -std=c++17 -Wall

# Directory settings
EXE_DIR = ./exe
TARGET = program
SOURCE = main.cpp

# Build rules
all: create_dir
	$(CXX) $(CXXFLAGS) $(SOURCE) -o $(EXE_DIR)/$(TARGET)

create_dir:
	mkdir -p $(EXE_DIR)

run: all
	$(EXE_DIR)/$(TARGET)

clean:
	rm -f $(EXE_DIR)/$(TARGET)
	rm -rf $(EXE_DIR)
# Makefile

# Compiler
CXX = g++

# Compiler flags
CXXFLAGS = --std=c++11 -Wall -Werror -pedantic -g

main.exe: main.cpp
	$(CXX) $(CXXFLAGS) $^ -o $@

# Disable built-in Makefile rules
.SUFFIXES:

clean:
	rm -rvf *.exe *.out.txt *.out.ppm *.dSYM *.stackdump

a.out: libab.a libcd.a main.o
	- clang++ main.o libab.a libcd.a
	- clang++ main.o libcd.a libab.a

libab.a: a.o b.o
	ar csr libab.a a.o b.o

libcd.a: c.o d.o
	ar csr libcd.a c.o d.o

main.o: main.cpp
	g++ -c main.cpp
a.o: a.cpp
	g++ -c a.cpp
b.o: b.cpp
	g++ -c b.cpp
c.o: c.cpp
	g++ -c c.cpp
d.o: d.cpp
	g++ -c d.cpp

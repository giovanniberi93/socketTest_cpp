server: server.o
	g++ -o server server.o -lboost_system -lboost_thread -lpthread
server.o: server.cpp
	g++ -c server.cpp
clean:
	rm -f *.o server
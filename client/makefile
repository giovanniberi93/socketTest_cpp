client: client.o
	g++ -o client client.o -lboost_system -lboost_thread -lpthread
client.o: client.cpp
	g++ -c client.cpp
clean:
	rm -f *.o client
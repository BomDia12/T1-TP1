all: name.o codigo.o city.o date.o time.o nota.o duration.o description.o address.o language.o password.o title.o email.o

codigo.o: codigo.cpp codigo.hpp
	g++ -std=c++17 -Wall -c codigo.cpp

city.o: city.cpp city.hpp
	g++ -std=c++17 -Wall -c city.cpp

date.o: date.cpp date.hpp
	g++ -std=c++17 -Wall -c date.cpp

name.o: name.cpp name.hpp
	g++ -std=c++17 -Wall -c name.cpp

time.o: time.cpp time.cpp
	g++ -std=c++17 -Wall -c time.cpp

duration.o: duration.cpp duration.hpp
	g++ -std=c++17 -Wall -c duration.cpp

description.o: description.cpp description.hpp
	g++ -std=c++17 -Wall -c description.cpp

address.o: address.cpp address.hpp
	g++ -std=c++17 -Wall -c address.cpp

password.o: password.cpp password.hpp
	g++ -std=c++17 -Wall -c password.cpp

language.o: language.cpp language.hpp
	g++ -std=c++17 -Wall -c language.cpp

nota.o: nota.cpp nota.hpp
	g++ -std=c++17 -Wall -c nota.cpp

title.o: title.cpp title.hpp
	g++ -std=c++17 -Wall -c title.cpp

email.o: email.cpp email.hpp
	g++ -std=c++17 -Wall -c email.cpp

clean:
	rm -rf *.o *.exe


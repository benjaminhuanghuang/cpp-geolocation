# Geolocation Makefile by Olivia Stone for Code Clinic: C++
CC		= g++
TARGET	= Geolocation
SRC		= GeolocationMain.cpp GeolocationRequest.cpp GeolocationWifiPoints.cpp cJSON.c
LDLIBS	= -L/usr/local/Cellar/curl/7.72.0/include -lcurl -lwlanapi

$(TARGET): $(SRC)
	$(CC) -o $(TARGET) $(SRC) $(LDLIBS)

clean:
	rm -f $(TARGET)
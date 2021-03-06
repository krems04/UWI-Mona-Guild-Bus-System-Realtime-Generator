University of The West Indies Guild Bus System Realtime feed Generator
==================================

Forked from thew University of South Florida Bull Runner Application

Desktop application that retrieves GPS Position Updates from Traccar from the UWI Mona's Guild Bus System operations and produces Trip Updates and Vehicle Positions files in GTFS-realtime format.

Protobuf URL endpoints for the feed: 

* tripUpdatesUrl = `http://localhost:8088/trip-updates`
* vehiclePositionsUrl = `http://localhost:8088/vehicle-positions`

To see a plain text representation, add `?debug` to the end of the URL:

* tripUpdatesUrl = `http://localhost:8088/trip-updates?debug`
* vehiclePositionsUrl = `http://localhost:8088/vehicle-positions?debug`

To run: 

`java -jar cutr-gtfs-realtime-bullrunner-0.9.0-SNAPSHOT.jar  --tripUpdatesUrl=http://localhost:8080/trip-updates   --vehiclePositionsUrl=http://localhost:8080/vehicle-positions`

...from TARGET directory

The original Bull Runner GTFS can be found [here](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator/blob/master/bullrunner-gtfs.zip) and should be extracted into `../myGTFS/`, as the GTFS-rt feed requires it to run.

# UWI-Mona-Guild-Bus-System-Realtime-Generator

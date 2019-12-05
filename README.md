# FACE-ADS-B-Demo
Demo using the FACE BALSA Data model to visualize live ADS-B Data
This will be a demo to do real time visualization of ADS-B live aircraft location data
it will do the following via four separate programs to start
1. REST api call to get live ADS-B Data for specific geo-location
2. FACE TSS DDS publisher of the results of #1
3. FACE TSS DDS Subscriber to receive the ADS-B Live data with geo-location coding
4. Mapping visualizer to show real-time aircraft data for given location used by #1

Initial commit will baseline the above functionality but there are many changes to planned to turn this from a nice demo into a usuable functional program example.


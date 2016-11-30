# Car-Location-Monitoring-System
##Service Start Sequence
1. docker-compose up
2. sh ./start-fleet-location-service.sh
3. go to fleet location service folder and run sh ./upload-fleet.sh
4. sh ./start-service-location-service.sh
5. go to service location service folder and run sh ./upload-serviceLocations.sh
6. sh ./start-eureka.sh
7. sh ./start-hystrix.sh
8. sh ./start-location-simulator.sh
9. sh ./start-location-ingest.sh
10. sh ./start-location-updater.sh
11. sh ./start-dashboard.sh

##UI
1. Open Dashboard UI on http://localhost:8080
2. Open Simulator UI on http://localhost:9005
3. Click run simulation

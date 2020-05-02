# go-loggy
A simple client/ server application for central system stats and log monitoring.

(*Note this is primarily an exercise to learn golang*)

The application will consist of a binary and a config file.  The binary can run in server or client mode.  The client will collect system stats (*log collection to come later*) and send them to the listening server.  The server will then parse and present the stats.


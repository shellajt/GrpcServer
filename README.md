# GrpcServer
Based off of the [Google Tutrial](http://www.grpc.io/docs/quickstart/java.html).

To build the project execute ./gradle build from the projects root directory. Follow this with a ./gradle installDist command.

To run the client, ./build/install/examples/bin/adder-server is then used. The server will start locally on port 50051 and wait for requests from client(s).
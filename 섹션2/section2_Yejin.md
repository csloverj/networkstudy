# Session2 - OSI Model

### OSI Model (Open Systems Interconnection model)

Agnostic applications
- without a standard model, your application must have knowledge of the underlying network medium
- Imagine if you have to author different version of your apps so that it works on wifi vs ethernet vs LTE vs fiber

Network Equipment Management
- without a standard model, upgrading network equipments becomes difficult

Decoupled Innovation
- Innovations can be done in each layer separately without affecting the rest of the models.


### 7Layers each describe a specific networking component
- Layer 7 - Application layer : HTTP/FTP/gRPC
- Layer 6 - Presentation layer : Encoding, Serialization
- Layer 5 - Session layer : Connection establishment, TLS
- Layer 4 - Transport layer : UDP/TCP
- layer 3 - Network layer : IP (전송개념 X)
- Layyer 2 - Data Link layer : Frames, Mac address Ethernet
- Layer 1 - Physical layer : Electric signals, fiber or radio waves


### The shortcomings of the OSI Model
- OSI Model has too many layers which can be hard to comprehend
- Hard to argue about which layer does what
- Simpler to deal with Layers 5-6-7 as just one layer, application
- TCP/IP Model does just that


### TCP/IP Model
- Much simpler than OSI jsut 4 layers
- Application (Layer 5,6,7)
- Transport (Layer 4)
- Internet (Layer 3)
- Data Link (Layer 2)
- Physical layer is not officially covered in the model



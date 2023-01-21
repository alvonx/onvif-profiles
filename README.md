# onvif-profile

## Profile A
- **Explanation**
  - Products utilised in electronic access control systems fall under Profile A. A device that complies with a profile can retrieve data, track events, and set up entities like schedules, credentials, and access rules. A profile A client that complies with the requirements can offer configurations for schedules, credentials, and access rules. The client can also retrieve and receive events that are linked to standardised access control.
- **Features**
  - Granting/revoking credentials
  - Creating schedules
  - Assigning access rules
---
## Profile C
- **Explanation**
  - Products utilised in electronic access control systems fall under profile C. Devices and clients that comply with Profile C support event and alarm management, door access control, and site information.
- **Features**
  - Site information and configuration
  - Event and alarm management
  - Door access control
---
## Profile D
- **Explanation**
  - For peripheral input devices like token readers (for cards, keys, mobile phones, or bar codes), biometric readers (for fingerprint recognition), cameras (for iris, facial, or licence plate recognition), keypads, sensors (for lock status, door status, temperature, or motion), and output devices like locks, displays, and LEDs, the Profile D specifies the interfaces.
   - An access control device or management software, for example, that is securely placed will receive input credential IDs from a Profile D peripheral device and transmit them to it. The client, which keeps track of access rules, schedules, and credentials, can then decide whether to permit or refuse access, display a message, or ask for more information, like a PIN number, before sending a command back to the peripheral device.
- **Features**
  - Transfers input credential identifiers and requests for access
  - Performs actions such as locking/unlocking
---
## Profile G
- **Explanation**
  - IP-based video systems are the intended use for Profile G. A Profile G device can either capture video data over an IP network or on the device itself (for example, an IP network camera or video encoder). A Profile G client is a device that can configure, ask for, and manage video data recording over an IP network from a Profile G conformant device. Examples of such clients include video management software. If the client supports those features, Profile G additionally contains capability for receiving audio and metadata streams.
- **Features**
  - Configure, request and control recording
  - Receive audio and metadata stream
---
## Profile M
- **Explanation**
  - Metadata filtering and streaming are supported together with analytics configuration and information query for metadata in ONVIF Profile M. It includes APIs for classifying objects generally as well as specific metadata for geolocation, cars, licence plates, people, and human faces and bodies. Profile M interfaces for features such media profile management, video streaming, adding images to metadata streams, event handling, or rule configuration must be offered if conformant products have native support for those features. Additionally, there ought to be Profile M event handling interfaces for analytics for object counting (such as counting people or automobiles), licence plate recognition, facial recognition, or the MQTT (Message Queuing Telemetry Transport) protocol used by Internet of Things devices.
- **Features**
  - Analytics configuration and information query for metadata
  - Configuration and streaming of metadata
  - Generic object classification support
  - Metadata definition for geolocation, vehicle, license plate, human face and body
  - Event interfaces for object counter, face and license plate recognition analytics
  - Sending events through metadata stream, ONVIF event service or over MQTT
  - Rule configuration for events
---
## Profile S
- **Explanation**
  - IP-based video systems are the target audience for Profile S. A Profile S device is one that can transmit video data over an IP network to a Profile S client, such as an IP network camera or video encoder. A Profile S client is a software programme that allows a Profile S device to configure, request, and control video streaming via an IP network. OnVIF specifications for relay outputs, audio in, multicasting, and PTZ control are also covered in Profile S for compliant devices and clients that enable them.
- **Features**
  - Video streaming and configuration 
---
## Profile T
- **Explanation**
  - IP-based video systems are the intended use for Profile T. The use of H.264 and H.265 encoding codecs, imaging options, and alarm events like motion and tamper detection are all supported by Profile T. Onscreen display and metadata streaming are additional required features for devices, while PTZ control is a required feature for clients. For conformant devices and clients that enable such capabilities, Profile T additionally covers the ONVIF requirements for HTTPS streaming, PTZ configuration, motion region configuration, digital inputs and relay outputs, and bidirectional audio.
- **Features**
  - H.264 / H.265 video compression
  - Imaging settings
  - Motion alarm and tampering events
  - Metadata streaming
  - Bi-directional audio

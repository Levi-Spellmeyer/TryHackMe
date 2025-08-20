
<h1>OSI 7-layer model </h1>
Stands for the Open Sytems Interconnection protocol. Specific processes take place at each layer and pieces of information are added to data as you move down the layers from top to bottom. This process is named encapsulation. The OSI model represents how devices connected on a network send and receive information.

---

<h3>Layer 1: Physical</h3>
^ This layer contains the physical networking devices you will find that send electrical signals (0's and 1's) between devices 

---

<h3>Layer 2: Data Link</h3>
^ Focuses on the physical addressing of the data transmission. Anything MAC address related is more than likely something belonging to layer 2. MAC addresses are burned into network interface cards by the manufacturer and are unique to each device.

---

<h3>Layer 3: Network</h3>
^ Where networking functionality comes into play and data is reassembled. Routing is the determination of the best path a transmission should take to reach its destination. Metrics include most reliable route, fastest route, and/or shortest path.

---

<h3>Layer 4: Transport</h3>
^ Data is sent using TCP or UDP (notes on this can be found in Packets and Frames markdown file). This layer manages flow control and the segmentation of larger data into smaller pieces.

---

<h3>Layer 5: Session</h3>
^ Creates connections and maintains sessions. Sessions are unique and data can only flow over its respectful connection and not over/during other sessions. Session is the technical term for when a connection is established.

---

<h3>Layer 6: Presentation</h3>
^ Layer where standardization starts to apply. Acts as a translator between the application layer and data being received. Secure protocols like HTTPS occur at this layer.

---

<h3>Layer 7: Application</h3>
^ Displays data and information in helpful GUIs so user can interact with applications.

---

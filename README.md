# OSI-Based Network Troubleshooting

This repository demonstrates how the OSI model is used as a structured troubleshooting framework in large, distributed education networks. The focus is on isolating issues quickly, minimizing downtime, and communicating clearly with both technical and non-technical stakeholders.

---

## Scenario 1: Classroom Devices Connected but No Access

**Problem**  
Devices appear connected to the network but cannot access instructional resources.

**OSI Layers Involved**  
- Layer 2 (Data Link)  
- Layer 3 (Network)

**Technical Diagnosis**  
Devices were assigned to an incorrect VLAN, preventing routed access to required systems.

**Resolution**  
Corrected VLAN assignment and verified gateway reachability.

**Non-Technical Explanation**  
Devices were connected, but placed in the wrong group.

---

## Scenario 2: School-Wide Connectivity Loss

**OSI Layers Involved**  
- Layer 1 (Physical)  
- Layer 3 (Network)

**Diagnosis**  
A failed uplink disrupted routing to the site.

**Resolution**  
Restored physical connectivity and validated routing convergence.

**Non-Technical Explanation:**  
A primary connection that carries network traffic to the school was interrupted. This is similar to a major road being closed, preventing traffic from reaching its destination. Once the connection was restored, normal access resumed.

---

## Scenario 3: Internet Works, Internal Systems Fail

**OSI Layer Involved**  
- Layer 7 (Application)

**Diagnosis**  
DNS resolution for internal systems was unavailable.

**Resolution**  
Restored DNS services.

**Non-Technical Explanation:**  
The network itself was functioning, but the system that helps computers locate internal services was unavailable. As a result, users could not access internal systems by name, even though the connection was still active.

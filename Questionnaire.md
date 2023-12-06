## **Shared Access and Medium Network Architecure**

# **Laboratory Session 1: Spanning Tree Simulator**

_Academic year 2023-2024_  
_Telematics Engineering Department - Universidad Carlos III de Madrid_

---

## Question 1
Using the topology where all links have the same cost, and after the STP converges, this is the state of the following ports:

|  |  |
| --- | --- |
| Bridge 0, port 0 | `Active` ($\checkmark$) |
| Bridge 0, port 1 | `Active` ($\checkmark$) |
| Bridge 1, port 0 | `Active` ($\checkmark$) |
| Bridge 3, port 0 | `Active` ($\checkmark$) |
| Bridge 3, port 1 | `Blocked` ($\checkmark$) |
| Bridge 3, port 2 | `Blocked` ($\checkmark$) |
| Bridge 4, port 0 | `Active` ($\checkmark$) |
| Bridge 4, port 1 | `Blocked` ($\checkmark$) |
| Bridge 4, port 2 | `Active` ($\checkmark$) |
| Bridge 4, port 3 | `Active` ($\checkmark$) |
| Bridge 6, port 0 | `Blocked` ($\times$- Active) |
| Bridge 6, port 1 | `Active` ($\times$- Blocked) |
| Bridge 6, port 2 | `Blocked` ($\checkmark$) |
| Bridge 6, port 3 | `Active` ($\checkmark$) |
| Bridge 7, port 0 | `Blocked` ($\checkmark$) |
| Bridge 7, port 1 | `Blocked` ($\checkmark$) |
| Bridge 7, port 2 | `Blocked` ($\checkmark$) |
| Bridge 7, port 3 | `Active` ($\checkmark$) |

## Question 2
With the topology where the bottom link has a cost of 1000, and after the Spanning Tree Protocol has converged, this is the state of the following ports:

|  |  |
| --- | --- |
| Bridge 7, port 3 | Blocked ($\checkmark$) |
| Bridge 4, port 1 | Blocked ($\checkmark$) |
| Bridge 3, port 1 | Blocked ($\checkmark$) |
| Bridge 2, port 0 | Active ($\checkmark$) |
| Bridge 7, port 0 | Blocked ($\checkmark$) |
| Bridge 3, port 0  | Blocked ($\times$- Active) |
| Bridge 2, port 3 | Active ($\checkmark$) |
| Bridge 7, port 2 | Active ($\checkmark$) |
| Bridge 3, port 3 | Active ($\checkmark$) |
| Bridge 7, port 1 | Blocked ($\checkmark$) |
| Bridge 4, port 0 | Active ($\checkmark$) |
| Bridge 3, port 2 | Blocked ($\checkmark$) |

## Question 3
With respect to the optimal path followed by a packet, answer the following questions.

The first packets sent by host00 to host01 is received by...
> All bridges

($\checkmark$)

The reply from host01 to host00 is received by...
> Bridge 00 only

($\times$- Bridges 00 and 01)

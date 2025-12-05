# **Problem Situation 2 – WATERWORKS!**

**Analysis and Design of Advanced Algorithms**
*Translation of Dra. Valentina Navárez Terán’s presentation*

---

# **Water Distribution Networks**

Water distribution is a complex and challenging problem. Since the water infrastructure forms a network of nodes, the tools of graph theory and related algorithms can help optimize how water flows across the system.

---

## **1. Instances**

A water distribution network consists of:

* **Nodes**: Represent infrastructure points.

  * **Sources**
  * **Non-source nodes**

* **Pipes (edges)**: Each pipe has an associated **weight**, representing its **capacity**.

---

## **2. Pipe Lengths**

Using the **x, y coordinates** of each node, calculate the length of each pipe.

You must create graphs showing:

* The **diameter** of each pipe
* The **length** of each pipe

---

## **3. Sectorization**

Sectorization means dividing the network into sectors, each associated with a source.

* Every node must be supplied by the **nearest source** in the network.
* Sectors are separated by **closing certain pipes**.
* You must determine which pipes must be closed.

Your report must include:

* Which nodes belong to each sector
* Which pipes were closed
* A **visual representation** (color-coded or any style you choose) marking the closed pipes

---

## **4. Water Freshness**

A quality metric is the **time** water takes to travel from a source to a node, which is proportional to **distance**.

You must answer:

* **Which node receives water the slowest in each sector?**

---

## **5. Maximum Flow Rate for Each Sector**

Using pipe capacities, determine the **maximum flow rate** within each sector.

For each sector define:

* **Origin**: the source
* **Destination**: the **farthest node** from that source

---

## **6. Water Quality Sampling**

To evaluate water quality, samples must be collected from **every node**.

Compute a **minimum-distance route** for a person starting at the node labeled **“office”**, visiting all nodes, and returning to the starting point.

Assumptions:

* All sampling can be completed in a single day
* Street layouts correspond to pipe layouts

---

## **7. Network Expansion**

Given a new node at specific coordinates:

1. Connect the new node to the **nearest non-source node**.
2. Update the existing network accordingly.

Rules:

* Only Problem 6 may require full recomputation
* All other structures must be updated **locally** without rebuilding the entire network

---

## **Test Files**

Test data will be provided in Canvas.

---

# **Waterworks! (Reference)**

The final slide references *Waterworks!*, a water-distribution game that uses small node counts but benefits from understanding both graph theory and geometry. Although brute-force solutions may work for small systems, real systems—even in games—require careful optimization to prevent lag and ensure a good user experience.

---

If you'd like, I can also:

✅ Convert this into a LaTeX document
✅ Create a formatted PDF
✅ Turn it into a project specification sheet
✅ Summarize it or generate diagrams for each task

Just tell me what you prefer, Santi.

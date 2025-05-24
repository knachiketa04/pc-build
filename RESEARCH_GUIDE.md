# 📝 PC Build Research Guide

> This guide outlines a systematic approach to researching components for your PC build. Following this order can help ensure compatibility and make informed decisions.

---

## 🛠️ Phase 1: Core Decisions & Foundation

This phase focuses on the central components that will dictate many of your subsequent choices.

### 🎯 1. Define Your Needs & Budget (Refer to `README.md` - Build Overview & Budget)
   - **Action:** Solidify your primary use case (gaming, workstation, streaming, etc.).
   - **Action:** Define clear performance goals (target resolution, frame rates, specific software demands).
   - **Action:** Establish a realistic overall budget and preliminary allocations for key components. This will evolve, but a starting point is crucial.
   - **Research:**
     - General PC build guides for your use case (e.g., "best gaming PC build guide 2025").
     - Articles/videos on budget allocation for PC builds.

### ⚡ 2. Central Processing Unit (CPU)
   - **Why first (or second alongside Motherboard):** The CPU choice heavily influences motherboard compatibility (socket type) and overall system performance.
   - **Research:**
     - **Socket Types:** Understand current CPU socket types (e.g., AM5 for AMD, LGA1700/1851 for Intel).
     - **Cores/Threads:** How many do you need for your tasks? (Gaming often prioritizes single-core speed, while productivity benefits from more cores/threads).
     - **Clock Speeds:** Base vs. Boost clocks.
     - **Integrated Graphics (iGPU):** Do you need one? (Useful for troubleshooting or if you're not getting a dedicated GPU immediately).
     - **TDP (Thermal Design Power):** Impacts cooler choice.
     - **Reviews & Benchmarks:** Look for performance in your specific use cases (e.g., "CPU X gaming benchmarks," "CPU Y video editing performance"). Compare against alternatives.
     - **Generational Differences:** Understand improvements in the latest CPU generations.
   - **Considerations:**
     - Balance between price and performance.
     - Future-proofing (though this can be a trap, consider a reasonable lifespan).
     - Compatibility with your intended motherboard chipset.

### 🔌 3. Motherboard
   - **Why second (or first alongside CPU):** Must be compatible with your chosen CPU (socket and chipset). It's the backbone connecting all components.
   - **Research:**
     - **Chipset:** Determines features (PCIe lanes, USB ports, overclocking support). Research chipsets compatible with your chosen CPU (e.g., B650, Z790).
     - **Form Factor:** ATX, Micro-ATX, Mini-ITX. This must fit your chosen case and dictates expansion options.
     - **RAM Compatibility:** Supported DDR generation (DDR4/DDR5), max speed, and capacity.
     - **Expansion Slots:** Number and type of PCIe slots (for GPU, expansion cards).
     - **Storage Options:** Number of M.2 slots, SATA ports. Consider NVMe Gen 4/5 support.
     - **I/O Panel:** USB port types and quantity, audio jacks, networking (Ethernet speed, Wi-Fi).
     - **VRM (Voltage Regulator Module):** Quality impacts CPU power delivery and overclocking stability.
     - **BIOS/UEFI:** User-friendliness, features.
     - **Reviews:** Look for reliability, ease of use, and feature set.
   - **Considerations:**
     - Don't overspend if you don't need premium features (e.g., extreme overclocking, excessive M.2 slots).
     - Ensure it has all the connectivity you need now and in the near future.

---

## 🚀 Phase 2: Performance & Core Components

With the CPU and Motherboard selected, you can now choose components that directly impact performance and are dependent on the foundation you've laid.

### 🧠 4. Memory (RAM)
   - **Why now:** RAM compatibility (DDR4/DDR5, speed) is determined by the motherboard and CPU.
   - **Research:**
     - **Type:** DDR4 vs. DDR5 (as supported by your motherboard/CPU).
     - **Capacity:** How much RAM do you need? (16GB is a good starting point for many, 32GB for more demanding tasks/gaming, 64GB+ for workstations).
     - **Speed (MHz/MT/s):** Higher speed can offer performance benefits, especially with certain CPUs (e.g., AMD Ryzen). Check motherboard QVL (Qualified Vendor List) for tested speeds.
     - **Timings (CL - CAS Latency):** Lower is generally better, but balance with speed and price.
     - **Kits:** Buy RAM in kits (e.g., 2x8GB, 2x16GB) for guaranteed compatibility and dual-channel performance.
     - **Reviews:** Check for reliability and real-world performance differences.
   - **Considerations:**
     - Motherboard QVL for best compatibility.
     - Balance between speed, capacity, and price.
     - Aesthetics (RGB, heat spreader design) if important.

### 🎮 5. Graphics Card (GPU)
   - **Why now:** This is often the most expensive component and the primary driver for gaming performance. Your CPU choice should complement your GPU to avoid bottlenecks.
   - **Research:**
     - **Performance Tier:** Based on your gaming/workload targets (e.g., 1080p, 1440p, 4K gaming; specific software acceleration).
     - **VRAM:** Amount of video memory (e.g., 8GB, 12GB, 16GB+). More is needed for higher resolutions and textures.
     - **Benchmarks:** Extensive research here is key. Compare different cards in the games/applications you use. Look at average FPS, 1% lows.
     - **Brands & Models:** Different AIB (Add-In Board) partners (e.g., ASUS, Gigabyte, MSI, EVGA (formerly), Sapphire, XFX) offer various cooler designs, factory overclocks, and aesthetics.
     - **Power Consumption (TDP):** Important for PSU selection.
     - **Dimensions:** Length, height, width – ensure it fits your case.
     - **Outputs:** DisplayPort, HDMI – ensure they match your monitor(s).
     - **Ray Tracing/DLSS/FSR:** If these features are important, research GPU support and performance.
   - **Considerations:**
     - CPU Bottleneck: Ensure your CPU is capable enough not to significantly limit your chosen GPU.
     - Monitor Compatibility: Match GPU capabilities with your monitor's resolution and refresh rate.
     - Price-to-Performance: This is critical. Look at $/FPS metrics.
     - Availability and current market pricing.

### 💾 6. Storage (SSD/HDD)
   - **Why now:** You know your motherboard's M.2 and SATA capabilities.
   - **Research:**
     - **Types:**
       - **NVMe SSD (PCIe Gen3/4/5):** Fastest option, ideal for OS, applications, and frequently played games. Check motherboard for M.2 slot compatibility (PCIe generation, key type).
       - **SATA SSD:** Slower than NVMe but faster than HDDs. Good for additional game storage or less critical applications.
       - **HDD (Hard Disk Drive):** Slowest but offers high capacity for cheap. Best for mass storage (media files, archives).
     - **Capacity:** How much storage do you need for OS, programs, games, and files?
     - **Read/Write Speeds:** Especially important for NVMe drives.
     - **Endurance (TBW - Terabytes Written):** Indicates lifespan for SSDs.
     - **DRAM Cache:** SSDs with DRAM cache generally perform better, especially under sustained loads.
     - **Reviews:** Look for reliability, real-world performance, and any known issues.
   - **Considerations:**
     - At least one NVMe SSD for the boot drive is highly recommended.
     - Balance between speed, capacity, and cost.
     - Number of M.2 slots and SATA ports on your motherboard.

---

## 🏠 Phase 3: Housing & Powering

These components ensure everything is housed correctly, cooled effectively, and powered reliably.

### 🏠 7. Case
   - **Why now:** You know the form factor of your motherboard and the size of your GPU.
   - **Research:**
     - **Motherboard Form Factor Compatibility:** ATX, mATX, Mini-ITX.
     - **GPU Clearance:** Maximum GPU length supported.
     - **CPU Cooler Clearance:** Maximum CPU cooler height supported (for air coolers) or radiator compatibility (for AIOs).
     - **Airflow:** Look for cases with good ventilation (mesh front panels, fan mounts). Read/watch reviews focusing on thermal performance.
     - **Drive Bays:** Number of 2.5" and 3.5" bays for your storage devices.
     - **Cable Management:** Features like routing holes, tie-down points, and PSU shroud.
     - **Aesthetics & Build Quality:** Subjective, but consider materials, window, and overall look.
     - **Front Panel I/O:** USB ports, audio jacks.
   - **Considerations:**
     - Ease of building in.
     - Noise levels (some cases are designed for silence).
     - Future expansion needs.

### ⚡ 8. Power Supply Unit (PSU)
   - **Why now:** You have a good estimate of the total power consumption of your CPU, GPU, and other components.
   - **Research:**
     - **Wattage:** Calculate the total estimated power draw of your system (many online calculators exist) and add a healthy headroom (e.g., 20-30%, or aim for your peak load to be 50-70% of PSU capacity for optimal efficiency).
     - **Efficiency Rating:** 80+ (Bronze, Silver, Gold, Platinum, Titanium). Higher efficiency means less wasted energy (heat) and potentially lower electricity bills. 80+ Gold is often a good sweet spot.
     - **Modularity:**
       - **Full-Modular:** All cables are detachable. Best for cable management.
       - **Semi-Modular:** Essential cables (motherboard, CPU) are attached, others are detachable.
       - **Non-Modular:** All cables are attached. Hardest for cable management.
     - **Connectors:** Ensure it has all the necessary connectors for your motherboard, CPU (EPS), GPU (PCIe), and storage. Pay attention to new GPU power connectors if applicable (e.g., 12VHPWR).
     - **Tier Lists:** Consult reputable PSU tier lists (e.g., Cultists Network PSU Tier List) for quality and reliability assessments. This is very important for system stability and safety.
     - **Warranty:** Longer warranty often indicates manufacturer confidence.
     - **Form Factor:** ATX is standard, SFX for small form factor builds.
   - **Considerations:**
     - **Never skimp on the PSU.** A bad PSU can damage your entire system.
     - Check reviews for noise levels (fan quality).

### ❄️ 9. CPU Cooler
   - **Why now:** You know your CPU's TDP, your case's cooler clearance, and RAM height (for air cooler compatibility).
   - **Research:**
     - **Types:**
       - **Air Coolers:** Tower coolers with heatsinks and fans. Simpler, often more reliable, can be very effective.
       - **AIO (All-In-One) Liquid Coolers:** Closed-loop liquid cooling with a radiator, pump, and fans. Can offer better cooling for high TDP CPUs or a cleaner look.
     - **TDP Rating:** Ensure the cooler's TDP rating meets or exceeds your CPU's TDP.
     - **Socket Compatibility:** Must match your CPU socket.
     - **Clearance (Air Coolers):** Height must fit within your case. Check RAM clearance as well.
     - **Radiator Size & Compatibility (AIOs):** 120mm, 240mm, 280mm, 360mm. Ensure your case supports the chosen radiator size and mounting location.
     - **Noise Levels:** Check reviews for fan noise at different RPMs.
     - **Reviews & Benchmarks:** Compare cooling performance and noise.
   - **Considerations:**
     - Stock coolers (if your CPU includes one) are often only adequate for basic use, not for heavy loads or overclocking.
     - Aesthetics.
     - Ease of installation.

---

## 🖱️ Phase 4: Peripherals & Final Touches (Research as needed, can be done earlier or later)

### 💨 10. Case Fans (if not included or upgrading)
   - **Research:**
     - **Size:** (e.g., 120mm, 140mm) - match case fan mounts.
     - **Airflow vs. Static Pressure:** Airflow fans are good for general case ventilation. Static pressure fans are better for pushing air through obstacles like heatsinks and radiators.
     - **PWM:** Allows for fan speed control via motherboard.
     - **Noise Levels (dBA).**
     - **Bearings:** Fluid dynamic, magnetic levitation, sleeve, ball – affect lifespan and noise.
   - **Considerations:**
     - Positive vs. Negative pressure setup for optimal airflow and dust management.

### ⌨️ 11. Monitors, Keyboard, Mouse, etc.
   - While not part of the PC itself, your monitor choice, in particular, should align with your GPU's capabilities (resolution, refresh rate, adaptive sync like G-Sync/FreeSync). Research these based on your needs and budget.

---

## 💡 General Research Tips:

*   **Use PCPartPicker.com:** This website is invaluable for checking compatibility, planning your build, and comparing prices.
*   **Read/Watch Multiple Reviews:** Don't rely on a single source. Look for reviews from reputable tech sites, YouTubers, and user reviews.
*   **Check Forums:** Communities like Reddit (e.g., r/buildapc, r/pcmasterrace) can provide insights, answer specific questions, and showcase builds.
*   **Understand Return Policies:** Especially for online purchases.
*   **Keep Track of Your Research:** Use your `README.md` or a spreadsheet to note down chosen components, alternatives, prices, and links to reviews.
*   **Don't Rush:** Take your time. This is a significant investment.

---

## ✅ Final Step: Compatibility Check (Refer to `README.md` - Compatibility Matrix)

Before purchasing anything:
1.  **Double-check all component compatibilities** using PCPartPicker and manufacturer specifications.
    *   CPU <-> Motherboard (Socket, Chipset)
    *   RAM <-> Motherboard (Type, Speed, QVL)
    *   GPU <-> Case (Length, Width)
    *   GPU <-> PSU (Power connectors, Wattage)
    *   CPU Cooler <-> Case (Height/Radiator support)
    *   CPU Cooler <-> Motherboard (Socket, RAM clearance)
    *   M.2 SSD <-> Motherboard (Key, PCIe generation)
    *   PSU <-> Case (Form factor)

This research guide should provide a solid framework for your PC building journey. Good luck!

---

<div align="center">

### 🌟 Happy Researching!

This guide is part of the [PC Building Project](README.md).

</div>

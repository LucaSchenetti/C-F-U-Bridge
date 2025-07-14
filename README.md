🎉 C‑F‑U Bridge: Open Source Dev Board for Fiber & Copper → USB 3.1 🎉

In the world of IoT, industrial systems, and high-performance networking—where fiber is becoming the new standard—we needed a compact and flexible tool to work with both optical and copper signals.

Introducing C‑F‑U Bridge, an open source development board I designed for prototyping, testing, and debugging:

🔌 Fiber Input
• SFP slot (INF‑8074i standard)
• Compatible with modules from 1 Gbit/s up to 4.25 Gbit/s (SFP+ supported for higher speeds)

⚡ USB 3.1 Gen1 Output
• Direct optical/copper to USB connection – no intermediate switch
• Up to 5 Gbit/s in Gen1 mode

🔄 Selectable Conversion Modes (via DIP switch)
• Optical → USB
• Copper → USB
• Optical → Copper

🧠 STM32 MCU with integrated I²C
• Dynamic register configuration via I²C
• No external EEPROM required

🌐 LAN7801 Controller (Microchip)
• High-performance USB 3.1 ↔ Gigabit Ethernet bridge
• Supports full-duplex, auto-negotiation, Wake-on-LAN, and advanced power saving
• Compact QFN‑64 package, ideal for embedded and industrial use

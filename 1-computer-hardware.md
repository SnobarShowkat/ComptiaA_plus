    Computer Hardware:

    Computer hardware refers to the physical components of a computer system that can be seen and touched. These components work together to receive input, proecess data, store information, and produce output according to user instructions.

        Input Devices: These devices are used to enter data and commands into a computer. They convert the entered information into a format that the computer can process. Example are Keyboard, Mouse and Scanner.

        Output Devices: These devices present processed data in a user-friendly form. They convert digital information into visual, audio, or physical results that users can easily understand. Examples are Monitor, Printer, Plotter, and Speakers.

        Memory: Designed to stores data and instructions needed by the computer. Primary memory includes RAM and ROM, while secondary storage devices store data for long-term use. Examples of secondary storage include CDs, DVDs, hard disks, SSDs, and USB drives.

        CPU (Central Processing Unit) : The brain of a computer that executes instructions and processes data. It performs arithmetic and logical operations and controls the activities of other computer components.

        Other Components: There are more physical parts inside a computer that work together to process data and perform different functions. Examples are, Motherboard, VGA Port, Graphics Card (GPU), Power Supply Unit (PSU) and Cooling Fan.

        The functions of CPU involve processing instructions from programs and controlling all operations within the computer. This is carried out through a sequence known as the Fetch-Decode-Execute-Store cycle:
        The cycle happens billions of times a second, letting the CPU handle tons of tasks super fast!
        Fetch: The CPU retrieves the instruction from main memory (RAM).
        Decode: The Control Unit interprets the fetched instruction to determine the required operation.
        Execute: The CPU performs the operation using the appropriate hardware components such as the ALU.
        Store: The result of the executed instruction is written back to memory or a register.

        Types of CPUs:

        CPUs come in different configurations based on the number of cores they contain. A core acts like a mini processor inside the CPU, allowing it to handle multiple tasks efficiently. These variations are commonly referred to as the types of CPU.

        Single-Core CPU: The oldest type, used in the 1970s. It can only handle one task at a time, so it’s slow for modern apps like games or web browsers.
        Dual-Core CPU: Has two cores, so it can handle two tasks at once. It’s faster and better for multitasking, like listening to music while doing homework.
        Quad-Core CPU: Has four cores, making it great for heavy tasks like video editing or playing modern games. It’s very fast and common in today’s computers.

        Core vs Thread:

        • Physical Core: An actual hardware processing unit inside the CPU chip that performs calculations.
        • CPU Thread (Logical Core): A virtual representation of a core that allows a single physical core to manage multiple instruction streams at the same time. A single CPU core can have up-to 2 threads per core. For example, if a CPU is dual core (i.e., 2 cores) it will have 4 threads. And if a CPU is Octal core (i.e., 8 core) it will have 16 threads and vice-versa.
    
    CPU Architetures:

    x86_64 and ARM64 are the two dominant 64-bit CPU architectures used in modern computing, differing fundamentally in design philosophy, instruction sets, and power usage.


        Key Architectural Breakdown

        • Instruction Sets (CISC vs. RISC):
            • x86_64 uses CISC, where hardware executes complex, multi-step instructions directly. This gives the processor immense single-threaded muscle for heavy workloads, though it demands more power and cooling.
            • ARM64 uses RISC, relying on a smaller set of simple, fast instructions. It pushes complexity onto the software compiler, allowing the chip to complete tasks with far fewer transistors and much less heat.
        • Power Efficiency vs. Peak Speed:
            • x86_64 (built by Intel and AMD) historically rules heavy desktop gaming and high-load servers, though it draws more wattage and requires active cooling (fans).
            • ARM64 (licensed by Arm Holdings and used by companies like Apple, Qualcomm, and Amazon) dominates mobile devices and is rapidly proving itself in laptops and data 
            centers by delivering high sustained performance without burning through battery.

        A CPU socket is a physical connector on the motherboard where the Central Processing Unit (CPU) is installed.

        It connects the processor to the motherboard and allows communication between the CPU and other computer components.

        Main functions of a CPU socket:
        1. Holds the processor securely on the motherboard.
        2. Provides electrical connections between the CPU and motherboard.
        3. Allows communication between the processor, RAM and other components.
        4. Makes it possible to replace or upgrade compatible processors.

    2. Types of CPU Sockets
    There are three major CPU socket types:

    A. PGA (Pin Grid Array)
    PGA stands for Pin Grid Array.
    - The pins are located on the CPU.
    - The motherboard socket contains small holes.
    - The CPU pins fit into these holes.
    - Care is required because CPU pins can bend easily.
    Example: AMD AM4 socket processors.

    B. LGA (Land Grid Array)
    LGA stands for Land Grid Array.
    - The pins are located on the motherboard socket.
    - The CPU has flat contact pads.
    - The CPU is placed carefully into the socket.
    - It is widely used in Intel desktop processors.
    Examples:
    - LGA 1151
    - LGA 1200
    - LGA 1700
    C. BGA (Ball Grid Array)
    BGA stands for Ball Grid Array.
    - The processor is permanently soldered to the motherboard.
    - It uses small solder balls to create electrical connections.
    - The CPU cannot normally be removed or upgraded by a user.
    - It is commonly found in laptops and compact devices.
    Example: Many laptop processors and low-power embedded processors.
    3. Difference Between PGA, LGA and BGA
    Feature	            PGA	                 LGA	           BGA
    Full form	        Pin Grid Array	    Land Grid Array	   Ball Grid Array
    Connection	        CPU pins	        Socket pins	       Solder balls
    Pins/contacts	    On CPU	            On motherboard	   Soldered to board
    Replaceable?	    Yes	                Yes	               Usually no
    Common usage	    AMD AM4	            Intel LGA 1700  	Laptops

    4. Examples of CPU Socket Types
    Socket	   Manufacturer	      Processor compatibility
    AM4	         AMD	          Many  Ryzen  CPUs
    AM5	         AMD	          Ryzen 7000 and newer supported generations
    LGA 1700	Intel	          12th, 13th and 14th Gen Core
    LGA 1200	Intel	          10th and 11th Gen Core
    LGA 1151	Intel	          Selected 6th–9th Gen Core CPUs, depending on motherboard

    Important: Not every CPU with the same socket is automatically compatible. The motherboard chipset and BIOS version also matter.

    5. How to Identify a CPU Socket
    You can identify a CPU socket by checking:
    1. The motherboard model number.
    2. The motherboard manufacturer's specifications.
    3. The processor's compatibility information.
    4. The socket type printed in the motherboard manual.


    Remember these facts:
    - PGA = Pins on the CPU.
    - LGA = Pins on the motherboard.
    - BGA = Processor soldered to the motherboard.
    - AM4 = AMD PGA socket.
    - AM5 = AMD LGA socket.
    - LGA 1700 = Intel socket.
    - BGA processors are generally not user-upgradable.
    - Always check CPU and motherboard compatibility.


    LGA 1700 and AM4:

    LGA 1700 and AM4 are two popular, value-oriented desktop platforms that are considered end-of-life (EOL), as both Intel and AMD have moved on to newer architectures (LGA 1851 and AM5).

    Key Differences

    • Platform & Manufacturer:
        • LGA 1700 is Intel's socket for 12th, 13th, and 14th Generation Core processors (such as the Intel Core i5-12400F Processor).
        • AM4 is AMD's long-running socket for Ryzen 1000 through Ryzen 5000 series desktop processors.
    • Pin Design:
        • LGA 1700 uses an LGA (Land Grid Array) design with 1,700 pins located directly on the motherboard socket.
        • AM4 uses a PGA (Pin Grid Array) design with 1,331 pins located underneath the CPU itself.
        Memory Support:
        • LGA 1700 motherboards can support either DDR4 or DDR5 depending on the specific board you purchase.
        • AM4 motherboards strictly support DDR4 memory



    RAM and its types:
    What is RAM?
Random Access Memory, is a type of computer memory that allows data to be read and written randomly, meaning that the computer can access any location in the memory directly rather than having to read the data in a specific order. This makes RAM an essential component of a computer system, as it enables the CPU to access data quickly and efficiently.

RAM is volatile in nature, which means if the power goes off, the stored information is lost. RAM is used to store the data that is currently processed by the CPU. Most of the programs and data that are modifiable are stored in RAM. 

Types of RAM?
Mainly RAM have 2types

SRAM (Static RAM)
DRAM (Dynamic RAM)

What is SRAM?
The SRAM memories consist of circuits capable of retaining the stored information as long as the power is applied. That means this type of memory requires constant power. SRAM memories are used to build Cache Memory.
What is DRAM?
DRAM stores the binary information in the form of electric charges applied to capacitors. The stored information on the capacitors tends to lose over a period of time and thus the capacitors must be periodically recharged to retain their usage. DRAM requires refresh time. The main memory is generally made up of DRAM chips.

DDR4 and DDR5 are generations of Double Data Rate (DDR) SDRAM system memory, with DDR5 serving as the faster, more efficient successor to DDR4.

Key Differences


Feature	                  DDR4	                                       DDR5
Speed / Bandwidth	      2,133 – 3,200 MT/s (up to ~5,000 MT/s OC)	   4,800 – 6,400+ MT/s (up to 8,800+ MT/s OC)
Max Capacity per Module	  Typically up to 32 GB – 64 GB	               Up to 128 GB – 256 GB+
Operating Voltage	      1.2V (regulated by motherboard)	           1.1V (on-module PMIC)
Channel Architecture	  Single 64-bit channel per stick	           Dual 32-bit subchannels per stick
Error Correction (ECC)	  ECC restricted mostly to server/Pro parts	   On-die ECC built into all modules
Initial CAS Latency    	  Lower (CL13 – CL19)	                       Higher raw numbers (CL36 – CL40), offset by speed


Major Performance & Design Shifts

• Speed and Bandwidth: DDR5 doubles the burst length and bank groups of DDR4, delivering significantly higher data throughput and smoother 1% low frames in high-refresh-rate gaming.
• Power Management: DDR4 relies on the motherboard for power regulation, whereas DDR5 moves the Power Management IC (PMIC) directly onto the RAM stick itself for better granularity, though this can make modules run warmer.
• Physical Incompatibility: DDR4 and DDR5 have different pin counts (288 pins each, but the physical key notch is in a different position). You cannot plug DDR4 into a DDR5 slot or vice versa.
• Platform Support:
	• AM4 (AMD) and older Intel platforms support DDR4 only.
	• AM5 (AMD Zen 4/5) and LGA1851 (Intel) support DDR5 only.
	• LGA1700 (Intel 12th–14th Gen) can support either DDR4 or DDR5 depending on your specific motherboard model.

DIMM anad SODIMM:

DIMM and SO-DIMM are the two primary physical form factors for computer memory (RAM), differing mainly in size, pin count, and where they are used.

DIMM (Dual In-line Memory Module)

• What it is: The standard, full-sized memory module designed for desktop computers and enterprise servers.
• Size: Measures approximately 133.35 mm in length.
• Pin Count:
	• DDR4 DIMM: 288 pins
	• DDR5 DIMM: 288 pins (note: DDR generations are not interchangeable due to different notch positions)
• Use Case: Standard desktop PCs, gaming rigs, and workstations.

SO-DIMM (Small Outline Dual In-line Memory Module)

• What it is: A smaller, compact alternative to a standard DIMM (roughly half the physical size).
• Size: Measures approximately 69.6 mm in length.
• Pin Count:
	• DDR4 SO-DIMM: 260 pins
	• DDR5 SO-DIMM: 262 pins
• Use Case: Laptops, notebook computers, mini-PCs (like NUCs), and select network hardware.

Key Differences at a Glance


Feature	               DIMM (Desktop)	                         SO-DIMM (Laptop)
Length	               ~133.35 mm	                             ~69.6 mm
DDR4 Pins	            288-pin	                                  260-pin
DDR5 Pins	            288-pin	                                  262-pin
Interchangeable?	   No — they will not physically fit each other's slots.	


Motherboard and its types:
A motherboard is the main printed circuit board in a computer that connects the CPU, memory, storage, and other hardware components, managing power distribution and data flow between them.


Main Types (Form Factors) of Motherboards

Motherboards come in different sizes, called form factors, which determine how large a computer case needs to be and how many expansion options are available:
• Mini-ITX (170 x 170 mm)
	• Slots: 1 to 2 RAM slots, 1 PCIe slot.
	• Best for: Ultra-compact builds, media centers, or HTPCs.
• Micro-ATX (244 x 244 mm)
	• Slots: Up to 4 RAM slots, 1 to 2 (sometimes 4) PCIe slots.
	• Best for: Budget builds and smaller mid-tower cases that save space without losing too many features.
• Standard ATX (305 x 244 mm)
	• Slots: Up to 4 RAM slots, multiple PCIe slots.
	• Best for: Mainstream desktop PCs, gaming rigs, and general content creation.
    • Extended ATX (E-ATX) (344 x 330 mm or larger)
	• Slots: Up to 8 RAM slots, heavy PCIe support, and sometimes dual CPU sockets.
	• Best for: High-end workstations, heavy AI modeling, servers, and extreme gaming rigs.
• Legacy and Specialized Boards
	• BTX: Designed by Intel for better thermal and airflow management, though rarely used today.
	• Industrial / Embedded Boards: Ruggedized single-board designs (such as Nano-ITX or Pico-ITX) built for extreme environments, automation, and IoT devices.


Main Components and Their Functions

• CPU Socket: A square mechanical interface where the processor is installed. Different processors require specific socket types designed for Intel or AMD.
• RAM (DIMM) Slots: Long vertical slots located near the CPU that hold system memory modules (DDR4 or DDR5) for fast, temporary data access.
• Chipset (PCH): A controller chip (or set of chips) hidden under a heatsink that manages data flow between the CPU, RAM, storage, and peripheral devices.
• VRM (Voltage Regulator Module): A cluster of small electronic components surrounding the CPU socket that cleans, regulates, and steps down power from the power supply unit to a safe level for the processor.
• PCIe Expansion Slots: Long slots (such as PCIe x16) used to plug in dedicated graphics cards (GPUs), sound cards, or high-speed network cards.

• Storage Connectors:• SATA Ports: Used to plug in traditional hard disk drives (HDDs) and 2.5-inch SATA solid-state drives (SSDs).
• M.2 Slots: Direct-mount sockets built for fast NVMe solid-state drives.
• BIOS / UEFI Chip: A non-volatile ROM/EEPROM chip containing low-level firmware that initializes and tests hardware during the boot process before loading the operating system.
• CMOS Battery: A small, round coin-cell battery that preserves basic system BIOS settings (such as time, date, and boot order) when the computer is unplugged or powered off.
• Power Connectors:• 24-pin ATX Connector: Supplies main power to the motherboard circuitry, RAM, and PCIe slots.
• CPU Power Connector (8-pin): Delivers dedicated electrical power directly to the CPU and VRM.

• Rear I/O Panel: A cluster of external ports on the back edge of the board, including USB ports, Ethernet (LAN) jacks, audio connections, and display outputs.
• Internal Headers: Pins on the board that connect case buttons, front USB/audio ports, cooling fans, and RGB lighting.



BIOS:
The BIOS (Basic Input/Output System) is pre-installed firmware stored on a motherboard memory chip that starts your computer and prepares its hardware before handing control over to the operating system.

Key Functions

• Power-On Self-Test (POST): Runs diagnostic tests to check hardware like RAM, keyboards, and drives, reporting any errors with beeps or codes.
• Hardware Initialization: Identifies and configures components such as the CPU clock speed, memory timings, and storage devices.
• Bootstrap Loader: Locates the operating system on your storage drive and loads it into the computer's memory.
• CMOS/BIOS Setup Utility: Allows users to change system settings like boot order, hardware voltages, and date/time.

BIOS vs. UEFI

• Legacy BIOS: Uses the Master Boot Record (MBR) and supports older, smaller storage drives (2TB or less).
• UEFI (Unified Extensible Firmware Interface): The modern replacement for legacy BIOS, which supports drives larger than 2TB, faster parallel boot times, a mouse-friendly graphical interface, and enhanced security features like Secure Boot. Most modern systems use UEFI while still informally referring to it as the BIOS
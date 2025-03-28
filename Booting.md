
# Computer Fundamentals

## **Computer**

A computer is an electronic device that takes raw input from the user, processes it, and provides a result as output.

### **Processing Devices**
- **CPU (Central Processing Unit)**
- **GPU (Graphics Processing Unit)**
- **Motherboard**
- **RAM (Random Access Memory)**
- **ROM (Read-Only Memory)**

### **Two Main Parts of a Computer**
1. **Hardware**
   - **Input Devices**: Keyboard, scanner, mouse, webcam
   - **Output Devices**: Printer, speaker, monitor
   - **Memory Devices**:
     - **Primary Memory**: RAM, ROM
     - **Secondary Memory**: HDD, SSD, CD, USB, pen drive, etc.

2. **Software**
   - **System Software**: Operating System (OS), BIOS (Basic Input Output System)
   - **Application Software**: Notepad, VLC, Firefox, MS Office, and other single-purpose software
   - **Utility Software**: Device drivers, antivirus, firewall

---

## **Current**

Current refers to the flow of electric charge. There are two types of current:

1. **DC (Direct Current)**
2. **AC (Alternating Current)**

### **AC (Alternating Current)**
- **Machines**: Devices that take input physically, process it physically, and provide output physically are known as machines. Machines use AC current.
- **Wattage Range**: 70W to 240W
- **Examples of AC Machines**: Tubelight, mixer grinder, fan, washing machine, water motor, etc.

### **DC (Direct Current)**
- **Electronic Devices**: Devices that use logic to solve problems efficiently are called electronic devices.
- **Examples of DC Devices**: Laptop, personal computer, television screen, electric vehicles, etc.

---

## **Booting Process**

![image](https://github.com/user-attachments/assets/b280a21d-ecd6-41a9-9f25-85ae5d2e73f5)


### **SMPS (Switched-Mode Power Supply)**
- The current passes through a three-pin socket with 70W to 240W.
- The SMPS stores around 300W inside.
- The SMPS provides multiple power outputs of -12V or +12V.
- A good supply reaches the trigger at around ±5V.
- Pressing the power button sends a signal to the SMPS to start.
- The SMPS powers the motherboard.
- The first power supply is sent to the CMOS section.
- **CMOS (Complementary Metal-Oxide-Semiconductor)** BIOS is activated.
- The BIOS retrieves its settings from ROM and loads into RAM.
- Essential components like CPU, GPU, RAM, and ROM become active.
- Two main motherboard chips:
  - **ICH (Input/Output Controller Hub)**
  - **GMCH (Graphics Memory Controller Hub)**
- The BIOS loads the RAM manufacturer logo.
- The BIOS executes **POST (Power-On Self Test)**.

### **(A) POST (Power-On Self-Test)**
1. Checks primary devices (CPU, GPU, RAM, ROM, SMPS, fan, motherboard).
2. Checks secondary devices (DVD, HDD, CD, SSD).
3. Checks input devices (mouse, keyboard).

### **(B) Boot Order Process**
1. Power-up: System receives power.
2. **POST (Power-On Self-Test)** runs.
3. The system searches for a boot device using the **MBR (Master Boot Record)**.
4. The MBR stores information about the HDD partitions.
5. The operating system is loaded.
6. BIOS loads the bootloader into RAM.
7. The bootloader shows the loading screen.
8. The desktop environment becomes usable.

### **Types of Booting**
1. **Cold Booting** - Starting the computer from a completely powered-off state.
2. **Warm Booting** - Restarting the computer without fully powering it off.

---

## **Operating System (OS)**

An operating system acts as an interface between the user and the computer hardware and manages the execution of programs.

### **Types of Windows OS**

#### **Server OS**
- Used to provide services to multiple clients.
- Provides enhanced security.
- Runs on servers.
- Handles multiple clients simultaneously.
- Complex and more stable.
- Higher processing power.

#### **Client OS**
- Receives services from a server.
- Simple operating system.
- Runs on desktops or laptops.
- Less processing power.
- Less stable.
- Serves a single user.
- Less efficient.

### **Types of User Interfaces (UI)**
1. **Command-Line Interface (CLI)**
2. **Graphical User Interface (GUI)**
3. **Text-Based User Interface (TUI)**

### **Five Tasks of an OS**
1. Command & control hardware.
2. Process management.
3. Provides a user platform.
4. Translates human language into machine language.
5. Manages input and output operations.

---

## **BIOS vs. UEFI**

### **BIOS (Basic Input Output System)**
- Classical method for detecting and connecting peripherals.
- Runs in 16-bit mode with only 1MB execution space.
- Supports only the MBR partition scheme.

### **UEFI (Unified Extensible Firmware Interface)**
- Modern replacement for BIOS.
- Can run in 32-bit or 64-bit mode.
- Supports both MBR and GPT partition schemes.

---

## **MBR vs. GPT**

**MBR (Master Boot Record)**
- Supports up to 4 primary partitions.
- Limited to a maximum storage of 2TB.
- Stores partition information in the first 512 bytes of the disk.

**GPT (GUID Partition Table)**
- Supports unlimited partitions (depending on the OS).
- Allows storage beyond 2TB.
- Uses CRC32 checksums for integrity.

---

## **Units of Computer Memory**

| Unit         | Abbreviation | Equivalent |
|-------------|--------------|-------------|
| Bit         | Bit          | 1 Binary Digit |
| Nibble      | Nibble       | 4 Bits |
| Byte        | Byte         | 8 Bits |
| Kilobyte    | KB          | 1024 Bytes |
| Megabyte    | MB          | 1024 KB |
| Gigabyte    | GB          | 1024 MB |
| Terabyte    | TB          | 1024 GB |
| Petabyte    | PB          | 1024 TB |
| Exabyte     | EB          | 1024 PB |
| Zettabyte   | ZB          | 1024 EB |
| Yottabyte   | YB          | 1024 ZB |

---






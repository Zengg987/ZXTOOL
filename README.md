# ZXTOOL
Here’s the revised guide for your C# .NET Core project:

---

## ZXTOOL Network Analysis Toolkit

### Overview

ZXTOOL is a **Network Analysis Toolkit v1.0** built with **C# .NET Core**, designed for **Advanced Network Exploration**, **Security Research**, and **Diagnostic Tools**. It offers a range of utilities for analyzing and diagnosing network issues effectively.

**Creator**: Zen  
**CAUTION**: Use responsibly and ethically.

---

### Features

1. **Domain to IP Resolution**: Convert domain names to their corresponding IP addresses.
2. **IP to Domain Resolution**: Retrieve the domain name for a given IP address.
3. **Network Packet Capture**: Analyze real-time network traffic packets.
4. **Network Interface Information**: Display detailed information about network interfaces.
5. **Port Scanner**: Scan and identify open ports on a target system.
6. **Packet Stress Test**: Simulate high-traffic packet loads for stress testing.

---

### Screenshot

![image](https://github.com/user-attachments/assets/206813c0-741c-49c3-8d5a-7136f9ace095)


---

### Prerequisites

1. **.NET Core SDK** installed on your system. [Download here](https://dotnet.microsoft.com/download).
2. **NPCAP** installed on your system. [Download here](https://npcap.com/#download).
3. Administrative/root privileges may be required for some features (e.g., packet capture).

---

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```

2. Build the project:
   ```bash
   dotnet build
   ```

3. Run the tool:
   ```bash
   dotnet run
   ```

---

### Usage

1. Launch the application:
   ```bash
   dotnet run
   ```

2. Navigate through the menu options by entering the corresponding number.

---

### Deployment

To publish the application for distribution:

1. Use the `dotnet publish` command:
   ```bash
   dotnet publish -c Release -r win-x64 --self-contained
   ```
   Replace `win-x64` with the target runtime (e.g., `linux-x64`, `osx-x64`).

2. Distribute the published files in the `bin/Release/netcoreappX.X/publish/` folder.

---

### Contributing

Contributions are welcome!  
1. Fork the repository.  
2. Create a new branch for your feature or fix.  
3. Submit a pull request.

---

### License

This project is licensed under the MIT License.

---

Replace `<your-username>` and `<your-repo>` with your GitHub username and repository name. Let me know if you need help refining or publishing this!

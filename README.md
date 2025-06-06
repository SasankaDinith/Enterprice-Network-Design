
   <h1>🌐 Enterprise Network Design using Cisco Packet Tracer</h1>
    <p>This project simulates a real-world <strong>enterprise/campus network</strong> using <strong>Cisco Packet Tracer</strong>, ideal for institutions such as universities or corporate environments with multiple departments and remote locations.</p>

   ![image url](https://github.com/SasankaDinith/Enterprice-Network-Design/blob/main/Screenshot%20(18).png?raw=true)
    
  <h2>🏗️ Project Overview</h2>
       <p>
    This University is a large university which has two campuses situated 20 miles apart.
    The university’s students and staff are distributed in 4 faculties. These include the faculties of
    Health and Sciences; Business; Engineering/Computing and Art/Design. Each member of staff has a PC and
    students have access to PCs in the labs.
  </p>

  <h2>Requirements:</h2>
  <p>
    a. Create a network topology with the main components to support the following:
  </p>

  <strong>Main campus:</strong>
  <ul>
    <li>
      <strong>Building A:</strong> Administrative staff in the departments of management, HR
      and finance. The admin staff PCs are distributed in the building offices and it is expected
      that they will share some networking equipment (Hint: use of VLANs is expected here).
      The Faculty of Business is also situated in this building
    </li>
    <li>
      <strong>Building B:</strong> Faculty of Engineering and Computing and Faculty of Art and
      Design
    </li>
    <li>
      <strong>Building C:</strong> Students’ labs and IT department. The IT department hosts the
      University Web server and other servers
    </li>
    <li>
      There is also an email server hosted externally on the cloud.
    </li>
  </ul>

  <strong>Smaller campus:</strong>
  <ul>
    <li>
      Faculty of Health and Sciences (staff and students’ labs are situated on
      separate floors)
    </li>
  </ul>

  <p>
    b. You will be expected to configure the core devices and few end devices to provide end-to-end
    connectivity and access to the internal servers and the external server.
  </p>

  <p>
    Each department/faculty is expected to be on its own separate IP network
  </p>
  <p>
    The switches should be configured with appropriate VLANs and security settings
  </p>
  <p>
    RIPV2 will be used to provide routing for the routers in the internal network and static router
    for the external server.
  </p>
</body>

  <h2>🔧 Features & Configuration</h2>
    <ul>
        <p>✅ <strong>VLAN Configuration</strong> - Each department is assigned a specific VLAN (e.g., VLAN90, VLAN100, etc.) to segment traffic and enhance security.</li>
        <p>✅ <strong>Inter-VLAN Routing</strong> - A multilayer switch is configured to enable communication between VLANs.</li>
        <p>✅ <strong>DHCP Server</strong> - Configured to automatically assign IP addresses to devices in different VLANs.</li>
        <p>✅ <strong>FTP Server & Cloud Simulation</strong> - Added for demonstrating server integration and external connectivity.</li>
        <p>✅ <strong>Subnetting & IP Scheme</strong> - A detailed subnetting plan to manage IP address distribution efficiently.</li>
        <p>✅ <strong>End Devices</strong> - Each department includes PCs, printers, and switches to simulate a realistic working environment.</li>
    </ul>

  <h2>📁 Files Included</h2>
    <ul>
        <li><strong>Enterprise_Network_Design.pkt</strong> – Cisco Packet Tracer project file</li>
        <li><strong>README.md</strong> – This file</li>
        <li><strong>network_diagram.png</strong> – Screenshot of the full topology (optional)</li>
    </ul>

  <h2>📌 Learning Outcomes</h2>
    <ul>
        <li>VLAN and Inter-VLAN Routing</li>
        <li>Server configuration (DHCP, FTP)</li>
        <li>Subnetting and IP planning</li>
        <li>Layer 2 and Layer 3 device configuration</li>
        <li>Realistic simulation of enterprise network infrastructure</li>
    </ul>


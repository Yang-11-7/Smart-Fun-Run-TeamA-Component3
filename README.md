# Smart-Fun-Run-TeamA-Component3
**Project Title & Component Name:** Team A: Centralized Dashboard
## Team Members & Roles

| Name | Matric Number | Course | Project Role |
| :--- | :--- | :--- | :--- |
| LEE ZI YANG | AN230131 | IoT (BNF44403) & OS (BNF32303) | Leader, programmer |
| LIM WEI MING | AN230114 | IoT (BNF44403) & OS (BNF32303) | secretary |
| LOO JIA QUAN | AN230105 | IoT (BNF44403) & OS (BNF32303) | second secretary |
| NUR DINI DAYANA BINTI AHMAD KHOMEINI | DN240100 | OS (BNF32303) | - |
| KHAIRUNNAJLAA BINTI ZAMRI | DN240125 | OS (BNF32303) | - |
| NUR ATIFAH AZIDA BINTI MD. AZLI | DN240098 | OS (BNF32303) | - |
| NORFAIZ AMSYAR BIN NORFAIZAL | DN240096 | OS (BNF32303) | - |
| MUHAMMAD HASANUL HILMAN BIN MOHD NORHASNI | DN240049 | OS (BNF32303) | - |

## Component Overview
Component 3 serves as the centralized Node-RED dashboard for the Smart Fun Run ecosystem. It acts as the primary orchestrator bridging the physical IoT edge nodes with the backend operating system, processing incoming telemetry payloads into standardized JSON formats. The system provides real-time visualization of event metricssuch as participant checkpoint tracking and network latency—and features automated alert mechanisms to monitor overall system health and microservice connectivity for Team A.

## Quick Start Guide
Prerequisites: Ensure you have the LTS version of Node.js installed on your machine.

### 1. Install Node-RED
Open your terminal or command prompt and install Node-RED globally:

```Bash
npm install -g --unsafe-perm node-red
```

### 2. Install Dashboard Dependencies
This component relies on the Node-RED dashboard package for the UI. Install it by running:

```Bash
npm install -g node-red-dashboard
```

### 3. Launch Node-RED
Start the runtime server by executing:

```bash
node-red
```

### 4. Import the Flow and Deploy

1. Open a web browser and navigate to the editor at http://localhost:1880/.
2. Click the hamburger menu in the top right corner and select Import.
3. Upload or paste the contents of the flows.json file from this repository.
4. Click the Deploy button to make the system live.
5. Access your centralized dashboard interface by navigating to http://localhost:1880/dashboard.

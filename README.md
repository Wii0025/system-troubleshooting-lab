# system-troubleshooting-lab

## Overview
This project demonstrates troubleshooting a slow Windows system by identifying performance bottlenecks and applying optimisation techniques using built-in system tools.

Basic systemtroubleshooting lab (CPU, memory, performance analysis)

## Scenario 
An employee reported that their computer was running slowly, impacting productivity. Upon initial inspection, the system had a good CPU and sufficient storage.

## Step 1: Gathering Information

To investigate the issue, I gathered system specifications and performance data.

### System Specifications
- CPU: (Intel(R) Core(TM) i5-5200U CPU @ 2.20GHz, 2201 Mhz, 2 Core(s), 4 Logical Processor(s)
- RAM: (4.00 GB)
- Storage: (476 GB SSD (390 GB free)

### Performance Analysis
I used Task Manager to monitor system performance:
- CPU usage
- Memory usage
- Disk usage

### Applications in Use
- Microsoft 365 (Word, Excel, PowerPoint, Teams)

## Findings
The system slowdown may be caused by:
- High memory usage
- Background applications
- Resource-intensive programs

## Tools Used
- System Information (msinfo32)
- Task Manager

## Step 2: Identify the Root Cause

Based on the system analysis, the main cause of the slow performance is low memory (RAM).

The system has only 4 GB of RAM, which is insufficient for running modern applications such as Microsoft 365 and Teams, especially during multitasking or video conferencing.

Additionally, background processes may also be consuming system resources, further reducing performance.

The CPU is adequate for basic tasks, and the storage (SSD) is not a bottleneck. Therefore, the primary limitation is memory capacity.

### Identified Issues:
- Low RAM (4GB) causing slow performance
- High memory usage during multitasking
- Background applications consuming resources

## Step 3: Recommended Solutions

Based on the analysis, the following solutions are recommended to improve system performance:

### 1. Upgrade RAM (Primary Solution)
The system currently has 4GB of RAM, which is insufficient for modern applications such as Microsoft 365 and Teams.

- Recommended upgrade: 8GB minimum (16GB preferred)
- Benefit: Improved multitasking and faster application performance
- Impact: This will significantly reduce system slowdowns

### 2. Reduce Background Processes
Unnecessary background applications may be consuming system resources.

- Close unused applications via Task Manager
- Disable startup programs (Task Manager → Startup tab)
- Benefit: Frees up memory and CPU usage

### 3. Optimise Software and System Settings
Outdated or unoptimised software can affect performance.

- Ensure Windows is up to date
- Update Microsoft 365 applications
- Run disk cleanup to remove temporary files
- Benefit: Improves system efficiency and stability

### 4. Consider Cloud-Based Solutions
If hardware upgrades are limited, cloud services can reduce system load.

- Use web-based versions of Microsoft 365 (e.g. Office Online)
- Store files on OneDrive instead of local storage
- Benefit: Reduces local resource usage

### 5. Regular System Maintenance
Routine maintenance helps prevent performance issues.

- Perform regular system restarts
- Scan for malware/viruses
- Monitor performance using Task Manager

---

## Conclusion

The primary issue affecting system performance is low memory (RAM).  
Upgrading the RAM, combined with system optimisation and reducing background processes, will significantly improve performance and user productivity.

## Step 4: Implement and Monitor

To improve system performance, I carried out the following actions:

- Deleted temporary files using the Run command (temp)
- Removed unnecessary system files
- Skipped files that were in use

### Monitoring Results:
After cleanup, the number of temporary files was significantly reduced. This freed up storage space and contributed to improved system responsiveness.

### Temporary Files Cleanup

Before cleanup:
![Temp Files Before](./images/temp-files-before-cleanup.png)

After cleanup:
![Temp Files After](./images/temp-files-after-cleanup.png)

Temporary files were deleted to improve system performance.

Some files could not be removed as they were in use by system processes, which is expected behaviour in Windows environments.

This cleanup reduced unnecessary disk usage and contributed to improved system responsiveness.

## Step 5: Ongoing Solutions

## Results
- Reduced number of temporary files significantly  
- Improved system responsiveness  
- Identified RAM as a key performance bottleneck

To prevent similar performance issues in the future, the following steps can be taken:

- Educate the user on managing system resources, such as closing unused applications and avoiding running too many programs at once.
- Encourage the use of lightweight applications where possible to reduce system load.
- Schedule regular system maintenance, including deleting temporary files and checking system performance.
- Monitor startup programs and disable unnecessary applications to improve boot time and performance.
- Consider upgrading hardware, such as increasing RAM, to support modern applications more efficiently.




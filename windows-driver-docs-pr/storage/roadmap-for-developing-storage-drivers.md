---
title: Roadmap for Developing Windows Storage Drivers
description: Roadmap for Developing Windows Storage Drivers
ms.assetid: 67627ff9-588c-492f-861f-c592f7f92b51
ms.date: 04/20/2017
ms.localizationpriority: medium
---

# Roadmap for Developing Windows Storage Drivers


![figure of a roadmap with the text "wdk" superimposed on a highway](images/wdkroadmap-th.png)To create a storage driver, perform the following steps:

1.  **Learn about Windows architecture and drivers.**

    You must understand the fundamentals of how drivers work in Windows operating systems. Knowing the fundamentals will help you make appropriate design decisions and allow you to streamline your development process. See [Concepts for all driver developers](https://msdn.microsoft.com/library/windows/hardware/ff554731).

2.  **Learn the fundamentals of storage drivers.**

    To learn storage driver fundamentals, see [Windows Storage Driver Architecture](storage-driver-architecture.md).

3.  **Determine additional storage driver design decisions.**

    For information about how to make design decisions, see [Capabilities Provided by Storport](capabilities-provided-by-storport.md), [Storage Virtual Miniport Drivers: When Are They Appropriate?](storage-virtual-miniport-drivers--when-are-they-appropriate-.md), and [Making SCSI Port Miniport Drivers Work with Storport](making-scsi-port-miniport-drivers-work-with-storport.md).

4.  **Learn about storage in the Windows operating system.**

    See [History of Storport](history-of-storport.md) in the Windows Driver Kit (WDK).

5.  **Learn about the Windows driver build, test, and debug processes and tools.**

    Building a driver is not the same as building a user-mode application. See [Developing, Testing, and Deploying Drivers](https://msdn.microsoft.com/windows-drivers/develop/visual_studio_driver_development_environment) for information about Windows driver build, debug, and test processes, driver signing, and Windows Logo testing. See [Driver Development Tools](https://msdn.microsoft.com/library/windows/hardware/ff545440) for information about building, testing, verifying, and debugging tools.

6.  **Review storage driver samples.**

    To access and review the storport miniport driver samples see the [Windows Driver Kit (WDK) samples](http://go.microsoft.com/fwlink/p/?LinkId=618052).

7.  **Develop, build, test, and debug your storage driver.**

    See [Building a Driver](https://msdn.microsoft.com/windows-drivers/develop/building_a_driver), [Testing a Driver](https://msdn.microsoft.com/windows-drivers/develop/testing_a_driver), and [Debugging a Driver](https://msdn.microsoft.com/windows-drivers/develop/debugging_a_driver) for information about iterative building, testing, and debugging. This process will help ensure that you build a driver that works.

8.  **Create a driver package for your storage driver.**

    For more information, see [Creating a Driver Package](https://msdn.microsoft.com/windows-drivers/develop/creating_a_driver_package).

9.  **Sign and distribute your storage** **driver.**

    The final step is to sign (optional) and distribute the driver. If your driver meets the quality standards that are defined for Windows Hardware Certification, you can distribute it through the Microsoft Windows Update program. For more information, see [Distributing a Driver Package](https://msdn.microsoft.com/windows-drivers/develop/distributing_a_driver_package_win8).

These are the basic steps. Additional steps might be necessary based on the needs of your individual driver.

 

 





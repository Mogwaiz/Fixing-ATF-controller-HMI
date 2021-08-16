# Fixing-ATF-controller-HMI
This guide will help you transfering the software from the HMI of a C24 - 4 ATF system controller to a new HMI, as Repligen no longer want to sell replace screens or charges 10000+ EUR for a replacement screen. All you need is a new HMI5070P (640€) from Maple System and a micro usb cable. 

The issue: The screen of the HMI start to get unreadable and it is difficult to interact with the controller. After investigation I have identified that the culpit is the daugter board with ID: Weintek_labs AV2_7 V1.1. Changing LCD does not change the issue. So far I have not yet found the fix

The solution: Order a 5070P screen from Maple Systems and download the emtp file (ATF 2.5) onto the new HMI using EZPlus (software can be downloaded for free from Maple Systems). The HMI software is a unmodified version exacted from the old Refine HMI using this guide: https://www.maplesystems.com/legacysolutions/converthmi5070thtoadvancedhmi.htm. 

I hope this guide can either be a wakeup call for Repligen and their policies of planned obselence, or at least help people repair the items and reduce electronic trash.

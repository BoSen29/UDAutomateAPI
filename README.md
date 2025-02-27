# UDAutomateAPI

Fork from https://github.com/gavsto/AutomateAPI, with optimized support to run in a Universal Dashboard https://github.com/ironmansoftware/universal-dashboard/. 
Some added features along the way.

# Features
1) Get, search and return Powershell objects for pre-defined searches or custom conditions using Get-AutomateComputer. See https://github.com/gavsto/AutomateAPI/wiki/Get-AutomateComputer

2) Identify agents that are online in Control and offline in Automate. See https://github.com/gavsto/AutomateAPI/wiki/Autofix-Broken-Agents

3) Autofix agents that are broken using Repair-AutomateAgent. See https://github.com/gavsto/AutomateAPI/wiki/Autofix-Broken-Agents

A Powershell Module created by Gavin Stone (Gavsto) for the ConnectWise Automate API

# How do I get Going
See https://github.com/gavsto/AutomateAPI/wiki/Pre-requisites-and-Install

Then https://github.com/gavsto/AutomateAPI/wiki/Getting-Started-and-Connected

Then https://github.com/gavsto/AutomateAPI/wiki/Get-AutomateComputer

If you're interested in repairing broken agents https://github.com/gavsto/AutomateAPI/wiki/Autofix-Broken-Agents

# I want to help
Great - dig in and submit a pull request! Please make sure your follow the conventions set by the other modules. Write documentation for functions, support pipeline input where required etc.

# Significant Contributions

**Darren White** for his pre-input, ongoing code support with the code and then his extensive support in helping me get the Control portions of this module down from 10 minutes to 25 seconds per 2500 PCs. You are defintely a legend, Darren.

# Special Thanks
Special thanks to a number of people whose help (and in certain cases code) I have used within this project

**Chris Taylor** where I have re-used and modified certain parts of the ConnectWise Control module to send commands to Contrl and his ConnectWise Automate module so we can reinstall services

**Mendy Green** for helping me test the initial code

**Davíð Snædal** for his assistance before this module even started with guidance on connection to the Automate REST APIs

**ConnectWise** for absolutely smashing the delivery of their API


# WinBuilder-Scripts
This repository contains scripts for WinBuilder which I developed some time ago.

## What is WinBuilder?
"WinBuilder is a free application designed to build and customize boot disks (Live CDs) based on Microsoft Windows (WinPE)."

## What scripts are provided here?

### Safeguard Easy / Disk Encryption (SGE / SDE)

This scripts integrates Safeguard Easy / Disk Encryption Recovery Logon into your PE.
I tested it successfully with Win7PE_SE (2010-11-12) and two encrypted hard drives. One hard drive is encrypted with SGE 4.40 and the other with SGE 4.30.

### Safeguard Enterprise
This scripts integrates Safeguard Enterprise Key Recovery into your PE.
I tested it successfully with Win7PE_SE (2010-11-12) and one encrypted hard drive. The hard drive is encrypted with SGN 5.50.0.116. I managed it to make it possible to integrate the Key Recovery from a machine that has no SGN installed with a little trick. 

### SGE / SDE / SGN Shortcuts
This script creates Shortcuts for the executable files of the first and the second script (Desktop / Quicklaunch / Startmenu)

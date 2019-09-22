---
layout: page
title:  "Projects"
color:  blue
width:   3
height:  1
date:   2016-03-30 11:31:49 +0200
categories: jekyll update
---

<div class="project_heading">
<h4>DRAM Solutions</h4> </div>
<div class="project_description">
<ui>
  <li> To decode and implement CPGC( converged pattern generator and checker ) an Intel proprietary on PCT 1.5 ( a customized Intel kabylake board used for testing DDR4's in Korea ). CPGC is a reusable BIST ( built in self-test ) engine to detect memory ( DRAM ) and IO defects with software assisted repair technology ( PPR ) to repair them.</li>
  <li>As part of this development I studied CPGC patents and did reverse engineering to figure out the features and functionalities of it which included making changes in BIOS code of Intel kabylake to develop our own pattern using CPGC and then validating the same on the DRAM data bus using inter-posers and logic analyzer (1333 MHz).</li>
  <li>Implemented BIST algorithms like MARCH and MATS using CPGC in the BIOS code to increase the test coverage and reduce the test time as CPGC is faster than the software testing.</li>
  <li>Enabled CPGC for memory training to reduce the validation time.</li>
  </ui>
  </div>


  <div class="project_heading">
  <h4>Analyze Mobile Payment Apps</h4> </div>
  <div class="project_description">
  <ui>
    <li> Analyzing an Android mobile payment app to check for Security vulnerabilities concentrating on communication protocols used, proper authentication and cryptographic implementation.</li>
    <li>Did automated analysis of the app to check for SSL/TLS vulnerabilities like certification errors using mallodroid.</li>
    <li>Used qualys SSL server test to check for SSL/TLS end point vulnerabilities.</li>
    <li>Manual analysis of the app code for behavior of the app, data flows, permissions and information leakage.</li>
    <li>checking proper implementation of the cryptography which included verifying message encryption and integrity</li>
    </ui>
    </div>


<div class="project_heading">
<h4> Security DIMM</h4></div>
  <div class="project_description">
    <ui>

      <li>Project to develop a security IP inside DRAM that will make some region of the dram as read only once the IP is enabled.</li>
      <li>It involved two phases hacking and security. As part of this project I developed 2 exploits to hack the
      Linux kernel which were than protected using the security IP.</li>
      <li>Hacking a remote Ubuntu PC using Kali Linux and modifying the kernel (version 4.2) code : Assuming the attacker
      knows the IP and username of the victim.</li>
      <li>Used hydra-gtk to crack the password using dictionary based attack and then elevating the privileges to root using Dirty cow (CVE-2016-5195) exploit.</li>
      <li>Determining the address of the kernel code section using cat/proc/iomem and erasing the 16th bit of CR0 Register which allowed modification of kernel code.</li>
    </ui>
  </div>




<div class="project_heading">
<h4> Row Hammering</h4></div>
  <div class="project_description">
    <ui>

      <li>Exploit in Linux to modify kernel code DRAM by a normal application using row hammering vulnerability.</li>
      <li>Created a shared memory segment and mapped it multiple times to fill most of the physical memory with page table.</li>
      <li>Row hammering was done on the page table to cause a bit flip in the page table entry to point it to one of the page table rather than physical address.</li>
      <li>Got read/write access to the whole physical memory by modifying that page table which could be used for modifying kernel code.</li>
    </ui>
  </div>


<div class="project_heading">
<h4> IO-Margin</h4> </div>
<div class="project_description">
<ui>

<li> Designed and developed the back end of the software in C language to analyze the effect of timing parameter tRAS, tCL, tRCD) on the DRAM performance (latency , ISI , cross-talks , data rate) and to set the best case of parameters for max imal performance based on eye diag ram.</li>
</ui></div>

<div class="project_heading">
<h4>EPICS (Engineering Projects in Community Service) </h4></div>
<div class="project_description">

<ui>
<li> Smart Chair for Disabled People: Project Involved Building Smart chair with control movement, call facility and lighting control features.</li>
<li>Designed and Implemented the Smart lighting features using Arduino UNO board, relays, Bluetooth Module(HC-05) to
control the lighting using buttons given on chair.</li>
<li>Demonstrated skills of coding in C, understanding of pin diagrams and AVR microcontroller, debugging and working of
Bluetooth module.</li>
<li> <b>Learning : AVR Microcontroller, HC-05 Bluetooth Module, Arduino.</b></li>
</ui></div>

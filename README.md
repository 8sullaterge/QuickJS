# Vt-x Support
  
Intel Virtualization Technology abstracts hardware that allows multiple workloads to share a common set of resources. On shared virtualized hardware, a variety of workloads can co-locate while maintaining full isolation from each other, freely migrate across infrastructures, and scale as needed.
 
With a VT-x supported Intel Processor and a VT-x supported BIOS, VT-x can be enabled or disabled in BIOS. Refer to your motherboard vendor for exact instructions if the option is not available in BIOS.
 
**Download ✓ [https://stupimoplanze.blogspot.com/?download=2A0Tcs](https://stupimoplanze.blogspot.com/?download=2A0Tcs)**


 
If Intel Virtualization Technology is not checked in the tool, there might be a possibility your processor still supports Intel Virtualization Technology, but it is already being used by some software that uses a hypervisor. In that case, you can also use the Task Manager to verify the situation.
 
With a VT-x supported Intel Processor and a VT-x supported BIOS, VT-x can be enabled or disabled in BIOS. Refer to your motherboard vendor for exact instructions if the option is not available in BIOS
 
In the late 1990s x86 virtualization was achieved by complex software techniques, necessary to compensate for the processor's lack of hardware-assisted virtualization capabilities while attaining reasonable performance. In 2005 and 2006, both Intel (VT-x) and AMD (AMD-V) introduced limited hardware virtualization support that allowed simpler virtualization software but offered very few speed benefits.[1] Greater hardware support, which allowed substantial speed improvements, came with later processor models.
 
In protected mode the operating system kernel runs at a higher privilege such as ring 0, and applications at a lower privilege such as ring 3.[*citation needed*] In software-based virtualization, a host OS has direct access to hardware while the guest OSs have limited access to hardware, just like any other application of the host OS. One approach used in x86 software-based virtualization to overcome this limitation is called *ring deprivileging*, which involves running the guest OS at a ring higher (lesser privileged) than 0.[2]
 
On traditional mainframes, the classic type 1 hypervisor was self-standing and did not depend on any operating system or run any user applications itself. In contrast, the first x86 virtualization products were aimed at workstation computers, and ran a guest OS inside a host OS by embedding the hypervisor in a kernel module that ran under the host OS (type 2 hypervisor).[8]
 
A different route was taken by other systems like Denali, L4, and Xen, known as paravirtualization, which involves porting operating systems to run on the resulting virtual machine, which does not implement the parts of the actual x86 instruction set that are hard to virtualize. The paravirtualized I/O has significant performance benefits as demonstrated in the original SOSP'03 Xen paper.[10]
 
In 2005 and 2006, Intel and AMD (working independently) created new processor extensions to the x86 architecture. The first generation of x86 hardware virtualization addressed the issue of privileged instructions. The issue of low performance of virtualized system memory was addressed with MMU virtualization that was added to the chipset later.

Because the Intel 80286 could not run concurrent DOS applications well by itself in protected mode, Intel introduced the virtual 8086 mode in their 80386 chip, which offered virtualized 8086 processors on the 386 and later chips. Hardware support for virtualizing the protected mode itself, however, became available 20 years later.[15]
 
AMD developed its first generation virtualization extensions under the code name "Pacifica", and initially published them as AMD Secure Virtual Machine (SVM),[16] but later marketed them under the trademark *AMD Virtualization*, abbreviated *AMD-V*.
 
AMD-V capability also features on the Athlon 64 and Athlon 64 X2 family of processors with revisions "F" or "G" on socket AM2, Turion 64 X2, and Opteron 2nd generation[17] and third-generation,[18] Phenom and Phenom II processors. The APU Fusion processors support AMD-V. AMD-V is not supported by any Socket 939 processors. The only Sempron processors which support it are APUs and Huron, Regor, Sargas desktop CPUs.
 
AMD Opteron CPUs beginning with the Family 0x10 Barcelona line, and Phenom II CPUs, support a second generation hardware virtualization technology called Rapid Virtualization Indexing (formerly known as Nested Page Tables during its development), later adopted by Intel as Extended Page Tables (EPT).
 
The CPU flag for AMD-V is "svm". This may be checked in BSD derivatives via dmesg or sysctl and in Linux via /proc/cpuinfo.[19] Instructions in AMD-V include VMRUN, VMLOAD, VMSAVE, CLGI, VMMCALL, INVLPGA, SKINIT, and STGI.
 
Previously codenamed "Vanderpool", VT-x represents Intel's technology for virtualization on the x86 platform. On November 13, 2005, Intel released two models of Pentium 4 (Model 662 and 672) as the first Intel processors to support VT-x. The CPU flag for VT-x capability is "vmx"; in Linux, this can be checked via /proc/cpuinfo, or in macOS via sysctl machdep.cpu.features.[19]
 
"VMX" stands for Virtual Machine Extensions, which adds 13 new instructions: VMPTRLD, VMPTRST, VMCLEAR, VMREAD, VMWRITE, VMCALL, VMLAUNCH, VMRESUME, VMXOFF, VMXON, INVEPT, INVVPID, and VMFUNC.[21] These instructions permit entering and exiting a virtual execution mode where the guest OS perceives itself as running with full privilege (ring 0), but the host OS remains protected.
 
As of 2015[update], almost all newer server, desktop and mobile Intel processors support VT-x, with some of the Intel Atom processors as the primary exception.[22] With some motherboards, users must enable Intel's VT-x feature in the BIOS setup before applications can make use of it.[23]
 
Since the Haswell microarchitecture (announced in 2013), Intel started to include *VMCS shadowing* as a technology that accelerates nested virtualization of VMMs.[30]The *virtual machine control structure* (VMCS) is a data structure in memory that exists exactly once per VM, while it is managed by the VMM. With every change of the execution context between different VMs, the VMCS is restored for the current VM, defining the state of the VM's virtual processor.[31] As soon as more than one VMM or nested VMMs are used, a problem appears in a way similar to what required shadow page table management to be invented, as described above. In such cases, VMCS needs to be shadowed multiple times (in case of nesting) and partially implemented in software in case there is no hardware support by the processor. To make shadow VMCS handling more efficient, Intel implemented hardware support for VMCS shadowing.[32]
 
VIA Nano 3000 Series Processors and higher support VIA VT virtualization technology compatible with Intel VT-x.[33] EPT is present in Zhaoxin ZX-C, a descendant of VIA QuadCore-E & Eden X4 similar to Nano C4350AL.[34]
 
In 2012, AMD announced their *Advanced Virtual Interrupt Controller* (*AVIC*) targeting interrupt overhead reduction in virtualization environments.[35] This technology, as announced, does not support x2APIC.[36]In 2016, AVIC is available on the AMD family 15h models 6Xh(Carrizo) processors and newer.[37]
 
Also in 2012, Intel announced a similar technology for interrupt and APIC virtualization, which did not have a brand name at its announcement time.[38]Later, it was branded as *APIC virtualization* (*APICv*)[39]and it became commercially available in the Ivy Bridge EP series of Intel CPUs, which is sold as Xeon E5-26xx v2 (launched in late 2013) and as Xeon E5-46xx v2 (launched in early 2014).[40]
 
Graphics virtualization is not part of the x86 architecture. Intel Graphics Virtualization Technology (GVT) provides graphics virtualization as part of more recent Gen graphics architectures. Although AMD APUs implement the x86-64 instruction set, they implement AMD's own graphics architectures (TeraScale, GCN and RDNA) which do not support graphics virtualization.[*citation needed*] Larrabee was the only graphics microarchitecture based on x86, but it likely did not include support for graphics virtualization.
 
An input/output memory management unit (IOMMU) allows guest virtual machines to directly use peripheral devices, such as Ethernet, accelerated graphics cards, and hard-drive controllers, through DMA and interrupt remapping. This is sometimes called *PCI passthrough*.[42]
 
An IOMMU also allows operating systems to eliminate bounce buffers needed to allow themselves to communicate with peripheral devices whose memory address spaces are smaller than the operating system's memory address space, by using memory address translation. At the same time, an IOMMU also allows operating systems and hypervisors to prevent buggy or malicious hardware from compromising memory security.
 
In addition to the CPU support, both motherboard chipset and system firmware (BIOS or UEFI) need to fully support the IOMMU I/O virtualization functionality for it to be usable. Only the PCI or PCI Express devices supporting *function level reset* (FLR) can be virtualized this way, as it is required for reassigning various device functions between virtual machines.[46][47] If a device to be assigned does not support Message Signaled Interrupts (MSI), it must not share interrupt lines with other devices for the assignment to be possible.[48]All conventional PCI devices routed behind a PCI/PCI-X-to-PCI Express bridge can be assigned to a guest virtual machine only all at once; PCI Express devices have no such restriction.
 
In SR-IOV, the most common of these, a host VMM configures supported devices to create and allocate virtual "shadows" of their configuration spaces so that virtual machine guests can directly configure and access such "shadow" device resources.[52] With SR-IOV enabled, virtualized network interfaces are directly accessible to the guests,[53]avoiding involvement of the VMM and resulting in high overall performance;[51] for example, SR-IOV achieves over 95% of the bare metal network bandwidth in NASA's virtualized datacenter[54] and in the Amazon Public Cloud.[55][56]
 a2f82b0cb4
 

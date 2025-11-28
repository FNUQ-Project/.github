# FNUQ Projcet
Welcome to the FNUQ Project, a project designed to address the shortcomings of QEMU, particularly its poor support for UEFI, its inadequate compatibility with Apple M-series chips, and the lack of a user-friendly visual interface.<br>
This is not an independent project. To be precise, it was developed and released by the E-comOS Opeartion Systems Team. More specifically, it was developed because the combination of a 64-bit kernel and UEFI was difficult to test in QEMU during the development of the E-comOS kernel. (Incidentally, FNUQ stands for Fuck No UEFI's QEMU.)<br>
## What do FNUQ do
Simply put, FNUQ aims to provide macOS developers with the same experience as testing on Linux. To replicate the macOS experience 100%, we use a hybrid C+Swift development model. Developers—or users—only need to drag and drop their .img, .iso, or other image files into the graphical interface (of course, if you want to use the command line, there will be instructions in the core repository).
## Why we create a organizational
"One repository is enough!" some might say. But we also have a graphical interface, so the core repository is the core, the "kernel" of FNUQ, while FTK is an extension. One repository cannot solve this distribution problem, so we created an organizational account.
## License
We often use GUN AGPL Version 3.

# Module: Sandboxing

The slides for this module are:

- [Sandboxing: Introduction](https://youtu.be/Ide_eg-eQZ0) (slides [here](https://docs.google.com/presentation/d/1TpMjTimroiC3Jm0dsteHWEUw06yZ5Oh7iM8YBmbOUkI/edit))
- [Sandboxing: chroot](https://youtu.be/C81lO7pG5aA) (slides [here](https://docs.google.com/presentation/d/1AWl9Gko_L1kDLBtrTFB3EohQU4vQjykpQE5dm9uxYi0/edit))
- **COMING SOON** Sandboxing: seccomp
- **COMING SOON** Sandboxing: cgroups

Additionally, you should be quite familiar with the following fundamental knowledge:

- [Fundamentals: Linux Process Execution](https://www.youtube.com/watch?v=Vtb5wIlthRg) (slides [here](https://docs.google.com/presentation/d/1ezY9Q8I0tzDD-7ZDXMbQM5RQ7z1dvB9-U_nDEhc6qdE/edit#slide=id.g8a9f5b81a5_0_0))

## Practice


Again, you will practice on a set of generated challenges.
There is a `/flag` file, and you get to choose one binary on which the SUID flag will be set.
The binaries that you are allowed to choose are all under the `/pwn` directory.

Each program will sandbox you to protect the flag.
If you can escape the sandbox, you can use read the `/flag` file.

If you are ready to tackle the challenges, go to [https://cse466.pwn.college](https://cse466.pwn.college)! **CHALLENGES WILL LAUNCH ON 9/9/2020! STAY TUNED!**

GPU: Intel® HD Graphics 530 on Intel i7-6700K

OS: Windows 10 x64 v2004


hashcat (v6.0.0) starting in benchmark mode...

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

You have enabled --force to bypass dangerous warnings and errors!
This can hide serious problems and should only be done when debugging.
Do not report hashcat issues encountered when using --force.
* Device #1: CUDA SDK Toolkit installation NOT detected.
             CUDA SDK Toolkit installation required for proper device support and utilization
             Falling back to OpenCL Runtime

OpenCL API (OpenCL 1.2 CUDA 11.0.186) - Platform #1 [NVIDIA Corporation]
========================================================================
* Device #1: GeForce RTX 2060, skipped

OpenCL API (OpenCL 2.1 ) - Platform #2 [Intel(R) Corporation]
=============================================================
* Device #2: Intel(R) HD Graphics 530, skipped
* Device #3: Intel(R) Core(TM) i7-6700K CPU @ 4.00GHz, 32129/32193 MB (8048 MB allocatable), 8MCU

Benchmark relevant options:
===========================
* --force
* --opencl-device-types=1
* --optimized-kernel-enable

Hashmode: 0 - MD5

Speed.#3.........:   708.6 MH/s (11.65ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 100 - SHA1

Speed.#3.........:   338.3 MH/s (24.57ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1400 - SHA2-256

Speed.#3.........:   135.9 MH/s (61.53ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 1700 - SHA2-512

Speed.#3.........: 44037.9 kH/s (95.02ms) @ Accel:512 Loops:1024 Thr:1 Vec:4

Hashmode: 22000 - WPA-PBKDF2-PMKID+EAPOL (Iterations: 4095)

Speed.#3.........:    16296 H/s (62.52ms) @ Accel:512 Loops:1024 Thr:1 Vec:8

Hashmode: 1000 - NTLM

Speed.#3.........:  1149.3 MH/s (7.15ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 3000 - LM

Speed.#3.........:   145.4 MH/s (57.26ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 5500 - NetNTLMv1 / NetNTLMv1+ESS

Speed.#3.........:   717.2 MH/s (11.52ms) @ Accel:1024 Loops:1024 Thr:1 Vec:8

Hashmode: 5600 - NetNTLMv2

Speed.#3.........: 58078.1 kH/s (72.01ms) @ Accel:1024 Loops:512 Thr:1 Vec:8

Hashmode: 1500 - descrypt, DES (Unix), Traditional DES

Speed.#3.........:  6179.8 kH/s (84.42ms) @ Accel:64 Loops:1024 Thr:1 Vec:8

Hashmode: 500 - md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5) (Iterations: 1000)

Speed.#3.........:    65064 H/s (62.40ms) @ Accel:512 Loops:1000 Thr:1 Vec:8

Hashmode: 3200 - bcrypt $2*$, Blowfish (Unix) (Iterations: 32)

Speed.#3.........:     4679 H/s (53.28ms) @ Accel:32 Loops:32 Thr:1 Vec:8

Hashmode: 1800 - sha512crypt $6$, SHA512 (Unix) (Iterations: 5000)

Speed.#3.........:     2831 H/s (71.98ms) @ Accel:512 Loops:256 Thr:1 Vec:4

Hashmode: 7500 - Kerberos 5, etype 23, AS-REQ Pre-Auth

Speed.#3.........:  6015.2 kH/s (87.01ms) @ Accel:16 Loops:64 Thr:64 Vec:8

Hashmode: 13100 - Kerberos 5, etype 23, TGS-REP

Speed.#3.........:  5583.6 kH/s (93.69ms) @ Accel:2 Loops:512 Thr:64 Vec:8

Hashmode: 15300 - DPAPI masterkey file v1 (Iterations: 23999)

Speed.#3.........:     2790 H/s (60.89ms) @ Accel:512 Loops:1024 Thr:1 Vec:8

Hashmode: 15900 - DPAPI masterkey file v2 (Iterations: 12899)

Speed.#3.........:     1701 H/s (92.35ms) @ Accel:256 Loops:1024 Thr:1 Vec:4

Hashmode: 7100 - macOS v10.8+ (PBKDF2-SHA512) (Iterations: 1023)

Speed.#3.........:    21268 H/s (63.58ms) @ Accel:512 Loops:511 Thr:1 Vec:4

Hashmode: 11600 - 7-Zip (Iterations: 16384)

Speed.#3.........:     3389 H/s (74.96ms) @ Accel:128 Loops:4096 Thr:1 Vec:8

Hashmode: 12500 - RAR3-hp (Iterations: 262144)

Speed.#3.........:      484 H/s (65.98ms) @ Accel:64 Loops:16384 Thr:1 Vec:8

Hashmode: 13000 - RAR5 (Iterations: 32799)

Speed.#3.........:     1675 H/s (73.97ms) @ Accel:512 Loops:1024 Thr:1 Vec:8

Hashmode: 6211 - TrueCrypt RIPEMD160 + XTS 512 bit (Iterations: 1999)

Speed.#3.........:    11512 H/s (87.74ms) @ Accel:256 Loops:1024 Thr:1 Vec:8

Hashmode: 13400 - KeePass 1 (AES/Twofish) and KeePass 2 (AES) (Iterations: 24569)

Speed.#3.........:     1388 H/s (61.36ms) @ Accel:256 Loops:1024 Thr:1 Vec:8

Hashmode: 6800 - LastPass + LastPass sniffed (Iterations: 499)

Speed.#3.........:   109.3 kH/s (71.71ms) @ Accel:1024 Loops:499 Thr:1 Vec:8

Hashmode: 11300 - Bitcoin/Litecoin wallet.dat (Iterations: 200459)

Speed.#3.........:      211 H/s (49.47ms) @ Accel:256 Loops:1024 Thr:1 Vec:4

Started: Sun Jun 21 07:56:51 2020

                                  
Stopped: Sun Jun 21 08:02:11 2020

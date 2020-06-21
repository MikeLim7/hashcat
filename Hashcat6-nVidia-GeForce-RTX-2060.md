GPU: nVidia GeForce RTX 2060

OS: Windows 10 x64 v2004


hashcat (v6.0.0) starting in benchmark mode...

Benchmarking uses hand-optimized kernel code by default.
You can use it in your cracking session by setting the -O option.
Note: Using optimized kernel code limits the maximum supported password length.
To disable the optimized kernel code in benchmark mode, use the -w option.

* Device #1: CUDA SDK Toolkit installation NOT detected.
             CUDA SDK Toolkit installation required for proper device support and utilization
             Falling back to OpenCL Runtime

* Device #1: WARNING! Kernel exec timeout is not disabled.
             This may cause "CL_OUT_OF_RESOURCES" or related errors.
             To disable the timeout, see: https://hashcat.net/q/timeoutpatch
This OpenCL driver has been marked as likely to fail kernel compilation or to produce false negatives.
You can use --force to override this, but do not report related errors.

OpenCL API (OpenCL 1.2 CUDA 11.0.186) - Platform #1 [NVIDIA Corporation]
========================================================================
* Device #1: GeForce RTX 2060, 5120/6144 MB (1536 MB allocatable), 30MCU

OpenCL API (OpenCL 2.1 ) - Platform #2 [Intel(R) Corporation]
=============================================================
* Device #2: Intel(R) HD Graphics 530, skipped
* Device #3: Intel(R) Core(TM) i7-6700K CPU @ 4.00GHz, skipped

Benchmark relevant options:
===========================
* --optimized-kernel-enable

Hashmode: 0 - MD5

Speed.#1.........: 24600.1 MH/s (81.50ms) @ Accel:64 Loops:1024 Thr:1024 Vec:8

Hashmode: 100 - SHA1

Speed.#1.........:  7818.4 MH/s (64.05ms) @ Accel:16 Loops:1024 Thr:1024 Vec:1

Hashmode: 1400 - SHA2-256

Speed.#1.........:  3306.3 MH/s (75.78ms) @ Accel:8 Loops:1024 Thr:1024 Vec:1

Hashmode: 1700 - SHA2-512

Speed.#1.........:   957.4 MH/s (65.39ms) @ Accel:16 Loops:128 Thr:1024 Vec:1

Hashmode: 22000 - WPA-PBKDF2-PMKID+EAPOL (Iterations: 4095)

Speed.#1.........:   392.9 kH/s (77.86ms) @ Accel:16 Loops:256 Thr:1024 Vec:1

Hashmode: 1000 - NTLM

Speed.#1.........: 43517.1 MH/s (45.91ms) @ Accel:64 Loops:1024 Thr:1024 Vec:8

Hashmode: 3000 - LM

Speed.#1.........: 22753.6 MH/s (43.74ms) @ Accel:512 Loops:1024 Thr:64 Vec:1

Hashmode: 5500 - NetNTLMv1 / NetNTLMv1+ESS

Speed.#1.........: 19816.2 MH/s (50.46ms) @ Accel:64 Loops:512 Thr:1024 Vec:2

Hashmode: 5600 - NetNTLMv2

Speed.#1.........:  1689.2 MH/s (74.14ms) @ Accel:8 Loops:512 Thr:1024 Vec:1

Hashmode: 1500 - descrypt, DES (Unix), Traditional DES

Speed.#1.........:   921.1 MH/s (67.77ms) @ Accel:32 Loops:1024 Thr:64 Vec:1

Hashmode: 500 - md5crypt, MD5 (Unix), Cisco-IOS $1$ (MD5) (Iterations: 1000)

Speed.#1.........: 10952.8 kH/s (86.16ms) @ Accel:32 Loops:1000 Thr:1024 Vec:1

Hashmode: 3200 - bcrypt $2*$, Blowfish (Unix) (Iterations: 32)

Speed.#1.........:    16518 H/s (38.58ms) @ Accel:2 Loops:32 Thr:11 Vec:1

Hashmode: 1800 - sha512crypt $6$, SHA512 (Unix) (Iterations: 5000)

Speed.#1.........:   163.7 kH/s (74.24ms) @ Accel:16 Loops:128 Thr:1024 Vec:1

Hashmode: 7500 - Kerberos 5, etype 23, AS-REQ Pre-Auth

Speed.#1.........:   296.9 MH/s (52.67ms) @ Accel:128 Loops:64 Thr:64 Vec:1

Hashmode: 13100 - Kerberos 5, etype 23, TGS-REP

Speed.#1.........:   297.2 MH/s (52.60ms) @ Accel:128 Loops:64 Thr:64 Vec:1

Hashmode: 15300 - DPAPI masterkey file v1 (Iterations: 23999)

Speed.#1.........:    66363 H/s (78.50ms) @ Accel:8 Loops:512 Thr:1024 Vec:1

Hashmode: 15900 - DPAPI masterkey file v2 (Iterations: 12899)

Speed.#1.........:    37109 H/s (63.37ms) @ Accel:2 Loops:512 Thr:1024 Vec:1

Hashmode: 7100 - macOS v10.8+ (PBKDF2-SHA512) (Iterations: 1023)

Speed.#1.........:   467.1 kH/s (43.10ms) @ Accel:2 Loops:511 Thr:1024 Vec:1

Hashmode: 11600 - 7-Zip (Iterations: 16384)

Speed.#1.........:   391.1 kH/s (74.00ms) @ Accel:4 Loops:4096 Thr:1024 Vec:1

Hashmode: 12500 - RAR3-hp (Iterations: 262144)

Speed.#1.........:    36269 H/s (52.71ms) @ Accel:1 Loops:16384 Thr:1024 Vec:1

Hashmode: 13000 - RAR5 (Iterations: 32799)

Speed.#1.........:    42270 H/s (87.80ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1

Hashmode: 6211 - TrueCrypt RIPEMD160 + XTS 512 bit (Iterations: 1999)

Speed.#1.........:   296.8 kH/s (95.32ms) @ Accel:8 Loops:256 Thr:1024 Vec:1

Hashmode: 13400 - KeePass 1 (AES/Twofish) and KeePass 2 (AES) (Iterations: 24569)

Speed.#1.........:    26120 H/s (195.83ms) @ Accel:4 Loops:1024 Thr:1024 Vec:1

Hashmode: 6800 - LastPass + LastPass sniffed (Iterations: 499)

Speed.#1.........:  2736.1 kH/s (86.44ms) @ Accel:8 Loops:499 Thr:1024 Vec:1

Hashmode: 11300 - Bitcoin/Litecoin wallet.dat (Iterations: 200459)

Speed.#1.........:     5120 H/s (61.05ms) @ Accel:8 Loops:256 Thr:1024 Vec:1

Started: Sun Jun 21 08:08:35 2020
                                  Stopped: Sun Jun 21 08:12:13 2020

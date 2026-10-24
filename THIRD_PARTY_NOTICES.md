# Third-party notices for this preservation copy

The original source files, copyright notices, and license text are preserved. This document supplements the original README; it does not relicense any component.

## PS5 Payload SDK

Original repository: https://github.com/ps5-payload-dev/sdk

Original credit: John Törnblom and contributors. The original README also credits artifacts originating in the PS5Dev/PS5SDK project. Unless a file states otherwise, the original README identifies SDK files as GPLv3-or-later; the original top-level `LICENSE` is included. Individual source-file notices remain authoritative.

## FreeBSD headers

The original README identifies `include/freebsd` as BSD-licensed material. Those files retain their individual copyright and license notices. Their distributed counterparts are in the binary SDK's `target/include` tree.

## LLVM C++ runtimes and headers

The original `libcxx.sh` pins LLVM 18.1.8 and builds libc++, libc++abi, and libunwind. The binary SDK includes LLVM-derived C++ headers and runtime archives, which retain their component-specific licensing. Supplemental original license texts from the `llvmorg-18.1.8` tag are included under `LICENSES/LLVM-18.1.8/`:

- `LICENSE-libcxx.txt`: https://github.com/llvm/llvm-project/blob/llvmorg-18.1.8/libcxx/LICENSE.TXT
- `LICENSE-libcxxabi.txt`: https://github.com/llvm/llvm-project/blob/llvmorg-18.1.8/libcxxabi/LICENSE.TXT
- `LICENSE-libunwind.txt`: https://github.com/llvm/llvm-project/blob/llvmorg-18.1.8/libunwind/LICENSE.TXT
- `LICENSE-LLVM.txt`: https://github.com/llvm/llvm-project/blob/llvmorg-18.1.8/llvm/LICENSE.TXT

The pinned external LLVM source distribution remains identified in the unchanged `libcxx.sh`; LLVM sources are not included in the original SDK source snapshot. This preservation copy does not claim third-party components as its own work.

Security Warnings
**********************

x86-64 Linux Only
-----------------------

There are [known bugs](https://github.com/scipr-lab/libsnark/issues/26) which
make proving keys generated on 64-bit systems unusable on 32-bit and big-endian
systems. It's unclear if a warning will be issued in this case, or if the
proving system will be silently compromised.


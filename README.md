# Use Debian CA trust-store for NSS
**Debian** package to resolve problem, where applications like **Firefox and Chrome** don't use system CA store, but use unconfigurable/static CA store in **libnss3**, see [https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=704180](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=704180).

> [!TIP]
> **Prepare package using (run in package root directory):**\
> dpkg-buildpackage

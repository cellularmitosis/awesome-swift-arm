# awesome-swift-arm
Everything I know about running Swift on ARM (Raspberry Pi, BeagleBone, etc)

# People

## William Dillon (@hpux735)

* https://twitter.com/hpux735
* https://github.com/hpux735

## Joe (@iachievedit)

* https://twitter.com/iachievedit
* https://github.com/iachievedit

### Articles

* Introducing Swift 3.0 (2016/2/16)
  * http://dev.iachieved.it/iachievedit/introducing-swift-3-0/
  * describes how he built swift 3.0 packages for ubuntu/x86_64

* Debian Packages for Swift on ARM (2015/12/22)
  * http://dev.iachieved.it/iachievedit/debian-packages-for-swift-on-arm/
  * describes how to use his repo for swift 2.2 packages on ubuntu/armhf

* Ubuntu Packages for Open Source Swift (2015/12/15)
  * http://dev.iachieved.it/iachievedit/ubuntu-packages-for-open-source-swift/
  * describes how to use his debian repo for swift 2.2 ubuntu/x86_64 packages

* Keeping up with Open Source Swift (2015/12/12)
  * http://dev.iachieved.it/iachievedit/keeping-up-with-open-source-swift/
  * describes how he built swift snapshot (2.2 at the time?) packages for ubuntu/x86_64

### github repos

* package-swift: A set of helper scripts for building and packaging Swift on Ubuntu Linux
  * https://github.com/iachievedit/package-swift

## Umberto Raimondi (@uraimo)

* https://twitter.com/uraimo
* https://github.com/uraimo

### Articles

* Swift 3.0 now available for all the ARMv6 RaspberryPi (1,Zero) (2016/3/10)
  * https://www.uraimo.com/2016/03/10/swift-3-available-on-armv6-raspberry-1-zero/
  * he built swift 3.0 for raspbian/armv6 and published a tarball on dropbox
    * https://www.dropbox.com/s/smk3ek5lfa8ae09/swift-2016-02-15.tar.gz

* Swift available for all the ARMv6 RaspberryPi (1,Zero) (2016/2/10)
  * https://www.uraimo.com/2016/02/10/swift-available-on-armv6-raspberry-1-zero/
  * he built swift 2.2 for raspbian/armv6 and published a tarball on dropbox
    * https://www.dropbox.com/s/he47c47bywm10nv/swift-armv6.tgz

# Other community blog posts / articles

* Swift on Raspberry Pi (2015/12/28)
  * http://blog.andrewmadsen.com/post/136137396480/swift-on-raspberry-pi
  * instructions for installing @iAchievedit's packages and writing hello world

# Relevant swift bugs

* SR-40: Port Swift to Linux on Raspberry Pi
  * https://bugs.swift.org/browse/SR-40

* SR-388: Swift REPL fails to launch on ARM
  * https://bugs.swift.org/browse/SR-388

# Relevant pull requests:

* 901: Support ARMv6 (original Raspberry Pi), ARMv7 bugfixes
  * https://github.com/apple/swift/pull/901

# Apple's swift CI server:

* https://ci.swift.org/view/Packages/

# swift build requirements:

* https://bugs.swift.org/browse/SR-40?focusedCommentId=10230&page=com.atlassian.jira.plugin.system.issuetabpanels:comment-tabpanel#comment-10230
  * "Building just LLVM and Clang requires more than 4 Gb, probably 8 Gb, IIRC. Building Swift requires 12 Gb if building with debug information (for the linking step)."

# ubuntu/14.04 on raspberry pi

* https://wiki.ubuntu.com/ARM/RaspberryPi
  * http://www.finnie.org/software/raspberrypi/

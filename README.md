| package names | des |
| :---        |    :---- |
| acl |访问控制列表（ACL）为文件系统提供了一个额外的、更灵活的许可机制。它是为协助UNIX文件权限而设计的。ACL允许你为任何用户或组赋予任何磁盘资源的权限。可以用``` tune2fs  -l /dev/xxx```命令查看是否开启了acl。更多信息请访问：https://wiki.archlinux.org/title/Access_Control_Lists。|
| advanceMAME | [advanceMAME(Multiple Arcade Machine Emulator) project](https://www.advancemame.it/)允许你用电视、街机显示器、PC显示器和LCD屏幕等视频硬件玩街机游戏。它们在GNU/Linux、Mac OS X、DOS和Windows中运行。|
| alsa-lib |[alsa(Advanced Linux Sound Architecture)-lib](https://github.com/alsa-project/alsa-lib)是一个库,用于连接Linux内核中的ALSA和使用插件系统的虚拟设备.ALSA为Linux操作系统提供音频和MIDI功能。|
| alsa-utils |[alsa-utils](https://github.com/alsa-project/alsa-utils)包含了ALSA项目的命令行工具。该软件包只能在安装了ALSA驱动和ALSA C库（alsa-lib）的情况下进行编译。|
| amiberry | [Amiberry](https://blitterstudio.com/amiberry/)是一个优化的Amiga模拟器，最初是为基于ARM的SoC（如Raspberry Pi）设计的，但现在也可用于macOS（包括Intel和Apple Silicon）和Linux x86-64，为你带来最高性能的Amiga仿真。无论是经典的A500、A1200、CD32还是配备了68040和显卡的高端机型，我们都能满足你的需求。代码是基于最新的WinUAE的核心仿真，但有些部分被剥离，并专门为低功率板进行了优化。此外，还有一些专门为Amiberry开发的功能，如支持WHDLoad、自定义事件、支持RetroArch映射等。<br><br> Amiga是Commodore公司在1985年推出的个人电脑系列.最初的型号是80年代中期的一些计算机之一，具有16或32位处理器，256KB或更多的内存，基于鼠标的图形用户界面，与以前的8位系统相比，图形和音频都有明显的改进。|
| attr | [attr](http://savannah.nongnu.org/projects/attr)为用户在XFS文件系统中为对象附加键值对附加到XFS文件系统中的对象。XFS是由Silicon Graphics, Inc在1993年创建的一个高性能64位日志文件系统.它从5.3版本开始,它是SGI的IRIX操作系统的默认文件系统。|
| autoconf | [Autoconf](https://www.gnu.org/software/autoconf/)是一个可扩展的M4宏包，它产生的shell脚本可以自动配置软件源代码包。这些脚本可以使软件包适应许多种类似UNIX的系统，而不需要用户手动干预。Autoconf通过一个模板文件为软件包创建配置脚本，该文件以M4宏调用的形式列出了软件包可以使用的操作系统特性。|
| autoconf-archive | [GNU Autoconf archive](https://github.com/autoconf-archive/autoconf-archive)是一个超过500个GNU Autoconf宏的集合，这些宏是由来自互联网上的友好支持者作为自由软件贡献的。这些宏中的每一个都可以被重新使用，而不会对生成的配置脚本的许可施加任何限制。特别是，它可以在为非自由软件设计的配置脚本中使用所有这些宏。这一政策对于自由软件基金会的项目来说是不寻常的。自由软件基金会坚信软件应该是自由的，而像GPL这样的软件许可证是专门为确保基于自由软件的衍生作品也必须是自由的而设计的。然而，在Autoconf的情况下，我们做了一个例外，因为Autoconf在软件开发工具链中处于如此关键的地位，尽可能广泛地提供这一工具的好处超过了一些作者可能选择将其用于专有软件的缺点。|
| automake | [GNU Automake](https://www.gnu.org/software/automake/) 是一个自动生成符合 GNU 编码标准Makefile.in文件的工具。Automake需要使用GNU Autoconf。|
| avahi | [Avahi](https://www.avahi.org/)是一个系统，它通过mDNS/DNS-SD协议套件促进本地网络的服务发现。这使你能够将你的笔记本电脑或计算机插入网络，并立即能够查看其他可以与你聊天的人，找到要打印的打印机或找到正在共享的文件。|
| bash | 著名的"bash".|
| bcm2835 |  Raspberry Pi的[c语言库](https://www.airspayce.com/mikem/bcm2835/)。|
| binutils | 著名的binutils.编译工具全家桶的重要组成部分。|
| bison | [Bison](https://www.gnu.org/software/bison/)是一个通用的分析器生成器，它可以将一个有注释的上下文自由语法转换为采用LALR(1)分析器表的确定性LR或广义LR（GLR）分析器。作为一个实验性的功能，Bison还可以生成IELR(1)或规范的LR(1)分析器表。一旦你熟练掌握了Bison，你就可以用它来开发各种语言分析器，从用于简单的桌面计算器到复杂的编程语言。|
| bluez5_utils | linux的蓝牙协议栈实现的相关工具。|
| boost | c++的一个重要[基础功能库](https://www.boost.org/)。|
| brcm-bt-firmware |博通的[蓝牙固件](https://github.com/winterheart/broadcom-bt-firmware)。 |
| brcmfmac_sdio-firmware-rpi |博通的一些[固件](https://github.com/LibreELEC/brcmfmac_sdio-firmware-rpi)，用于树梅派。|
| busybox | [BusyBox](https://busybox.net/)将许多常见的UNIX工具的微小版本整合到一个小的可执行文件中。它提供了大多数你通常在GNU fileutils、shellutils等中找到的实用程序的替换。BusyBox中的实用程序通常比其全功能的GNU表亲拥有更少的选项；然而，所包含的选项提供了预期的功能，其行为与GNU的同类程序非常相似。BusyBox为任何小型或嵌入式系统提供了一个相当完整的环境。|
| bzip2 | [bzip2](https://sourceware.org/bzip2/)是一个免费提供的、无专利的（见下文）、高质量的数据压缩器。它通常将文件压缩到现有最佳技术（PPM统计压缩器系列）的10%到15%之内，同时压缩速度是其两倍，解压速度是其六倍。|
| ca-certificates | 一种[数字证书](https://snapshot.debian.org/archive/debian/20211022T144903Z/pool/main/c/ca-certificates)，用于验证第三方的身份，并对你和上述第三方之间的数据进行加密。  证书颁发机构（ca），是一个受信任的实体（如Comodo），它颁发数字文件，可以像数字护照一样使用。当我们去一个网站（如google.com）时，谷歌会向你发送他们的证书。我们的浏览器对ca证书做了一个小魔术，并验证或拒绝谷歌提供的证书。  它也被用来在你和谷歌之间来回处理数据，使其在传输过程中被加密。这有助于阻止人们观察你的数据在你和谷歌之间的移动。 它还可以帮助你确定是否有人试图通过假装成谷歌、你的银行或其他网站来诈骗.虽然不是万无一失，但到目前为止，它比几乎任何人都可以阅读的纯文本要安全得多。|
| c-ares | [c-ares](https://c-ares.org/)是一个用于异步DNS请求（包括名称解析）的C库。|
| cifs-utils | [cifs-util](https://wiki.samba.org/index.php/LinuxCIFS_utils)软件包提供了一种在Linux系统上挂载SMB/CIFS共享的方法。
| cmake | [c/c++构建工具](https://cmake.org/)。|
| cmocka | [c单元测试工具](https://cmocka.org/)。 |
| crda | [crda(central regulatory domain agent)](https://git.kernel.org/pub/scm/linux/kernel/git/mcgrof/crda.git/),它的作用只有一个:告诉Linux内核要对802.11执行哪些监管规则。  IEEE 802.11是IEEE 802系列局域网技术标准的一部分,规定了实现无线局域网计算机通信的一套媒体访问控制和物理层协议。|
| db9_gpio_rpi |[db9_gpio_rpi](https://github.com/marqs85/db9_gpio_rpi)是一个驱动（Linux内核模块），用于连接到Raspberry Pi的GPIO的DB9操纵杆和游戏手柄。 |
| dbus |[D-Bus](https://www.freedesktop.org/wiki/Software/dbus/)是一个消息总线系统，是应用程序之间相互交谈的一种简单方式。除了进程间的通信，D-Bus还有助于协调进程的生命周期；它使编码 "单实例 "应用程序或守护程序变得简单可靠，并在需要其服务时按需启动应用程序和守护程序。 |
| dbus-cpp |dbus的[c++ api接口](https://dbus-cplusplus.sourceforge.net/)。 |
| dbus-python |dbus的[python api接口](https://dbus.freedesktop.org/doc/dbus-python//)。  |
| dbus-triggerd |[dbus-triggerd](http://rg42.org/gitweb/?p=dbustriggerd.git)在收到一个给定的dbus信号时触发shell. |
| dejavu |[DejaVu字体](https://github.com/dejavu-fonts/dejavu-fonts)是一个基于Bitstream Vera字体的字体家族。其目的是在保持原有外观和感觉的同时，提供更广泛的字符。 |
| dhcpcd |[dhcpcd](https://roy.marples.name/projects/dhcpcd/)，一个DHCP和DHCPv6客户端。它也是一个IPv4LL（又称ZeroConf）客户端。通俗地说，dhcpcd在你的机器上运行，默默地配置你的计算机，使其在连接的网络上工作，没有任何麻烦，而且大部分情况下无需配置。 |
| diffutils |[GNU Diffutils](https://www.gnu.org/software/diffutils/)是一个由几个与寻找文件间差异有关的程序组成的软件包. |
| dos2unix | windows, Unix, MacOS之间的文件换行[格式转化](https://waterlan.home.xs4all.nl/dos2unix.html)。|
| dosbox |[DOSBox](https://www.dosbox.com/)是一个使用SDL库的DOS模拟器，这使得DOSBox非常容易移植到不同的平台。 |
| dosfstools |[dosfstools](https://github.com/dosfstools/dosfstools)由mkfs.fat、fsck.fat和fatlabel程序组成，用于创建、检查和标记FAT系列的文件系统。 |
| dropbear |[Dropbear](https://matt.ucc.asn.au/dropbear/dropbear.html)是一个相对较小的SSH服务器和客户端。它运行在各种unix平台上。Dropbear是开放源码软件，在MIT风格的许可证下发布。Dropbear对 "嵌入式 "的Linux（或其他Unix）系统特别有用，如无线路由器。 |
| duckstation |[DuckStation](https://www.duckstation.org/)是一个PS1模拟器，旨在实现最佳的准确性和游戏支持。|
| e2fsprogs |[e2fsprogs](https://e2fsprogs.sourceforge.net/)提供了用于ext2文件系统的文件系统实用程序。它也支持ext3和ext4文件系统。 |
| eepromutils |用于树梅派的[EEPROM烧写工具](https://github.com/raspberrypi/hats/tree/master/eepromutils)。 EEPROM（也称为E2PROM）是电可擦除可编程只读存储器的缩写，是一种用于计算机的非易失性存储器，通过允许个别字节被擦除和重新编程来存储相对少量的数据。|
| elfutils |[elfutils](https://sourceware.org/elfutils/)是一个实用程序和库的集合，用于读取、创建和修改ELF二进制文件，查找和处理DWARF调试数据、符号、线程状态和GNU/Linux上进程和核心文件的堆栈跟踪。 |
| eudev |eudev是Gentoo的udev分支，udev是systemd用于Linux内核的设备文件管理器。它管理/dev中的设备节点，并在添加或删除设备时处理所有用户空间的操作。  eudev的目标是获得与现有软件更好的兼容性，如OpenRC, Upstart, 老的Linux内核、各种工具链，以及其他任何udev需要的东西。 |
| evtest |输入设备事件监控和查询[工具](https://gitlab.freedesktop.org/libevdev/evtest). |
| exfat |用于Unix-like系统的[exfat文件系统](https://github.com/relan/exfat)。 |
| exfat-utils |用于Unix-like系统的[exfat文件系统实用工具](https://github.com/relan/exfat)。 |
| expat |[expat](https://libexpat.github.io/)是一个xml语法解析库。 |
| expect |[Expectaa是一个用于自动化交互式应用程序的工具，如telnet、ftp、passwd、fsck、rlogin、tip等。Expect对于测试这些相同的应用程序也很有用。|
| faad2 |Freeware Advanced Audio (AAC)[解码器](https://github.com/knik0/faad2)。|
| fakeroot |[fakeroot](https://wiki.debian.org/FakeRoot)提供一个假的root环境，以消除在构建软件包时成为root的需要。 |
| fbdump |[fbdump](https://www.rcdrummond.net/fbdump)是一个简单的工具，它捕捉Linux帧缓冲器设备的可见部分的内容，并将其作为PPM文件写入标准输出。换句话说，它对在帧缓冲器上运行的任何东西进行截图。 |
| fbgrab | [FBGrab](https://github.com/GunnarMonell/fbgrab)是一个帧缓冲区截图程序，捕捉Linux的帧缓冲区并将其转换为png图片。|
| fbv | [fbv(FrameBuffer Viewer)](https://github.com/smokku/fbv)是一个简单的程序，用于查看Linux帧缓冲设备上的图片。|
| ffmpeg |[ffmpeg](https://ffmpeg.org/)是一个完整的、跨平台的音频和视频录制、转换和流媒体解决方案。 |
| flac |[FLAC](https://xiph.org/flac/)是Free Lossless Audio Codec的缩写，是一种类似于MP3的音频格式，但却是无损的，这意味着音频在FLAC中被压缩而不会有任何质量上的损失。这类似于Zip的工作原理，除了FLAC，你会得到更好的压缩，因为它是专门为音频设计的，你可以在你喜欢的播放器（或你的汽车或家庭音响，见支持的设备）播放压缩的FLAC文件. |
| flatbuffers |[FlatBuffers](https://google.github.io/flatbuffers/)是一个高效的跨平台序列化库，适用于C++、C#、C、Go、Java、Kotlin、JavaScript、Lobster、Lua、TypeScript、PHP、Python、Rust和Swift。它最初是在谷歌创建的，用于游戏开发和其他性能关键型应用。 | 
| flex |[flex](https://github.com/westes/flex)：快速词法分析器生成器。 |
| fluidsynth |FluidSynth是一个跨平台的实时软件音频合成器，基于Soundfont 2规范。 |
| fmt |[fmt](https://github.com/fmtlib/fmt/)是一个开源的格式化库，为C语言的stdio和C++的iostreams提供了一个快速和安全的替代品. |
| fontconfig |[Fontconfig](https://www.freedesktop.org/wiki/Software/fontconfig/)是一个自由软件程序库，旨在为其他程序提供配置字体的功能。 |
| freetype |[FreeType](https://freetype.org/)用于渲染字体。 |
| fstrcmp |[fstrcmp](https://fstrcmp.sourceforge.net/)项目提供了一个库，用来对字符串和字节数组进行模糊比较，包括多字节的字符字符串。 |
| gamecon_gpio_rpi |[gamecon_gpio_rpi](https://github.com/marqs85/gamecon_gpio_rpi)是一个Linux内核模块，可以将各种复古游戏手柄与Raspberry Pi的GPIO连接起来。 |
| gawk |[awk](https://www.gnu.org/software/gawk/)工具解释了一种特殊用途的编程语言，使得只用几行代码就可以处理简单的数据格式化工作。 |
| gcc | 著名的"[gcc](https://gcc.gnu.org/)". |
| genimage |[genimage](https://github.com/pengutronix/genimage)是一个从给定的根文件系统树中生成多个文件系统和闪存/磁盘镜像的工具。genimage打算在fakeroot环境中运行。它还支持从不同的文件系统镜像和文件中创建闪存/磁盘镜像。 |
| gesftpserver | [sftp](https://www.greenend.org.uk/rjk/sftpserver/)服务器。|
| gettext-tiny |[gettext-tiny](https://github.com/sabotage-linux/gettext-tiny)为GNU gettext套件中的典型工具提供了轻量级的替换，GNU gettext套件非常臃肿，并且需要大量的时间来构建（在慢速设备上大约需要一个小时）。最引人注目的组件是msgfmt，用于从.po格式的文本输入文件中创建.mo格式的二进制翻译文件。  GNU gettext 实用程序是一套工具，它提供了一个框架来帮助其他 GNU 包产生多语言（汉语、日语、法语等等）信息。 |
| giflib |[gif动图库](https://giflib.sourceforge.net/)。 |
| glibc |[GNU C库项目](https://www.gnu.org/software/libc/)为GNU系统和GNU/Linux系统，以及许多其他使用Linux作为内核的系统提供核心库。这些库提供了关键的API，包括ISO C11、POSIX.1-2008、BSD、操作系统专用API等。这些API包括诸如open、read、write、malloc、printf、getaddrinfo、dlopen、pthread_create、crypt、login、exit等基础性设施。 |
| gmp |[GMP](https://gmplib.org/)是一个免费的任意精度算术库，对有符号整数、有理数和浮点数进行运算。除了GMP运行的机器中的可用内存所隐含的精度外，对精度没有实际限制。GMP有丰富的函数集，而且这些函数有一个常规的接口。 |
| gnutls |[GnuTLS](https://www.gnutls.org/)是一个安全通信库，实现了SSL、TLS和DTLS协议及其周边技术。它提供了一个简单的C语言应用编程接口（API）来访问安全通信协议，以及解析和编写X.509、PKCS #12和其他必要结构的API。 |
| gobject-introspection |[GObject](https://gi.readthedocs.io/)是C库（使用GObject）和语言绑定之间的一个中间件层。除了实际的本地C库之外，C库可以在编译时被扫描并生成元数据文件。然后，语言绑定可以读取这些元数据，并自动提供绑定，以调用到C库中。 |
| gperf |[GNU gperf](https://www.gnu.org/software/gperf/)是一个完美的哈希函数发生器。对于一个给定的字符串列表，它以C或C++代码的形式产生一个哈希函数和哈希表，用于根据输入的字符串查询一个值。哈希函数是完美的，这意味着哈希表没有碰撞，而且哈希表的查找只需要进行单一的字符串比较。 |
| gsplus |[GSplus](https://apple2.gs/)是一个苹果IIgs模拟器。 |
| guichan | [Guichan](https://github.com/wheybags/guichan)是一个为游戏设计的C++ GUI库。|
| harfbuzz |[HarfBuzz](https://github.com/harfbuzz/harfbuzz)是一个文本塑形引擎。它主要支持OpenType，但也支持Apple Advanced Typography。HarfBuzz被用于Android、Chrome、ChromeOS、Firefox、GNOME、GTK+、KDE、LibreOffice、OpenJDK、PlayStation、Qt、XeTeX和其他地方。 |
| hatari |[Hatari](https://hatari.tuxfamily.org/)是一个Atari ST/STE/TT/Falcon模拟器，用于GNU/Linux、BSD、Mac OS X、Windows和其他SDL库支持的系统。 |
| heimdal |支持多个https验证协议的[库](https://github.com/heimdal/heimdal)。 |
| hid-nintendo |任天堂手柄的[驱动](https://github.com/nicman23/dkms-hid-nintendo)。 |
| htop |[进程查看器](https://htop.dev/)。 |
| hypseus |[hypseus](https://github.com/DirtBagXon/hypseus-singe)一个在PC、Mac或Raspberry Pi上播放激光唱片街机游戏的模拟器。 |
| i2c-tools |[i2c-tools](https://i2c.wiki.kernel.org/index.php/I2C_Tools#I2C_Tools_for_Linux)软件包包含了一套用于Linux的I2C工具：一个总线探测工具、一个芯片跳线、寄存器级的SMBus访问助手、EEPROM解码脚本、EEPROM编程工具和一个用于SMBus访问的python模块。所有版本的Linux都被支持，只要内核中包含I2C支持。 |
| icu |[International Components for Unicode](https://icu.unicode.org/)是一个由成熟的C/C++和Java库组成的开源项目，用于支持Unicode、软件国际化和软件全球化。ICU可广泛移植到许多操作系统和环境中。 |
| isl |[isl](https://libisl.sourceforge.io/)是一个库，用于操作由线性约束条件限定的整数点的集合和关系。 |
| iw |[iw](https://www.linuxfromscratch.org/blfs/view/svn/basicnet/iw.html)是一个新的基于nl80211的无线设备CLI配置工具。它支持最近添加到内核的所有新驱动程序。 |
| jimtcl |[Jim](https://github.com/msteveb/jimtcl)是一个小规模的Tcl编程语言的实现。|
| joycond |[joycond](https://github.com/DanielOgorchock/joycond)是一个linux守护程序，它使用hid-nintendo（以前称为hid-joycon）提供的evdev设备来实现joycon配对。 |
| jpeg-turbo |[libjpeg-turbo](https://libjpeg-turbo.org/)是一个JPEG图像编解码器，它使用SIMD指令（MMX，SSE2，AVX2，Neon，AltiVec）来加速x86，x86-64，Arm和PowerPC系统上的基线JPEG压缩和解压缩，以及x86，x86-64和Arm系统上的渐进JPEG压缩。 |
| jsoncpp |[JsonCpp](https://github.com/open-source-parsers/jsoncpp)是一个C++库，允许操作JSON值，包括序列化和反序列化到字符串和从字符串。它还可以在反序列化/序列化步骤中保留现有的注释，使其成为存储用户输入文件的方便格式。 |
| json-for-modern-cpp | [另一个c++ json库](https://github.com/nlohmann/json)。 |
| jstest2 |[sdl-jstest和sdl2-jstest](https://gitlab.com/sdl-jstest/sdl-jstest)是简单的程序，可以让你找出系统中检测到的SDL或SDL2的操纵杆，它们各自有多少轴、按钮、帽子和球。它们还可以让你通过显示它们发送的事件或显示它们当前的按钮、轴、帽子或球的状态来测试操纵杆。如果你想测试你的SDL_LINUX_JOYSTICK配置，sdl-jstest就特别有用。 |
| kbd |[kbd](https://kbd-project.org/)项目包含用于管理Linux控制台（Linux控制台、虚拟终端、键盘等）的实用程序--主要是加载控制台字体和键盘映射。这些实用程序使用内核接口来加载键盘. |
| kernelfirmwares |[kernelfirmwares](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/)a是一个与Linux内核一起分发的软件包，其中包含某些硬件设备的部分或全部功能所需的固件二进制代码块。这些二进制包通常是专有的，因为一些硬件制造商不发布构建固件本身所需的源代码。 |
| kmod |[kmod](https://mirrors.edge.kernel.org/pub/linux/utils/kernel/kmod/)是一套用于插入、加载和删除内核模块的Linux程序。|
| kmsgrab |[kmsgrab](http://underpop.online.fr/f/ffmpeg/help/kmsgrab.htm.gz)捕获与指定的CRTC或plane相关的KMS扫描出帧缓冲区，作为一个DRM对象，可以传递给其他硬件函数。 |
| kodi | [Kodi](https://github.com/xbmc/xbmc)是一个获奖的自由和开源软件媒体播放器和数字媒体的娱乐中心。可作为安卓、Linux、BSD、macOS、iOS、tvOS和Windows操作系统的本地应用程序，Kodi在大多数常见的处理器架构上运行。|
| kodi-audiodecoder-modplug |
| kodi-audiodecoder-nosefart |
| kodi-audiodecoder-sidplay |
| kodi-audiodecoder-snesapu |
| kodi-audiodecoder-stsound |
| kodi-audiodecoder-timidity |
| kodi-audiodecoder-vgmstream |
| kodi-audioencoder-flac |
| kodi-audioencoder-lame |
| kodi-audioencoder-vorbis |
| kodi-audioencoder-wav |
| kodi-inputstream-adaptive |
| kodi-inputstream-ffmpegdirect |
| kodi-inputstream-rtmp |
| kodi-jsonschemabuilder |
| kodi-peripheral-joystick |
| kodi-peripheral-xarcade |
| kodi-plugin-video-netflix |
| kodi-plugin-video-twitch |
| kodi-plugin-video-youtube |
| kodi-pvr-argustv |
| kodi-pvr-dvblink |
| kodi-pvr-dvbviewer |
| kodi-pvr-filmon |
| kodi-pvr-hdhomerun |
| kodi-pvr-hts |
| kodi-pvr-iptvsimple |
| kodi-pvr-mediaportal-tvserver |
| kodi-pvr-mythtv |
| kodi-pvr-nextpvr |
| kodi-pvr-njoy |
| kodi-pvr-octonet |
| kodi-pvr-pctv |
| kodi-pvr-plutotv |
| kodi-pvr-stalker |
| kodi-pvr-vbox |
| kodi-pvr-vdr-vnsi |
| kodi-pvr-vuplus |
| kodi-pvr-waipu |
| kodi-pvr-wmc |
| kodi-pvr-zattoo |
| kodi-resource-language-de_de |
| kodi-resource-language-es_es |
| kodi-resource-language-eu_es |
| kodi-resource-language-fr_fr |
| kodi-resource-language-it_it |
| kodi-resource-language-pt_br |
| kodi-resource-language-sv_se |
| kodi-resource-language-tr_tr |
| kodi-resource-language-zh_cn |
| kodi-script-module-addon-signals |
| kodi-script-module-chardet |
| kodi-script-module-future |
| kodi-script-module-idna |
| kodi-script-module-inputstreamhelper |
| kodi-script-module-myconnpy |
| kodi-script-module-python-twitch |
| kodi-script-module-requests |
| kodi-script-module-six |
| kodi-script.module.t0mm0.common |
| kodi-script-module-urllib3 |
| kodi-skin-confluence-480 |
| kodi-texturepacker |
| lame |[LAME](https://lame.sourceforge.io/)是一个高质量的MPEG音频层III（MP3）编码器，在LGPL下授权。 |
| lba-finder | [lba-finder](https://gitlab.com/recalbox/lba-finder)返回MBR磁盘或镜像的第一个分区的LBA（逻辑块寻址）。|
| lcms2 |[Little cms](https://sourceforge.net/projects/lcms/)是一个色彩管理库。在ICC配置文件之间实现快速转换。它专注于速度，并可在多个平台上移植（MIT许可）。| 
| libao |[跨平台音频库](https://ftp.osuosl.org/pub/xiph/releases/ao/)。 |
| libass |[libass](https://github.com/libass/libass)是一个用于ASS/SSA（Advanced Substation Alpha/Substation Alpha）字幕格式的便携式字幕渲染器。它主要与VSFilter兼容。 |
| libcapsimage |
| libcdio | https://www.gnu.org/software/libcdio/|
| libcec | https://github.com/Pulse-Eight/libcec |
| libconfuse | libConfuse是一个用C语言编写的配置文件解析器库，它支持分段和（列表）值，以及其他功能，如单/双引号字符串、环境变量扩展、函数和嵌套的包含语句。值可以是字符串、整数、浮点数、布尔运算和部分。https://github.com/libconfuse/libconfuse |
| libcrossguid |https://github.com/graeme-hill/crossguid |
| libcurl |libcurl是一个免费且易于使用的客户端URL传输库，支持DICT, FILE, FTP, FTPS, GOPHER, GOPHERS, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, MQTT, POP3, POP3S, RTMP, RTMPS, RTSP, SCP, SFTP, SMB, SMBS, SMTP, SMTPS, TELNET 和 TFTP。libcurl支持SSL证书、HTTP POST、HTTP PUT、FTP上传、基于HTTP表单的上传、代理、HTTP/2、HTTP/3、cookies、用户+密码认证（Basic、Digest、NTLM、Negotiate、Kerberos）、文件传输恢复、http代理隧道等等。https://curl.se/libcurl/ |
| libdaemon | libdaemon是一个轻量级的C语言库，它简化了UNIX守护程序的编写。http://0pointer.de/lennart/projects/libdaemon/#overview|
| libdrm |用户态使用drm的库。https://dri.freedesktop.org/libdrm/ |
| libenet |ENet的目的是在UDP（用户数据报协议）之上提供一个相对较薄、简单和强大的网络通信层。它提供的主要功能是可选的可靠、有序的数据包交付。http://enet.bespin.org/|
| libevdev | libevdev是一个针对evdev设备的包装库。它将处理evdev设备时的常见任务移到一个库中，并为调用者提供一个库接口，从而避免了错误的ioctls等。https://www.freedesktop.org/wiki/Software/libevdev/|
| libevent |libevent API提供了一种机制，当文件描述符上发生特定事件或达到超时后执行回调函数。此外，libevent还支持由于信号或常规超时而产生的回调。https://libevent.org/ |
| libffi | 有些程序在编译时可能不知道要向一个函数传递什么参数。例如，一个解释器可能在运行时被告知用于调用某个函数的参数数量和类型。Libffi可以用在这样的程序中，提供一个从解释器程序到编译代码的桥梁。https://sourceware.org/libffi/|
| libfreeimage |FreeImage是一个开源库项目，为那些希望支持流行的图形图像格式，如PNG、BMP、JPEG、TIFF和其他当今多媒体应用所需要的图像格式的开发者提供服务。FreeImage易于使用，速度快，多线程安全，与所有32位或64位的Windows版本兼容，并且跨平台（与Linux和Mac OS X兼容）。https://freeimage.sourceforge.io/| 
| libfribidi | 阻止自由软件在中东地区普及的一个缺失环节是缺乏对阿拉伯和希伯来字母的支持。为了有适当的阿拉伯文和希伯来文支持，需要实现bidi算法。我们希望这个库能在中东国家刺激更多的自由软件。 https://github.com/fribidi/fribidi| 
| libfuse |FUSE（用户空间的文件系统）是用户空间程序向Linux内核输出文件系统的接口。FUSE项目由两部分组成：fuse内核模块（维护在常规内核仓库中）和libfuse用户空间库（维护在该仓库中）。libfuse提供了与FUSE内核模块通信的参考实现。FUSE 文件系统通常被实现为一个与 libfuse 链接的独立应用程序。 libfuse 提供了挂载文件系统、卸载文件系统、从内核读取请求以及发送响应的功能。libfuse 提供了两个 API：一个 "高级 "同步 API，以及一个 "低级 "异步 API。在这两种情况下，从内核传入的请求都是通过回调传递给主程序的。当使用高级API时，回调可以使用文件名和路径而不是节点，当回调函数返回时，请求的处理就结束了。当使用低级别的API时，回调必须使用inodes，并且必须使用一组单独的API函数来明确发送响应。https://github.com/libfuse/libfuse|
| libgcrypt |Libgcrypt是一个通用的加密库.https://gnupg.org/software/libgcrypt/index.html | 
| libglib2 |GLib 是一款包含许多有用的处理各类数据结构的 C 例程的软件库，例如处理树、散列、列表和字符串。作为有用的通用 C 库，它为 GTK+、GIMP 和 GNOME 等许多项目所使用。https://download.gnome.org/sources/glib/|
| libgpg-error |Libgpg-error是一个小型库，它最初为所有GnuPG组件定义了常见的错误值。 |
| libhdhomerun |https://github.com/Silicondust/libhdhomerun|
| libidn | Libidn的目的是对国际化的域名进行编码和解码。https://www.gnu.org/software/libidn/|
| libinput |libinput是一个在Wayland合成器中处理输入设备的库，并提供一个通用的X.Org输入驱动。它提供了设备检测、设备处理、输入设备事件处理和抽象，从而最大限度地减少合成器需要的自定义输入代码量，以提供用户期望的通用功能集。https://www.freedesktop.org/wiki/Software/libinput/| 
| libjpeg |https://libjpeg.sourceforge.net/| 
| liblcf |liblcf是一个处理RPG Maker 2000和2003游戏数据的库。它可以读取和写入LCF和XML文件。|
| liblockfile | https://github.com/miquels/liblockfile|
| libmad | https://www.underbit.com/products/mad/|
| libmicrohttpd |libmicrohttpd可以使运行一个 HTTP 服务器作为另一个应用程序的一部分变得容易。https://www.gnu.org/software/libmicrohttpd/ |
| libmodplug |https://modplug-xmms.sourceforge.net|
| libmpeg2 |https://libmpeg2.sourceforge.io/ |
| libnfs | https://github.com/sahlberg/libnfs|
| libnl |libnl套件是一个库的集合，为基于netlink协议的Linux内核接口提供API。|
| libnspr | https://firefox-source-docs.mozilla.org/nspr/index.html|
| libnss | 网络安全服务（NSS）是一套库，旨在支持跨平台的安全客户端和服务器应用程序的开发。https://firefox-source-docs.mozilla.org/security/nss/index.html|
| libogg | https://xiph.org/ogg/|
| libopenssl |OpenSSL是一个强大的、商业级的、全功能的开源工具包，用于传输层安全（TLS）协议，以前被称为安全套接字层（SSL）协议。该协议的实现是基于一个全强度的通用加密库，它也可以独立使用。https://github.com/openssl/openssl |
| libpcap |libpcap是一个独立于系统的用户级数据包捕获接口。libpcap提供了一个可移植的低级网络监控框架。其应用包括网络统计收集、安全监控、网络调试等。由于几乎每个系统供应商都为数据包捕获提供了不同的接口，而且我们已经开发了几个需要这种功能的工具，所以我们创建了这个与系统无关的API，以方便移植，并减轻每个应用程序中对几个与系统相关的数据包捕获模块的需要。https://github.com/the-tcpdump-group/libpcap|
| libplatform | 这个库为其他库提供了特定的平台支持，并被libCEC和Kodi的二进制附加组件所使用。|
| libplist |一个小型的可移植C语言库，用于处理二进制或XML格式的Apple Property List文件。https://github.com/libimobiledevice/libplist |
| libpng |http://www.libpng.org/pub/png/libpng.html|
| libpthread-stubs |libpthread-stubs软件包为libc中没有提供的或默认提供的pthread函数提供了弱的别名。这对于那些依靠 pthread stubs 来选择使用 pthreads 的库是非常有用的。在Linux上，所有必要的pthread函数都是可用的，所以这个包只是一个占位符。|
| libretro-2048 |
| libretro-81 |
| libretro-a5200 |
| libretro-atari800 |
| libretro-beetle-lynx |
| libretro-beetle-ngp |
| libretro-beetle-pce-fast |
| libretro-beetle-pcfx |
| libretro-beetle-psx |
| libretro-beetle-supergrafx |
| libretro-beetle-vb |
| libretro-beetle-wswan |
| libretro-bk-emulator |
| libretro-bluemsx |
| libretro-bsnes |
| libretro-bsnes-hd |
| libretro-cannonball |
| libretro-cap32 |
| libretro-cdi2015 |
| libretro-cheats |
| libretro-crocods |
| libretro-dinothawr |
| libretro-dosbox-pure |
| libretro-easyrpg |
| libretro-ecwolf |
| libretro-emuscv |
| libretro-fbneo |
| libretro-fceumm |
| libretro-fceunext |
| libretro-flycast |
| libretro-fmsx |
| libretro-freechaf |
| libretro-freeintv |
| libretro-fuse |
| libretro-gambatte |
| libretro-gearcoleco |
| libretro-gearsystem |
| libretro-genesisplusgx |
| libretro-genesisplusgxwide |
| libretro-gong |
| libretro-gpsp |
| libretro-gw |
| libretro-handy |
| libretro-hatari |
| libretro-imageviewer |
| libretro-lowres-nx |
| libretro-lutro |
| libretro-mame2000 |
| libretro-mame2003 |
| libretro-mame2003-plus |
| libretro-mame2010 |
| libretro-mame2015 |
| libretro-mesen |
| libretro-mesen-s |
| libretro-meteor |
| libretro-mgba |
| libretro-minivmac |
| libretro-mrboom |
| libretro-mu |
| libretro-mupen64plus-nx |
| libretro-neocd |
| libretro-nestopia |
| libretro-np2kai |
| libretro-nxengine |
| libretro-o2em |
| libretro-opera |
| libretro-parallel-n64 |
| libretro-pcsx_rearmed |
| libretro-picodrive |
| libretro-pokemini |
| libretro-potator |
| libretro-ppsspp |
| libretro-prboom |
| libretro-prosystem |
| libretro-px68k |
| libretro-quasi88 |
| libretro-quicknes |
| libretro-race |
| libretro-reminiscence |
| libretro-retro8 |
| libretro-sameboy |
| libretro-sameduck |
| libretro-snes9x |
| libretro-snes9x2002 |
| libretro-snes9x2005 |
| libretro-snes9x2010 |
| libretro-stella |
| libretro-swanstation |
| libretro-tgbdual |
| libretro-theodore |
| libretro-tic80 |
| libretro-tyrquake |
| libretro-uae |
| libretro-uae4arm |
| libretro-uzem |
| libretro-vecx |
| libretro-vice |
| libretro-virtualjaguar |
| libretro-vitaquake2 |
| libretro-xmil |
| libretro-xrick |
| libretro-yabasanshiro |
| libshairplay |AirPlay server.https://github.com/juhovh/shairplay |
| libsidplay2 | https://sidplay2.sourceforge.net/ |
| libsndfile |libsndfile是一个C语言库，用于读写包含采样音频数据的文件。https://github.com/libsndfile/libsndfile|
| libtasn1 | 这份文件描述了Libtasn1库，它提供了抽象语法符号一（ASN.1，由X.680 ITU-T建议规定）解析和结构管理，以及区分编码规则（DER，根据X.690）编码和解码功能。https://www.gnu.org/software/libtasn1/manual/libtasn1.html|
| libtheora | https://www.theora.org/doc/libtheora-1.0/index.html.|
| libtirpc | https://sourceforge.net/projects/libtirpc/.|
| libtool | 著名的"libtool"，它与autoconf, automake一起构成了gnu下常用的构建系统。 https://www.gnu.org/software/libtool/ |
| libunistring | unicode的字符串处理库。https://www.gnu.org/software/libunistring/|
| libusb | https://libusb.info/ |
| libusb-compat |https://github.com/libusb/libusb-compat-0.1|
| libuv | libuv是一个多平台支持库，专注于异步I/O。http://docs.libuv.org/en/v1.x/ |
| libvorbis | Ogg Vorbis是一种完全开放的、非专有的、无专利和版权的、通用的压缩音频格式，适用于中高质（8kHz-48.0kHz，16+比特，复音）音频和音乐，固定和可变比特率为16-128kbps/channel。这使Vorbis与MPEG-4（AAC）等音频表现形式处于同一竞争级别，与MPEG-1/2音频层3、MPEG-4音频（TwinVQ）、WMA和PAC类似，但性能更高。https://xiph.org/vorbis/|
| libvpx | https://www.webmproject.org/code/|
| libwebsockets | Libwebsockets（LWS）是一个灵活的、轻量级的纯C语言库，使用非阻塞事件循环，以很小的占用空间轻松实现现代网络协议。https://libwebsockets.org/|
| libxcb | https://xcb.freedesktop.org/| 
| libxkbcommon | xkbcommon是一个用于处理键盘描述的库，包括从磁盘加载它们，解析它们和处理它们的状态。它主要用于客户端工具包、窗口系统和其他系统应用。https://xkbcommon.org/|
| libxml2 | https://github.com/GNOME/libxml2 |
| libxmp-lite | https://github.com/libxmp/libxmp |
| libxslt |http://xmlsoft.org/libxslt/tutorial/libxslttutorial.html |
| libzip |https://libzip.org/|
| libzlib |zlib被设计成一个免费的、通用的、无法律约束的--也就是说，不受任何专利保护的--无损数据压缩库，几乎可以在任何计算机硬件和操作系统上使用。zlib数据格式本身是可以跨平台移植的。与Unix compress(1)和GIF图像格式中使用的LZW压缩方法不同，目前在zlib中使用的压缩方法基本上不会扩展数据。(在极端情况下，LZW可以使文件大小增加两倍或三倍。)zlib的内存占用也是独立于输入数据的，如果有必要，可以在压缩中付出一些代价来减少。https://zlib.net/|
| linapple-pie | https://github.com/dabonetn/linapple-pie |
| linux | https://www.kernel.org | 
| linuxconsoletools | https://slackbuilds.org/repository/14.2/system/linuxconsoletools/ |
| lirc-tools |LIRC是一个软件包，允许你解码和发送许多（但不是全部）常用遥控器的红外线信号。https://www.lirc.org/ |
| lockfile-progs | https://linux.die.net/man/1/lockfile-progs |
| lz4 | LZ4是无损压缩算法，每核提供的压缩速度大于500MB/s，可在多核CPU上扩展。它有一个极快的解码器，每核速度为多GB/s，通常在多核系统上达到RAM的速度限制。https://github.com/lz4/lz4 |
| lzip | Lzip是一个无损数据压缩器，其用户界面类似于gzip或bzip2的界面。Lzip使用 "Lempel-Ziv-Markov chain-Algorithm"（LZMA）流格式的简化形式，并提供一个3因素完整性检查，以最大限度地提高互操作性和优化安全性。Lzip的压缩速度与gzip差不多（lzip -0），或对大多数文件的压缩速度超过bzip2（lzip -9）。解压速度介于 gzip 和 bzip2 之间。从数据恢复的角度来看，Lzip比gzip和bzip2更好。Lzip 是经过精心设计、编写和测试的，以取代 gzip 和 bzip2，成为类似 unix 系统的标准通用压缩格式。https://www.nongnu.org/lzip/ |
| lzo | http://www.oberhumer.com/opensource/lzo/ |
| m4 | GNU M4是传统Unix宏处理器的一个实现。它主要与SVR4兼容，尽管它有一些扩展（例如，处理超过9个位置参数的宏）。GNU M4也有内置的功能，包括文件、运行shell命令、做算术等等。https://www.gnu.org/software/m4/ |
| megatools | Megatools是一个程序集，用于从你的桌面或服务器的命令行访问Mega.nz服务。https://megatools.megous.com/ |
| mesa3d |开源OpenGL, OpenGL ES, Vulkan, OpenCL实现。是计算机图形渲染的开源解决方案的重要基础设施。https://www.mesa3d.org/ |
| meson | 一个构建系统，主要用于mesa3d。 https://mesonbuild.com/ |
| mk_arcade_joystick_rpi |https://github.com/recalbox/mk_arcade_joystick_rpi |
| moonlight-embedded | Moonlight Embedded允许你将你的全部游戏收藏从你强大的Windows桌面流向你的（嵌入式）Linux系统，如Raspberry Pi, CuBox-i和ODROID。 https://github.com/moonlight-stream/moonlight-embedded |
| mosquitto | https://mosquitto.org/|
| mpc | GNU MPC是一个用于复数运算的C库，具有任意高的精度和正确的舍入结果。它将IEEE-754标准中关于固定精度的实数浮点数的原则扩展到复数，为每一个操作提供了明确的语义。同时，高精度下的操作速度是一个主要的设计目标。https://www.multiprecision.org/mpc/ |
| mpfr |https://www.mpfr.org/ |
| mpg123 | https://www.mpg123.de/ |
| mpv | https://mpv.io/ |
| mtdev | 用于linux内核的多点触碰（MT）协议转换库。|
| mtools | https://www.gnu.org/software/mtools/ |
| mupen64plus-audio-sdl | https://github.com/mupen64plus/mupen64plus-audio-sdl |
| mupen64plus-core |
| mupen64plus-input-sdl |
| mupen64plus-rsphle |
| mupen64plus-uiconsole |
| mupen64plus-video-glide64mk2 |
| mupen64plus-video-rice |
| nano | https://www.nano-editor.org/ |
| nanoarch | https://github.com/heuripedes/nanoarch |
| nasm | 这是网络汇编程序（NASM）的项目网页，这是一个适用于x86 CPU架构的汇编程序，可以移植到几乎所有的现代平台，并且可以为许多新旧平台生成代码。https://www.nasm.us/ |
| ncurses | TUI库。https://invisible-island.net/ncurses/announce.html|
| nettle | Nettle是一个加密库，它被设计成可以轻松适应或多或少的任何环境。在面向对象语言（C++、Python、Pike...）的加密工具包中，在LSH或GNUPG等应用中，甚至在内核空间中。https://www.lysator.liu.se/~nisse/nettle/ |
| nfs-utils | http://git.linux-nfs.org/?p=steved/nfs-utils.git;a=summary |
| nghttp2 | https://nghttp2.org/ |
| ninja | https://ninja-build.org/ |
| nodejs | https://nodejs.org/en/ |
| ntfs-3g | https://www.tuxera.com/company/open-source/ |
| ntp | http://www.ntp.org/ntpfaq/NTP-s-def.htm |
| openbor | https://github.com/DCurrent/openbor |
| opus | https://opus-codec.org/ |
| opusfile | https://github.com/xiph/opusfile |
| oracle-mysql | https://www.oracle.com/mysql/ |
| oricutron | https://github.com/pete-gordon/oricutron |
| p7zip | https://p7zip.sourceforge.net/ |
| pamix | https://github.com/patroclos/PAmix |
| parted | https://www.gnu.org/software/parted/ GNU Parted可以操作分区表。这对于为新的操作系统创造空间、重新组织磁盘使用、复制硬盘上的数据和磁盘成像很有用。该软件包包含一个库，libparted，以及一个命令行前端，parted，它也可以在脚本中使用。 |
| patchelf | PatchELF是一个用于修改现有ELF可执行文件和库的简单工具。https://github.com/NixOS/patchelf |
| pcre | PCRE库是一组实现正则表达式模式匹配的函数.https://www.pcre.org/ |
| perl | https://www.perl.org/ |
| perl-parse-yapp | Parse::Yapp (Yet Another Perl Parser compiler)是一个模块集合，让你生成和使用类似yacc的线程安全（可重入）的解析器，并具有perl面向对象的接口。https://metacpan.org/pod/Parse::Yapp |
| pixman | http://www.pixman.org/ |
| pkgconf | pkgconf是一个有助于为开发框架配置编译器和链接器标志的程序。它类似于freedesktop.org的pkg-config，在提供额外功能的同时也保持了兼容性。http://pkgconf.org/|
| popt | 命令行解析工具。https://github.com/rpm-software-management/popt|
| ppsspp | https://www.ppsspp.org/模拟器 |
| prelink-cross | https://wiki.yoctoproject.org/wiki/Cross-Prelink |
| procps-ng | 用于浏览procfs的命令行工具，procfs是一个由内核动态生成的 "伪 "文件系统，提供关于其进程表中条目状态的信息。https://gitlab.com/procps-ng/procps |
| protobuf | protobuf是谷歌的语言中立、平台中立、可扩展的机制，用于序列化结构化数据--想想XML，但更小、更快、更简单。你只需定义一次你希望你的数据如何被结构化，然后你就可以使用特殊生成的源代码，轻松地从各种数据流和使用各种语言写入和读取你的结构化数据。https://developers.google.com/protocol-buffers |
| pugixml | pugixml是一个轻量级的C++ XML处理库。https://pugixml.org/ |
| pulseaudio | PulseAudio是一个用于POSIX操作系统的声音服务器系统，这意味着它是你的声音应用程序的代理。https://www.freedesktop.org/wiki/Software/PulseAudio/ |
| python3 | https://www.python.org/ |
| python-certifi |
| python-charset-normalizer |
| python-gobject |
| python-idna |
| python-libusb1 |
| python-mako |
| python-markupsafe |
| python-paho-mqtt |
| python-psutil |
| python-pycryptodomex |
| python-pygame |
| python-pyudev |
| python-requests |
| python-rpi-gpio |
| python-setuptools |
| python-six |
| python-urllib3 |
| qemu | https://www.qemu.org/ |
| qtsixa |
| qtsixa-shanwan |
| rapidjson |
| raspi-gpio |
| rb5000 |
| readline |
| recalbox-initramfs |
| recalbox-manager2 |
| recalbox-retrogame |
| recalbox-settings |
| recalbox-themes |
| recalbox-volumed |
| retroarch |
| retroarch-assets |
| rgb-pi |
| rpi-firmware |
| rsync |
| rtl8189fs |
| rtl8812au |
| rtl88x2bu |
| rtmpdump |
| samba4 |
| sbc |
| scummvm |
| sdl |
| sdl2 |
| sdl2_gfx |
| sdl2_image |
| sdl2_mixer |
| sdl2_net |
| sdl2_ttf |
| sdl_image |
| sdl_mixer |
| sdl_net |
| sdl_sound |
| sdl_ttf |
| simcoupe |
| snappy |
| spdlog |
| speex |
| speexdsp |
| sqlite |
| squashfs |
| swig |
| switchres |
| sysvinit |
| taglib |
| tar |
| tcl |
| tft-waveshare |
| ti99sim |
| tinyxml |
| tinyxml2 |
| tzdata |
| unzip |
| usb_modeswitch |
| usb_modeswitch_data |
| usbmount |
| usbutils |
| util-linux |
| vim |
| virtualgamepads |
| waf |
| wget |
| wildmidi |
| wireless-regdb |
| wpa_supplicant |
| wsd |
| x264 |
| x265 |
| xapp_xkbcomp |
| xarcade2jstick |
| xcb-proto |
| xkeyboard-config |
| xlib_libX11 |
| xlib_libXau |
| xlib_libXdmcp |
| xlib_libxkbfile |
| xlib_xtrans |
| xmlstarlet |
| xorgproto |
| xow |
| xpi_gamecon_rpi |
| xroar |
| xutil_util-macros |
| xz |
| zic |
| zip |
| zstd |

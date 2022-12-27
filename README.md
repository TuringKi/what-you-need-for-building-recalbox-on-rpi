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
| icu |
| isl |
| iw |
| jimtcl |
| joycond |
| jpeg-turbo |
| jsoncpp |
| json-for-modern-cpp |
| jstest2 |
| kbd |
| kernelfirmwares |
| kmod |
| kmsgrab |
| kodi |
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
| lame |
| lba-finder |
| lcms2 |
| libao |
| libass |
| libcapsimage |
| libcdio |
| libcec |
| libconfuse |
| libcrossguid |
| libcurl |
| libdaemon |
| libdrm |
| libenet |
| libevdev |
| libevent |
| libffi |
| libfreeimage |
| libfribidi |
| libfuse |
| libgcrypt |
| libglib2 |
| libgpg-error |
| libhdhomerun |
| libidn |
| libinput |
| libjpeg |
| liblcf |
| liblockfile |
| libmad |
| libmicrohttpd |
| libmodplug |
| libmpeg2 |
| libnfs |
| libnl |
| libnspr |
| libnss |
| libogg |
| libopenssl |
| libpcap |
| libplatform |
| libplist |
| libpng |
| libpthread-stubs |
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
| libshairplay |
| libsidplay2 |
| libsndfile |
| libtasn1 |
| libtheora |
| libtirpc |
| libtool |
| libunistring |
| libusb |
| libusb-compat |
| libuv |
| libvorbis |
| libvpx |
| libwebsockets |
| libxcb |
| libxkbcommon |
| libxml2 |
| libxmp-lite |
| libxslt |
| libzip |
| libzlib |
| linapple-pie |
| linux |
| linuxconsoletools |
| lirc-tools |
| lockfile-progs |
| lz4 |
| lzip |
| lzo |
| m4 |
| megatools |
| mesa3d |
| meson |
| mk_arcade_joystick_rpi |
| moonlight-embedded |
| mosquitto |
| mpc |
| mpfr |
| mpg123 |
| mpv |
| mtdev |
| mtools |
| mupen64plus-audio-sdl |
| mupen64plus-core |
| mupen64plus-input-sdl |
| mupen64plus-rsphle |
| mupen64plus-uiconsole |
| mupen64plus-video-glide64mk2 |
| mupen64plus-video-rice |
| nano |
| nanoarch |
| nasm |
| ncurses |
| nettle |
| nfs-utils |
| nghttp2 |
| ninja |
| nodejs |
| ntfs-3g |
| ntp |
| openbor |
| opus |
| opusfile |
| oracle-mysql |
| oricutron |
| p7zip |
| pamix |
| parted |
| patchelf |
| pcre |
| perl |
| perl-parse-yapp |
| pixman |
| pkgconf |
| popt |
| ppsspp |
| prelink-cross |
| procps-ng |
| protobuf |
| pugixml |
| pulseaudio |
| python3 |
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
| qemu |
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

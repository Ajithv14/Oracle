$ cat /etc/os-release

NAME="Oracle Linux Server"
VERSION="7.9"
ID="ol"
ID_LIKE="fedora"
VARIANT="Server"
VARIANT_ID="server"
VERSION_ID="7.9"
PRETTY_NAME="Oracle Linux Server 7.9"
ANSI_COLOR="0;31"
CPE_NAME="cpe:/o:oracle:linux:7:9:server"
HOME_URL="https://linux.oracle.com/"
BUG_REPORT_URL="https://bugzilla.oracle.com/"

ORACLE_BUGZILLA_PRODUCT="Oracle Linux 7"
ORACLE_BUGZILLA_PRODUCT_VERSION=7.9
ORACLE_SUPPORT_PRODUCT="Oracle Linux"
ORACLE_SUPPORT_PRODUCT_VERSION=7.9

# yum update -y

# yum install oracle-database-preinstall-19c wget -y
Loaded plugins: ulninfo
Resolving Dependencies
--> Running transaction check
---> Package oracle-database-preinstall-19c.x86_64 0:1.0-3.el7 will be installed
--> Processing Dependency: bind-utils for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: compat-libcap1 for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: glibc-devel for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: ksh for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: libaio for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: libaio-devel for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: libstdc++-devel for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: make for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: nfs-utils for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: smartmontools for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: sysstat for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: unzip for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: xorg-x11-utils for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Processing Dependency: xorg-x11-xauth for package: oracle-database-preinstall-19c-1.0-3.el7.x86_64
--> Running transaction check
---> Package bind-utils.x86_64 32:9.11.4-26.P2.el7_9.15 will be installed
--> Processing Dependency: bind-libs(x86-64) = 32:9.11.4-26.P2.el7_9.15 for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: bind-libs-lite(x86-64) = 32:9.11.4-26.P2.el7_9.15 for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: libGeoIP.so.1()(64bit) for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: libbind9.so.160()(64bit) for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: libdns.so.1102()(64bit) for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: libirs.so.160()(64bit) for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: libisc.so.169()(64bit) for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: libisccfg.so.160()(64bit) for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
--> Processing Dependency: liblwres.so.160()(64bit) for package: 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64
---> Package compat-libcap1.x86_64 0:1.10-7.el7 will be installed
---> Package glibc-devel.x86_64 0:2.17-326.0.9.el7_9 will be installed
--> Processing Dependency: glibc-headers = 2.17-326.0.9.el7_9 for package: glibc-devel-2.17-326.0.9.el7_9.x86_64
--> Processing Dependency: glibc-headers for package: glibc-devel-2.17-326.0.9.el7_9.x86_64
---> Package ksh.x86_64 0:20120801-144.0.1.el7_9 will be installed
---> Package libaio.x86_64 0:0.3.109-13.el7 will be installed
---> Package libaio-devel.x86_64 0:0.3.109-13.el7 will be installed
---> Package libstdc++-devel.x86_64 0:4.8.5-44.0.3.el7 will be installed
---> Package make.x86_64 1:3.82-24.el7 will be installed
---> Package nfs-utils.x86_64 1:1.3.0-0.68.0.1.el7.2 will be installed
--> Processing Dependency: gssproxy >= 0.7.0-3 for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: libtirpc >= 0.2.4-0.7 for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: keyutils for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: libevent for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: libnfsidmap for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: quota for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: rpcbind for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: libevent-2.0.so.5()(64bit) for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: libnfsidmap.so.0()(64bit) for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
--> Processing Dependency: libtirpc.so.1()(64bit) for package: 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64
---> Package smartmontools.x86_64 1:7.0-2.el7 will be installed
--> Processing Dependency: mailx for package: 1:smartmontools-7.0-2.el7.x86_64
---> Package sysstat.x86_64 0:10.1.5-20.0.3.el7_9 will be installed
--> Processing Dependency: libsensors.so.4()(64bit) for package: sysstat-10.1.5-20.0.3.el7_9.x86_64
---> Package unzip.x86_64 0:6.0-24.0.1.el7_9 will be installed
---> Package xorg-x11-utils.x86_64 0:7.5-23.el7 will be installed
--> Processing Dependency: libX11-xcb.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libX11.so.6()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXext.so.6()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXi.so.6()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXinerama.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXrandr.so.2()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXrender.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXtst.so.6()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXv.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXxf86dga.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXxf86misc.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libXxf86vm.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libdmx.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libxcb-shape.so.0()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
--> Processing Dependency: libxcb.so.1()(64bit) for package: xorg-x11-utils-7.5-23.el7.x86_64
---> Package xorg-x11-xauth.x86_64 1:1.0.9-1.el7 will be installed
--> Processing Dependency: libXau.so.6()(64bit) for package: 1:xorg-x11-xauth-1.0.9-1.el7.x86_64
--> Processing Dependency: libXmuu.so.1()(64bit) for package: 1:xorg-x11-xauth-1.0.9-1.el7.x86_64
--> Running transaction check
---> Package GeoIP.x86_64 0:1.5.0-14.el7 will be installed
--> Processing Dependency: geoipupdate for package: GeoIP-1.5.0-14.el7.x86_64
---> Package bind-libs.x86_64 32:9.11.4-26.P2.el7_9.15 will be installed
--> Processing Dependency: bind-license = 32:9.11.4-26.P2.el7_9.15 for package: 32:bind-libs-9.11.4-26.P2.el7_9.15.x86_64
---> Package bind-libs-lite.x86_64 32:9.11.4-26.P2.el7_9.15 will be installed
---> Package glibc-headers.x86_64 0:2.17-326.0.9.el7_9 will be installed
--> Processing Dependency: kernel-headers >= 2.2.1 for package: glibc-headers-2.17-326.0.9.el7_9.x86_64
--> Processing Dependency: kernel-headers for package: glibc-headers-2.17-326.0.9.el7_9.x86_64
---> Package gssproxy.x86_64 0:0.7.0-30.el7_9 will be installed
--> Processing Dependency: libini_config >= 1.3.1-31 for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libini_config.so.3(INI_CONFIG_1.1.0)(64bit) for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libini_config.so.3(INI_CONFIG_1.2.0)(64bit) for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libref_array.so.1(REF_ARRAY_0.1.1)(64bit) for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libverto-module-base for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libbasicobjects.so.0()(64bit) for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libcollection.so.2()(64bit) for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libini_config.so.3()(64bit) for package: gssproxy-0.7.0-30.el7_9.x86_64
--> Processing Dependency: libref_array.so.1()(64bit) for package: gssproxy-0.7.0-30.el7_9.x86_64
---> Package keyutils.x86_64 0:1.5.8-3.el7 will be installed
---> Package libX11.x86_64 0:1.6.7-5.el7_9 will be installed
--> Processing Dependency: libX11-common >= 1.6.7-5.el7_9 for package: libX11-1.6.7-5.el7_9.x86_64
---> Package libXau.x86_64 0:1.0.8-2.1.el7 will be installed
---> Package libXext.x86_64 0:1.3.3-3.el7 will be installed
---> Package libXi.x86_64 0:1.7.9-1.el7 will be installed
---> Package libXinerama.x86_64 0:1.1.3-2.1.el7 will be installed
---> Package libXmu.x86_64 0:1.1.2-2.el7 will be installed
--> Processing Dependency: libXt.so.6()(64bit) for package: libXmu-1.1.2-2.el7.x86_64
---> Package libXrandr.x86_64 0:1.5.1-2.el7 will be installed
---> Package libXrender.x86_64 0:0.9.10-1.el7 will be installed
---> Package libXtst.x86_64 0:1.2.3-1.el7 will be installed
---> Package libXv.x86_64 0:1.0.11-1.el7 will be installed
---> Package libXxf86dga.x86_64 0:1.1.4-2.1.el7 will be installed
---> Package libXxf86misc.x86_64 0:1.0.3-7.1.el7 will be installed
---> Package libXxf86vm.x86_64 0:1.1.4-1.el7 will be installed
---> Package libdmx.x86_64 0:1.1.3-3.el7 will be installed
---> Package libevent.x86_64 0:2.0.21-4.el7 will be installed
---> Package libnfsidmap.x86_64 0:0.25-19.el7 will be installed
---> Package libtirpc.x86_64 0:0.2.4-0.16.el7 will be installed
---> Package libxcb.x86_64 0:1.13-1.el7 will be installed
---> Package lm_sensors-libs.x86_64 0:3.4.0-8.20160601gitf9185e5.0.1.el7_9.1 will be installed
---> Package mailx.x86_64 0:12.5-19.el7 will be installed
---> Package quota.x86_64 1:4.01-19.el7 will be installed
--> Processing Dependency: quota-nls = 1:4.01-19.el7 for package: 1:quota-4.01-19.el7.x86_64
--> Processing Dependency: tcp_wrappers for package: 1:quota-4.01-19.el7.x86_64
---> Package rpcbind.x86_64 0:0.2.0-49.el7 will be installed
--> Running transaction check
---> Package bind-license.noarch 32:9.11.4-26.P2.el7_9.15 will be installed
---> Package geoipupdate.x86_64 0:2.5.0-2.el7 will be installed
---> Package kernel-headers.x86_64 0:3.10.0-1160.118.1.0.1.el7 will be installed
---> Package libX11-common.noarch 0:1.6.7-5.el7_9 will be installed
---> Package libXt.x86_64 0:1.1.5-3.el7 will be installed
--> Processing Dependency: libICE.so.6()(64bit) for package: libXt-1.1.5-3.el7.x86_64
--> Processing Dependency: libSM.so.6()(64bit) for package: libXt-1.1.5-3.el7.x86_64
---> Package libbasicobjects.x86_64 0:0.1.1-32.el7 will be installed
---> Package libcollection.x86_64 0:0.7.0-32.el7 will be installed
---> Package libini_config.x86_64 0:1.3.1-32.el7 will be installed
--> Processing Dependency: libpath_utils.so.1(PATH_UTILS_0.2.1)(64bit) for package: libini_config-1.3.1-32.el7.x86_64
--> Processing Dependency: libpath_utils.so.1()(64bit) for package: libini_config-1.3.1-32.el7.x86_64
---> Package libref_array.x86_64 0:0.1.5-32.el7 will be installed
---> Package libverto-libevent.x86_64 0:0.2.5-4.el7 will be installed
---> Package quota-nls.noarch 1:4.01-19.el7 will be installed
---> Package tcp_wrappers.x86_64 0:7.6-77.el7 will be installed
--> Running transaction check
---> Package libICE.x86_64 0:1.0.9-9.el7 will be installed
---> Package libSM.x86_64 0:1.2.2-2.el7 will be installed
---> Package libpath_utils.x86_64 0:0.2.1-32.el7 will be installed
--> Finished Dependency Resolution

Dependencies Resolved

==============================================================================================================================================================
 Package                                       Arch                  Version                                                  Repository                 Size
==============================================================================================================================================================
Installing:
 oracle-database-preinstall-19c                x86_64                1.0-3.el7                                                ol7_latest                 27 k
Installing for dependencies:
 GeoIP                                         x86_64                1.5.0-14.el7                                             ol7_latest                1.5 M
 bind-libs                                     x86_64                32:9.11.4-26.P2.el7_9.15                                 ol7_latest                158 k
 bind-libs-lite                                x86_64                32:9.11.4-26.P2.el7_9.15                                 ol7_latest                1.1 M
 bind-license                                  noarch                32:9.11.4-26.P2.el7_9.15                                 ol7_latest                 91 k
 bind-utils                                    x86_64                32:9.11.4-26.P2.el7_9.15                                 ol7_latest                261 k
 compat-libcap1                                x86_64                1.10-7.el7                                               ol7_latest                 17 k
 geoipupdate                                   x86_64                2.5.0-2.el7                                              ol7_latest                 34 k
 glibc-devel                                   x86_64                2.17-326.0.9.el7_9                                       ol7_latest                1.1 M
 glibc-headers                                 x86_64                2.17-326.0.9.el7_9                                       ol7_latest                694 k
 gssproxy                                      x86_64                0.7.0-30.el7_9                                           ol7_latest                110 k
 kernel-headers                                x86_64                3.10.0-1160.118.1.0.1.el7                                ol7_latest                9.1 M
 keyutils                                      x86_64                1.5.8-3.el7                                              ol7_latest                 53 k
 ksh                                           x86_64                20120801-144.0.1.el7_9                                   ol7_latest                882 k
 libICE                                        x86_64                1.0.9-9.el7                                              ol7_latest                 66 k
 libSM                                         x86_64                1.2.2-2.el7                                              ol7_latest                 39 k
 libX11                                        x86_64                1.6.7-5.el7_9                                            ol7_latest                607 k
 libX11-common                                 noarch                1.6.7-5.el7_9                                            ol7_latest                164 k
 libXau                                        x86_64                1.0.8-2.1.el7                                            ol7_latest                 28 k
 libXext                                       x86_64                1.3.3-3.el7                                              ol7_latest                 38 k
 libXi                                         x86_64                1.7.9-1.el7                                              ol7_latest                 40 k
 libXinerama                                   x86_64                1.1.3-2.1.el7                                            ol7_latest                 13 k
 libXmu                                        x86_64                1.1.2-2.el7                                              ol7_latest                 70 k
 libXrandr                                     x86_64                1.5.1-2.el7                                              ol7_latest                 27 k
 libXrender                                    x86_64                0.9.10-1.el7                                             ol7_latest                 25 k
 libXt                                         x86_64                1.1.5-3.el7                                              ol7_latest                172 k
 libXtst                                       x86_64                1.2.3-1.el7                                              ol7_latest                 20 k
 libXv                                         x86_64                1.0.11-1.el7                                             ol7_latest                 18 k
 libXxf86dga                                   x86_64                1.1.4-2.1.el7                                            ol7_latest                 18 k
 libXxf86misc                                  x86_64                1.0.3-7.1.el7                                            ol7_latest                 19 k
 libXxf86vm                                    x86_64                1.1.4-1.el7                                              ol7_latest                 17 k
 libaio                                        x86_64                0.3.109-13.el7                                           ol7_latest                 24 k
 libaio-devel                                  x86_64                0.3.109-13.el7                                           ol7_latest                 12 k
 libbasicobjects                               x86_64                0.1.1-32.el7                                             ol7_latest                 25 k
 libcollection                                 x86_64                0.7.0-32.el7                                             ol7_latest                 41 k
 libdmx                                        x86_64                1.1.3-3.el7                                              ol7_latest                 15 k
 libevent                                      x86_64                2.0.21-4.el7                                             ol7_latest                208 k
 libini_config                                 x86_64                1.3.1-32.el7                                             ol7_latest                 63 k
 libnfsidmap                                   x86_64                0.25-19.el7                                              ol7_latest                 49 k
 libpath_utils                                 x86_64                0.2.1-32.el7                                             ol7_latest                 28 k
 libref_array                                  x86_64                0.1.5-32.el7                                             ol7_latest                 27 k
 libstdc++-devel                               x86_64                4.8.5-44.0.3.el7                                         ol7_latest                1.5 M
 libtirpc                                      x86_64                0.2.4-0.16.el7                                           ol7_latest                 89 k
 libverto-libevent                             x86_64                0.2.5-4.el7                                              ol7_latest                8.2 k
 libxcb                                        x86_64                1.13-1.el7                                               ol7_latest                213 k
 lm_sensors-libs                               x86_64                3.4.0-8.20160601gitf9185e5.0.1.el7_9.1                   ol7_latest                 42 k
 mailx                                         x86_64                12.5-19.el7                                              ol7_latest                244 k
 make                                          x86_64                1:3.82-24.el7                                            ol7_latest                420 k
 nfs-utils                                     x86_64                1:1.3.0-0.68.0.1.el7.2                                   ol7_latest                413 k
 quota                                         x86_64                1:4.01-19.el7                                            ol7_latest                178 k
 quota-nls                                     noarch                1:4.01-19.el7                                            ol7_latest                 90 k
 rpcbind                                       x86_64                0.2.0-49.el7                                             ol7_latest                 59 k
 smartmontools                                 x86_64                1:7.0-2.el7                                              ol7_latest                546 k
 sysstat                                       x86_64                10.1.5-20.0.3.el7_9                                      ol7_latest                316 k
 tcp_wrappers                                  x86_64                7.6-77.el7                                               ol7_latest                 78 k
 unzip                                         x86_64                6.0-24.0.1.el7_9                                         ol7_latest                172 k
 xorg-x11-utils                                x86_64                7.5-23.el7                                               ol7_latest                114 k
 xorg-x11-xauth                                x86_64                1:1.0.9-1.el7                                            ol7_latest                 29 k

Transaction Summary
==============================================================================================================================================================
Install  1 Package (+57 Dependent packages)

Total download size: 21 M
Installed size: 40 M
Is this ok [y/d/N]: y
Downloading packages:
(1/58): GeoIP-1.5.0-14.el7.x86_64.rpm                                                                                                  | 1.5 MB  00:00:00
(2/58): bind-libs-lite-9.11.4-26.P2.el7_9.15.x86_64.rpm                                                                                | 1.1 MB  00:00:00
(3/58): bind-license-9.11.4-26.P2.el7_9.15.noarch.rpm                                                                                  |  91 kB  00:00:00
(4/58): bind-utils-9.11.4-26.P2.el7_9.15.x86_64.rpm                                                                                    | 261 kB  00:00:00
(5/58): bind-libs-9.11.4-26.P2.el7_9.15.x86_64.rpm                                                                                     | 158 kB  00:00:00
(6/58): compat-libcap1-1.10-7.el7.x86_64.rpm                                                                                           |  17 kB  00:00:00
(7/58): geoipupdate-2.5.0-2.el7.x86_64.rpm                                                                                             |  34 kB  00:00:00
(8/58): glibc-headers-2.17-326.0.9.el7_9.x86_64.rpm                                                                                    | 694 kB  00:00:00
(9/58): glibc-devel-2.17-326.0.9.el7_9.x86_64.rpm                                                                                      | 1.1 MB  00:00:00
(10/58): gssproxy-0.7.0-30.el7_9.x86_64.rpm                                                                                            | 110 kB  00:00:00
(11/58): keyutils-1.5.8-3.el7.x86_64.rpm                                                                                               |  53 kB  00:00:00
(12/58): ksh-20120801-144.0.1.el7_9.x86_64.rpm                                                                                         | 882 kB  00:00:00
(13/58): libICE-1.0.9-9.el7.x86_64.rpm                                                                                                 |  66 kB  00:00:00
(14/58): libSM-1.2.2-2.el7.x86_64.rpm                                                                                                  |  39 kB  00:00:00
(15/58): libX11-1.6.7-5.el7_9.x86_64.rpm                                                                                               | 607 kB  00:00:00
(16/58): kernel-headers-3.10.0-1160.118.1.0.1.el7.x86_64.rpm                                                                           | 9.1 MB  00:00:00
(17/58): libX11-common-1.6.7-5.el7_9.noarch.rpm                                                                                        | 164 kB  00:00:00
(18/58): libXau-1.0.8-2.1.el7.x86_64.rpm                                                                                               |  28 kB  00:00:00
(19/58): libXext-1.3.3-3.el7.x86_64.rpm                                                                                                |  38 kB  00:00:00
(20/58): libXi-1.7.9-1.el7.x86_64.rpm                                                                                                  |  40 kB  00:00:00
(21/58): libXinerama-1.1.3-2.1.el7.x86_64.rpm                                                                                          |  13 kB  00:00:00
(22/58): libXrandr-1.5.1-2.el7.x86_64.rpm                                                                                              |  27 kB  00:00:00
(23/58): libXmu-1.1.2-2.el7.x86_64.rpm                                                                                                 |  70 kB  00:00:00
(24/58): libXrender-0.9.10-1.el7.x86_64.rpm                                                                                            |  25 kB  00:00:00
(25/58): libXt-1.1.5-3.el7.x86_64.rpm                                                                                                  | 172 kB  00:00:00
(26/58): libXtst-1.2.3-1.el7.x86_64.rpm                                                                                                |  20 kB  00:00:00
(27/58): libXxf86dga-1.1.4-2.1.el7.x86_64.rpm                                                                                          |  18 kB  00:00:00
(28/58): libXxf86misc-1.0.3-7.1.el7.x86_64.rpm                                                                                         |  19 kB  00:00:00
(29/58): libXv-1.0.11-1.el7.x86_64.rpm                                                                                                 |  18 kB  00:00:00
(30/58): libXxf86vm-1.1.4-1.el7.x86_64.rpm                                                                                             |  17 kB  00:00:00
(31/58): libaio-0.3.109-13.el7.x86_64.rpm                                                                                              |  24 kB  00:00:00
(32/58): libbasicobjects-0.1.1-32.el7.x86_64.rpm                                                                                       |  25 kB  00:00:00
(33/58): libaio-devel-0.3.109-13.el7.x86_64.rpm                                                                                        |  12 kB  00:00:00
(34/58): libcollection-0.7.0-32.el7.x86_64.rpm                                                                                         |  41 kB  00:00:00
(35/58): libdmx-1.1.3-3.el7.x86_64.rpm                                                                                                 |  15 kB  00:00:00
(36/58): libevent-2.0.21-4.el7.x86_64.rpm                                                                                              | 208 kB  00:00:00
(37/58): libnfsidmap-0.25-19.el7.x86_64.rpm                                                                                            |  49 kB  00:00:00
(38/58): libini_config-1.3.1-32.el7.x86_64.rpm                                                                                         |  63 kB  00:00:00
(39/58): libpath_utils-0.2.1-32.el7.x86_64.rpm                                                                                         |  28 kB  00:00:00
(40/58): libstdc++-devel-4.8.5-44.0.3.el7.x86_64.rpm                                                                                   | 1.5 MB  00:00:00
(41/58): libtirpc-0.2.4-0.16.el7.x86_64.rpm                                                                                            |  89 kB  00:00:00
(42/58): libverto-libevent-0.2.5-4.el7.x86_64.rpm                                                                                      | 8.2 kB  00:00:00
(43/58): libxcb-1.13-1.el7.x86_64.rpm                                                                                                  | 213 kB  00:00:00
(44/58): lm_sensors-libs-3.4.0-8.20160601gitf9185e5.0.1.el7_9.1.x86_64.rpm                                                             |  42 kB  00:00:00
(45/58): mailx-12.5-19.el7.x86_64.rpm                                                                                                  | 244 kB  00:00:00
(46/58): make-3.82-24.el7.x86_64.rpm                                                                                                   | 420 kB  00:00:00
(47/58): nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64.rpm                                                                                     | 413 kB  00:00:00
(48/58): oracle-database-preinstall-19c-1.0-3.el7.x86_64.rpm                                                                           |  27 kB  00:00:00
(49/58): quota-4.01-19.el7.x86_64.rpm                                                                                                  | 178 kB  00:00:00
(50/58): quota-nls-4.01-19.el7.noarch.rpm                                                                                              |  90 kB  00:00:00
(51/58): rpcbind-0.2.0-49.el7.x86_64.rpm                                                                                               |  59 kB  00:00:00
(52/58): libref_array-0.1.5-32.el7.x86_64.rpm                                                                                          |  27 kB  00:00:00
(53/58): smartmontools-7.0-2.el7.x86_64.rpm                                                                                            | 546 kB  00:00:00
(54/58): sysstat-10.1.5-20.0.3.el7_9.x86_64.rpm                                                                                        | 316 kB  00:00:00
(55/58): unzip-6.0-24.0.1.el7_9.x86_64.rpm                                                                                             | 172 kB  00:00:00
(56/58): tcp_wrappers-7.6-77.el7.x86_64.rpm                                                                                            |  78 kB  00:00:00
(57/58): xorg-x11-xauth-1.0.9-1.el7.x86_64.rpm                                                                                         |  29 kB  00:00:00
(58/58): xorg-x11-utils-7.5-23.el7.x86_64.rpm                                                                                          | 114 kB  00:00:00
--------------------------------------------------------------------------------------------------------------------------------------------------------------
Total                                                                                                                          27 MB/s |  21 MB  00:00:00
Running transaction check
Running transaction test
Transaction test succeeded
Running transaction
  Installing : libXau-1.0.8-2.1.el7.x86_64                                                                                                               1/58
  Installing : libxcb-1.13-1.el7.x86_64                                                                                                                  2/58
  Installing : libref_array-0.1.5-32.el7.x86_64                                                                                                          3/58
  Installing : libevent-2.0.21-4.el7.x86_64                                                                                                              4/58
  Installing : libaio-0.3.109-13.el7.x86_64                                                                                                              5/58
  Installing : 32:bind-license-9.11.4-26.P2.el7_9.15.noarch                                                                                              6/58
  Installing : libbasicobjects-0.1.1-32.el7.x86_64                                                                                                       7/58
  Installing : libcollection-0.7.0-32.el7.x86_64                                                                                                         8/58
  Installing : libICE-1.0.9-9.el7.x86_64                                                                                                                 9/58
  Installing : libtirpc-0.2.4-0.16.el7.x86_64                                                                                                           10/58
  Installing : rpcbind-0.2.0-49.el7.x86_64                                                                                                              11/58
  Installing : libSM-1.2.2-2.el7.x86_64                                                                                                                 12/58
  Installing : libaio-devel-0.3.109-13.el7.x86_64                                                                                                       13/58
  Installing : libverto-libevent-0.2.5-4.el7.x86_64                                                                                                     14/58
  Installing : 1:quota-nls-4.01-19.el7.noarch                                                                                                           15/58
  Installing : mailx-12.5-19.el7.x86_64                                                                                                                 16/58
  Installing : 1:smartmontools-7.0-2.el7.x86_64                                                                                                         17/58
  Installing : libstdc++-devel-4.8.5-44.0.3.el7.x86_64                                                                                                  18/58
  Installing : keyutils-1.5.8-3.el7.x86_64                                                                                                              19/58
  Installing : libnfsidmap-0.25-19.el7.x86_64                                                                                                           20/58
  Installing : lm_sensors-libs-3.4.0-8.20160601gitf9185e5.0.1.el7_9.1.x86_64                                                                            21/58
  Installing : sysstat-10.1.5-20.0.3.el7_9.x86_64                                                                                                       22/58
  Installing : libpath_utils-0.2.1-32.el7.x86_64                                                                                                        23/58
  Installing : libini_config-1.3.1-32.el7.x86_64                                                                                                        24/58
  Installing : gssproxy-0.7.0-30.el7_9.x86_64                                                                                                           25/58
  Installing : compat-libcap1-1.10-7.el7.x86_64                                                                                                         26/58
  Installing : ksh-20120801-144.0.1.el7_9.x86_64                                                                                                        27/58
  Installing : tcp_wrappers-7.6-77.el7.x86_64                                                                                                           28/58
  Installing : 1:quota-4.01-19.el7.x86_64                                                                                                               29/58
  Installing : 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64                                                                                                  30/58
  Installing : libX11-common-1.6.7-5.el7_9.noarch                                                                                                       31/58
  Installing : libX11-1.6.7-5.el7_9.x86_64                                                                                                              32/58
  Installing : libXext-1.3.3-3.el7.x86_64                                                                                                               33/58
  Installing : libXi-1.7.9-1.el7.x86_64                                                                                                                 34/58
  Installing : libXrender-0.9.10-1.el7.x86_64                                                                                                           35/58
  Installing : libXrandr-1.5.1-2.el7.x86_64                                                                                                             36/58
  Installing : libXtst-1.2.3-1.el7.x86_64                                                                                                               37/58
  Installing : libdmx-1.1.3-3.el7.x86_64                                                                                                                38/58
  Installing : libXinerama-1.1.3-2.1.el7.x86_64                                                                                                         39/58
  Installing : libXv-1.0.11-1.el7.x86_64                                                                                                                40/58
  Installing : libXxf86misc-1.0.3-7.1.el7.x86_64                                                                                                        41/58
  Installing : libXxf86vm-1.1.4-1.el7.x86_64                                                                                                            42/58
  Installing : libXxf86dga-1.1.4-2.1.el7.x86_64                                                                                                         43/58
  Installing : xorg-x11-utils-7.5-23.el7.x86_64                                                                                                         44/58
  Installing : libXt-1.1.5-3.el7.x86_64                                                                                                                 45/58
  Installing : libXmu-1.1.2-2.el7.x86_64                                                                                                                46/58
  Installing : 1:xorg-x11-xauth-1.0.9-1.el7.x86_64                                                                                                      47/58
  Installing : unzip-6.0-24.0.1.el7_9.x86_64                                                                                                            48/58
  Installing : 1:make-3.82-24.el7.x86_64                                                                                                                49/58
  Installing : geoipupdate-2.5.0-2.el7.x86_64                                                                                                           50/58
  Installing : GeoIP-1.5.0-14.el7.x86_64                                                                                                                51/58
  Installing : 32:bind-libs-lite-9.11.4-26.P2.el7_9.15.x86_64                                                                                           52/58
  Installing : 32:bind-libs-9.11.4-26.P2.el7_9.15.x86_64                                                                                                53/58
  Installing : 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64                                                                                               54/58
  Installing : kernel-headers-3.10.0-1160.118.1.0.1.el7.x86_64                                                                                          55/58
  Installing : glibc-headers-2.17-326.0.9.el7_9.x86_64                                                                                                  56/58
  Installing : glibc-devel-2.17-326.0.9.el7_9.x86_64                                                                                                    57/58
  Installing : oracle-database-preinstall-19c-1.0-3.el7.x86_64                                                                                          58/58
  Verifying  : libtirpc-0.2.4-0.16.el7.x86_64                                                                                                            1/58
  Verifying  : gssproxy-0.7.0-30.el7_9.x86_64                                                                                                            2/58
  Verifying  : libXi-1.7.9-1.el7.x86_64                                                                                                                  3/58
  Verifying  : libdmx-1.1.3-3.el7.x86_64                                                                                                                 4/58
  Verifying  : libICE-1.0.9-9.el7.x86_64                                                                                                                 5/58
  Verifying  : 1:nfs-utils-1.3.0-0.68.0.1.el7.2.x86_64                                                                                                   6/58
  Verifying  : libXinerama-1.1.3-2.1.el7.x86_64                                                                                                          7/58
  Verifying  : 32:bind-libs-lite-9.11.4-26.P2.el7_9.15.x86_64                                                                                            8/58
  Verifying  : libXrender-0.9.10-1.el7.x86_64                                                                                                            9/58
  Verifying  : 32:bind-utils-9.11.4-26.P2.el7_9.15.x86_64                                                                                               10/58
  Verifying  : libXv-1.0.11-1.el7.x86_64                                                                                                                11/58
  Verifying  : libXxf86misc-1.0.3-7.1.el7.x86_64                                                                                                        12/58
  Verifying  : libXxf86vm-1.1.4-1.el7.x86_64                                                                                                            13/58
  Verifying  : kernel-headers-3.10.0-1160.118.1.0.1.el7.x86_64                                                                                          14/58
  Verifying  : libcollection-0.7.0-32.el7.x86_64                                                                                                        15/58
  Verifying  : libXt-1.1.5-3.el7.x86_64                                                                                                                 16/58
  Verifying  : libbasicobjects-0.1.1-32.el7.x86_64                                                                                                      17/58
  Verifying  : rpcbind-0.2.0-49.el7.x86_64                                                                                                              18/58
  Verifying  : GeoIP-1.5.0-14.el7.x86_64                                                                                                                19/58
  Verifying  : sysstat-10.1.5-20.0.3.el7_9.x86_64                                                                                                       20/58
  Verifying  : geoipupdate-2.5.0-2.el7.x86_64                                                                                                           21/58
  Verifying  : glibc-headers-2.17-326.0.9.el7_9.x86_64                                                                                                  22/58
  Verifying  : 32:bind-license-9.11.4-26.P2.el7_9.15.noarch                                                                                             23/58
  Verifying  : xorg-x11-utils-7.5-23.el7.x86_64                                                                                                         24/58
  Verifying  : libX11-1.6.7-5.el7_9.x86_64                                                                                                              25/58
  Verifying  : libXtst-1.2.3-1.el7.x86_64                                                                                                               26/58
  Verifying  : libxcb-1.13-1.el7.x86_64                                                                                                                 27/58
  Verifying  : 1:make-3.82-24.el7.x86_64                                                                                                                28/58
  Verifying  : unzip-6.0-24.0.1.el7_9.x86_64                                                                                                            29/58
  Verifying  : libaio-0.3.109-13.el7.x86_64                                                                                                             30/58
  Verifying  : libini_config-1.3.1-32.el7.x86_64                                                                                                        31/58
  Verifying  : libX11-common-1.6.7-5.el7_9.noarch                                                                                                       32/58
  Verifying  : tcp_wrappers-7.6-77.el7.x86_64                                                                                                           33/58
  Verifying  : 1:smartmontools-7.0-2.el7.x86_64                                                                                                         34/58
  Verifying  : libXext-1.3.3-3.el7.x86_64                                                                                                               35/58
  Verifying  : glibc-devel-2.17-326.0.9.el7_9.x86_64                                                                                                    36/58
  Verifying  : ksh-20120801-144.0.1.el7_9.x86_64                                                                                                        37/58
  Verifying  : libevent-2.0.21-4.el7.x86_64                                                                                                             38/58
  Verifying  : oracle-database-preinstall-19c-1.0-3.el7.x86_64                                                                                          39/58
  Verifying  : libverto-libevent-0.2.5-4.el7.x86_64                                                                                                     40/58
  Verifying  : compat-libcap1-1.10-7.el7.x86_64                                                                                                         41/58
  Verifying  : libXrandr-1.5.1-2.el7.x86_64                                                                                                             42/58
  Verifying  : libaio-devel-0.3.109-13.el7.x86_64                                                                                                       43/58
  Verifying  : libref_array-0.1.5-32.el7.x86_64                                                                                                         44/58
  Verifying  : 1:xorg-x11-xauth-1.0.9-1.el7.x86_64                                                                                                      45/58
  Verifying  : libpath_utils-0.2.1-32.el7.x86_64                                                                                                        46/58
  Verifying  : lm_sensors-libs-3.4.0-8.20160601gitf9185e5.0.1.el7_9.1.x86_64                                                                            47/58
  Verifying  : 1:quota-4.01-19.el7.x86_64                                                                                                               48/58
  Verifying  : libnfsidmap-0.25-19.el7.x86_64                                                                                                           49/58
  Verifying  : libSM-1.2.2-2.el7.x86_64                                                                                                                 50/58
  Verifying  : 32:bind-libs-9.11.4-26.P2.el7_9.15.x86_64                                                                                                51/58
  Verifying  : libXxf86dga-1.1.4-2.1.el7.x86_64                                                                                                         52/58
  Verifying  : libXmu-1.1.2-2.el7.x86_64                                                                                                                53/58
  Verifying  : keyutils-1.5.8-3.el7.x86_64                                                                                                              54/58
  Verifying  : libXau-1.0.8-2.1.el7.x86_64                                                                                                              55/58
  Verifying  : libstdc++-devel-4.8.5-44.0.3.el7.x86_64                                                                                                  56/58
  Verifying  : mailx-12.5-19.el7.x86_64                                                                                                                 57/58
  Verifying  : 1:quota-nls-4.01-19.el7.noarch                                                                                                           58/58

Installed:
  oracle-database-preinstall-19c.x86_64 0:1.0-3.el7

Dependency Installed:
  GeoIP.x86_64 0:1.5.0-14.el7                                                             bind-libs.x86_64 32:9.11.4-26.P2.el7_9.15
  bind-libs-lite.x86_64 32:9.11.4-26.P2.el7_9.15                                          bind-license.noarch 32:9.11.4-26.P2.el7_9.15
  bind-utils.x86_64 32:9.11.4-26.P2.el7_9.15                                              compat-libcap1.x86_64 0:1.10-7.el7
  geoipupdate.x86_64 0:2.5.0-2.el7                                                        glibc-devel.x86_64 0:2.17-326.0.9.el7_9
  glibc-headers.x86_64 0:2.17-326.0.9.el7_9                                               gssproxy.x86_64 0:0.7.0-30.el7_9
  kernel-headers.x86_64 0:3.10.0-1160.118.1.0.1.el7                                       keyutils.x86_64 0:1.5.8-3.el7
  ksh.x86_64 0:20120801-144.0.1.el7_9                                                     libICE.x86_64 0:1.0.9-9.el7
  libSM.x86_64 0:1.2.2-2.el7                                                              libX11.x86_64 0:1.6.7-5.el7_9
  libX11-common.noarch 0:1.6.7-5.el7_9                                                    libXau.x86_64 0:1.0.8-2.1.el7
  libXext.x86_64 0:1.3.3-3.el7                                                            libXi.x86_64 0:1.7.9-1.el7
  libXinerama.x86_64 0:1.1.3-2.1.el7                                                      libXmu.x86_64 0:1.1.2-2.el7
  libXrandr.x86_64 0:1.5.1-2.el7                                                          libXrender.x86_64 0:0.9.10-1.el7
  libXt.x86_64 0:1.1.5-3.el7                                                              libXtst.x86_64 0:1.2.3-1.el7
  libXv.x86_64 0:1.0.11-1.el7                                                             libXxf86dga.x86_64 0:1.1.4-2.1.el7
  libXxf86misc.x86_64 0:1.0.3-7.1.el7                                                     libXxf86vm.x86_64 0:1.1.4-1.el7
  libaio.x86_64 0:0.3.109-13.el7                                                          libaio-devel.x86_64 0:0.3.109-13.el7
  libbasicobjects.x86_64 0:0.1.1-32.el7                                                   libcollection.x86_64 0:0.7.0-32.el7
  libdmx.x86_64 0:1.1.3-3.el7                                                             libevent.x86_64 0:2.0.21-4.el7
  libini_config.x86_64 0:1.3.1-32.el7                                                     libnfsidmap.x86_64 0:0.25-19.el7
  libpath_utils.x86_64 0:0.2.1-32.el7                                                     libref_array.x86_64 0:0.1.5-32.el7
  libstdc++-devel.x86_64 0:4.8.5-44.0.3.el7                                               libtirpc.x86_64 0:0.2.4-0.16.el7
  libverto-libevent.x86_64 0:0.2.5-4.el7                                                  libxcb.x86_64 0:1.13-1.el7
  lm_sensors-libs.x86_64 0:3.4.0-8.20160601gitf9185e5.0.1.el7_9.1                         mailx.x86_64 0:12.5-19.el7
  make.x86_64 1:3.82-24.el7                                                               nfs-utils.x86_64 1:1.3.0-0.68.0.1.el7.2
  quota.x86_64 1:4.01-19.el7                                                              quota-nls.noarch 1:4.01-19.el7
  rpcbind.x86_64 0:0.2.0-49.el7                                                           smartmontools.x86_64 1:7.0-2.el7
  sysstat.x86_64 0:10.1.5-20.0.3.el7_9                                                    tcp_wrappers.x86_64 0:7.6-77.el7
  unzip.x86_64 0:6.0-24.0.1.el7_9                                                         xorg-x11-utils.x86_64 0:7.5-23.el7
  xorg-x11-xauth.x86_64 1:1.0.9-1.el7

Complete!

# su - oracle

# passwd oracle
Changing password for user oracle.
New password:
BAD PASSWORD: The password is shorter than 8 characters
Retype new password:
passwd: all authentication tokens updated successfully.

# mkdir -p /u01/app/oracle/product/19.0.0/dbhome_1
# mkdir -p /u02/oradata
# chown -R oracle:oinstall /u01 /u02
# chmod -R 775 /u01 /u02

# su - oracle
Last login: Sat May 11 06:47:12 GMT 2024 on pts/0

[oracle@ip-172-31-54-158 ~]$ vi .bash_profile                       
contents : 
export ORACLE_HOME=/u01/app/oracle/product/19.0.0/dbhome_1
export ORACLE_BASE=/u01/app/oracle
export ORACLE_SID=ORCL19C
export LD_LIBRARY_PATH=/usr/lib:$ORACLE_HOME/lib
export PATH=$ORACLE_HOME/bin:$PATH
export ORA_INVENTORY=/u01/app/oraInventory
export ORACLE_HOSTNAME= gdclab2187vml

$ source .bash_profile

[oracle@ip-172-31-54-158 ~]$ cd $ORACLE_HOME

[oracle@ip-172-31-54-158 dbhome_1]$ vi l.sh                     [copy the content by clicking insert option don't forget]
contents:
#!/bin/sh

#
# Generated on Fri May 10 21:49:53 PDT 2024
# Start of user configurable variables
#
LANG=C
export LANG

#Trap to cleanup cookie file in case of unexpected exits.
trap 'rm -f $COOKIE_FILE; exit 1' 1 2 3 6 

# SSO username 
printf 'SSO User Name:' 
read SSO_USERNAME

# Path to wget command
WGET=/usr/bin/wget

# Log directory and file
LOGDIR=.
LOGFILE=$LOGDIR/wgetlog-$(date +%m-%d-%y-%H:%M).log

# Print wget version info 
echo "Wget version info: 
------------------------------
$($WGET -V) 
------------------------------" > "$LOGFILE" 2>&1 

# Location of cookie file 
COOKIE_FILE=$(mktemp -t wget_sh_XXXXXX) >> "$LOGFILE" 2>&1 
if [ $? -ne 0 ] || [ -z "$COOKIE_FILE" ] 
then 
 echo "Temporary cookie file creation failed. See $LOGFILE for more details." |  tee -a "$LOGFILE" 
 exit 1 
fi 
echo "Created temporary cookie file $COOKIE_FILE" >> "$LOGFILE" 

# Output directory and file
OUTPUT_DIR=.
#
# End of user configurable variable
#

# The following command to authenticate uses HTTPS. This will work only if the wget in the environment
# where this script will be executed was compiled with OpenSSL.
# 
 $WGET  --secure-protocol=auto --save-cookies="$COOKIE_FILE" --keep-session-cookies --http-user "$SSO_USERNAME" --ask-password  "https://edelivery.oracle.com/osdc/cliauth" -a "$LOGFILE"

# Verify if authentication is successful 
if [ $? -ne 0 ] 
then 
 echo "Authentication failed with the given credentials." | tee -a "$LOGFILE"
 echo "Please check logfile: $LOGFILE for more details." 
else
 echo "Authentication is successful. Proceeding with downloads..." >> "$LOGFILE" 
 $WGET --load-cookies="$COOKIE_FILE" "https://edelivery.oracle.com/osdc/softwareDownload?fileName=V982063-01.zip&token=ZW9qQVNpYml1cTVPNG05TXdCWmlXQSE6OiFmaWxlSWQ9MTA0NDg4MDA2JmZpbGVTZXRDaWQ9OTAxMzc3JnJlbGVhc2VDaWRzPTg5NDk4MiZwbGF0Zm9ybUNpZHM9MzUmZG93bmxvYWRUeXBlPTk1NzY0JmFncmVlbWVudElkPTEwNzU5ODExJmVtYWlsQWRkcmVzcz1haml0aHZrYW55YWt1bWFyaUBnbWFpbC5jb20mdXNlck5hbWU9RVBELUFKSVRIVktBTllBS1VNQVJJQEdNQUlMLkNPTSZpcEFkZHJlc3M9MjQwNToyMDE6ZTAwNTozODc1OjgwNWI6ZDdlYTpjYzMwOjZlMmYmdXNlckFnZW50PU1vemlsbGEvNS4wIChXaW5kb3dzIE5UIDEwLjA7IFdpbjY0OyB4NjQpIEFwcGxlV2ViS2l0LzUzNy4zNiAoS0hUTUwsIGxpa2UgR2Vja28pIENocm9tZS8xMjQuMC4wLjAgU2FmYXJpLzUzNy4zNiZjb3VudHJ5Q29kZT1JTiZkbHBDaWRzPTEwNjMyMDk" -O "$OUTPUT_DIR/V982063-01.zip" >> "$LOGFILE" 2>&1 
fi 

# Cleanup
rm -f "$COOKIE_FILE" 
echo "Removed temporary cookie file $COOKIE_FILE" >> "$LOGFILE" 






[oracle@ip-172-31-54-158 dbhome_1]$ sh l.sh

SSO User Name:ajithvkanyakumari@gmail.com         [oracle edelivery cloud username & pass]
Password:
[oracle@ip-172-31-54-158 dbhome_1]$ ls -l         [just check the size of the zip file, coz sometimes the content of the wget we downloaded would change]

[check the sha value, 
 $sha256sum <zipfile>
 it will give a result, cross check it with sha value of original wget we downloaded in the website
 both should match, otherwise delete the l.sh content and paste it with wget content]
 
[diff checker - used to find out the difference between two contents]
 
[oracle@ip-172-31-54-158 dbhome_1]$ unzip V982063-01.zip
 
last content of unziping process
  javavm/admin/classes.bin -> ../../javavm/jdk/jdk8/admin/classes.bin
  javavm/admin/libjtcjt.so -> ../../javavm/jdk/jdk8/admin/libjtcjt.so
  jdk/jre/bin/ControlPanel -> jcontrol
  javavm/admin/lfclasses.bin -> ../../javavm/jdk/jdk8/admin/lfclasses.bin
  javavm/lib/security/cacerts -> ../../../javavm/jdk/jdk8/lib/security/cacerts
  javavm/lib/sunjce_provider.jar -> ../../javavm/jdk/jdk8/lib/sunjce_provider.jar
  javavm/lib/security/README.txt -> ../../../javavm/jdk/jdk8/lib/security/README.txt
  javavm/lib/security/java.security -> ../../../javavm/jdk/jdk8/lib/security/java.security
  jdk/jre/lib/amd64/server/libjsig.so -> ../libjsig.so

[oracle@ip-172-31-54-158 dbhome_1]$ export CV_ASSUME_DISTID=OL7

[oracle@ip-172-31-54-158 dbhome_1]$
./runInstaller -ignorePrereq -waitforcompletion -silent \
 -responseFile ${ORACLE_HOME}/install/response/db_install.rsp \
 oracle.install.option=INSTALL_DB_SWONLY \
 ORACLE_HOSTNAME=${ORACLE_HOSTNAME} \
 UNIX_GROUP_NAME=oinstall \
 INVENTORY_LOCATION=${ORA_INVENTORY} \
 SELECTED_LANGUAGES=en,en_GB \
 ORACLE_HOME=${ORACLE_HOME} \
 ORACLE_BASE=${ORACLE_BASE} \
 oracle.install.db.InstallEdition=EE \
 oracle.install.db.OSDBA_GROUP=dba \
 oracle.install.db.OSBACKUPDBA_GROUP=dba \
 oracle.install.db.OSDGDBA_GROUP=dba \
 oracle.install.db.OSKMDBA_GROUP=dba \
 oracle.install.db.OSRACDBA_GROUP=dba \
 SECURITY_UPDATES_VIA_MYORACLESUPPORT=false \
 DECLINE_SECURITY_UPDATES=true
 
 Launching Oracle Database Setup Wizard...                     [it will show some warning don't need to bother that]

[WARNING] [INS-13014] Target environment does not meet some optional requirements.
   CAUSE: Some of the optional prerequisites are not met. See logs for details. installActions2024-05-11_09-09-34AM.log
   ACTION: Identify the list of failed prerequisite checks from the log: installActions2024-05-11_09-09-34AM.log. Then either from the log file or from installation manual find the appropriate configuration to meet the prerequisites and fix it manually.
The response file for this session can be found at:
 /u01/app/oracle/product/19.0.0/dbhome_1/install/response/db_2024-05-11_09-09-34AM.rsp

You can find the log of this install session at:
 /tmp/InstallActions2024-05-11_09-09-34AM/installActions2024-05-11_09-09-34AM.log

As a root user, execute the following script(s):
        1. /u01/app/oraInventory/orainstRoot.sh
        2. /u01/app/oracle/product/19.0.0/dbhome_1/root.sh

Execute /u01/app/oraInventory/orainstRoot.sh on the following nodes:
[ip-172-31-62-176]
Execute /u01/app/oracle/product/19.0.0/dbhome_1/root.sh on the following nodes:
[ip-172-31-62-176]


Successfully Setup Software with warning(s).
Moved the install session logs to:
 /u01/app/oraInventory/logs/InstallActions2024-05-11_09-09-34AM

 
 
 
 
 [try to connect to sqlplus]
 
 [oracle@ip-172-31-62-176 dbhome_1]$ sqlplus /

SQL*Plus: Release 19.0.0.0.0 - Production on Sat May 11 09:13:02 2024
Version 19.3.0.0.0

Copyright (c) 1982, 2019, Oracle.  All rights reserved.

ERROR:
ORA-01034: ORACLE not available
ORA-27101: shared memory realm does not exist
Linux-x86_64 Error: 2: No such file or directory
Additional information: 4376
Additional information: 2079936291
Process ID: 0
Session ID: 0 Serial number: 0


Enter user-name: sqlplus / sys as sysdba
Connected to an idle instance.

SQL>


[next is for creating database]

[oracle@ip-172-31-54-158 dbhome_1]$cd bin


	dbca -silent -createDatabase                            \
     -templateName General_Purpose.dbc                  \
     -gdbname ${ORACLE_SID} -sid  ${ORACLE_SID}         \
     -characterSet AL32UTF8                             \
     -sysPassword enterDB#123                           \
     -systemPassword enterDB#123                        \
     -createAsContainerDatabase false                   \
     -totalMemory 2000                                  \
     -storageType FS                                    \
     -datafileDestination /u01/db_files                 \
     -emConfiguration NONE                              \
     -ignorePreReqs -sampleSchema true
	 
Prepare for db operation
10% complete
Copying database files
File "/etc/oratab" is not accessible.
40% complete
Creating and starting Oracle instance
42% complete
46% complete
50% complete
54% complete
58% complete
60% complete
Completing Database Creation
66% complete
69% complete
70% complete
Executing Post Configuration Actions
100% complete
Database creation complete. For details check the logfiles at:
 /u01/app/oracle/cfgtoollogs/dbca/ORCL19C.
Database Information:
Global Database Name:ORCL19C
System Identifier(SID):ORCL19C
Look at the log file "/u01/app/oracle/cfgtoollogs/dbca/ORCL19C/ORCL19C.log" for further details.
	 

#wine-staging-lol


wine (master)+staging+lol patch(64496 and 64507)

To make it work, please run as root:
echo 0 > /proc/sys/abi/vsyscall32

as explained in https://bugs.winehq.org/show_bug.cgi?id=47198#c40:
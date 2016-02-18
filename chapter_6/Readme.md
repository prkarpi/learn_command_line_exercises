#Chapter_6

> What's in the tmp directory?

Vassio-Book:/ $ cd tmp


Vassio-Book:tmp $ ls
KSOutOfProcessFetcher.501.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
com.apple.launchd.HXxqvmgy8l
com.apple.launchd.M09aksjUAz
com.apple.launchd.d6IyPeptMU
com.apple.launchd.ymS73ldWHC


> Can you show me what files are in that directory?

Vassio-Book:tmp $ ls -lr
total 0
drwx------  3 user  wheel  102 Feb 14 14:59 com.apple.launchd.ymS73ldWHC
drwx------  3 user  wheel  102 Feb 13 19:15 com.apple.launchd.d6IyPeptMU
drwx------  3 user  wheel  102 Feb 14 14:59 com.apple.launchd.M09aksjUAz
drwx------  3 user  wheel  102 Feb 13 19:15 com.apple.launchd.HXxqvmgy8l
drwx------  3 user  wheel  102 Feb 17 16:39 KSOutOfProcessFetcher.501.sAglCyxY5lzPoNgfmEvv-ZqGl-w=


> What files are in your home directory?

Vassio-Book:/ $ ls
Applications              bin                       net
Library                   cores                     private
Network                   dev                       sbin
System                    etc                       tmp
Users                     home                      usr
Volumes                   installer.failurerequests var


> What's in slash temp?

From my root directory I 'cd tmp' and the results are as follows:

Vassio-Book:/ $ ls
Applications              bin                       net
Library                   cores                     private
Network                   dev                       sbin
System                    etc                       tmp
Users                     home                      usr
Volumes                   installer.failurerequests var


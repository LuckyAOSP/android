# LuckyOS is an Android Open Source Project

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using theese trees, use a command like this:

    repo init -u https://github.com/LuckyAOSP/android.git -b aosp-11

Then to sync up:

    repo sync -c -j$(nproc --all)


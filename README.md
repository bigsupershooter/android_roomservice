Getting Started
To get started with Android/LineageOS, you'll need to get familiar with Git and Repo.

To initialize your local repository, in the directory of your choice, using the LineageOS trees, use a command like this:

cd /PATH/TO/YOUR/SOURCE/DIRECTORY

repo init -u git://github.com/LineageOS/android.git -b cm-11.0

if you want less download time and no git history so save bandwidth, add --depth=1 to the end of the repo init command.

to bring in the needed stuffs for the Evo 3d CDMA (shooter):

git clone https://github.com/bigsupershooter/android_roomservice.git .repo/local_manifests/ -b cm-11.0

Then to sync up:

repo sync

if you want less download and no git history so save bandwidth, add --depth=1 to the end of the repo init command.
Please see the LineageOS Wiki for building instructions.

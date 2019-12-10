# android_device_xiaomi_platina-10

https://fdn.gsmarena.com/imgroot/reviews/18/xiaomi-mi-8-lite/lifestyle/-728w2/gsmarena_006.jpg

extract stock_kernel.tar.gz

to compile

. build/envsetup.sh

lunch omni_platina-eng

export ALLOW_MISSING_DEPENDENCIES=true # Only if you use minimal twrp tree.

make -j9 recoveryimage

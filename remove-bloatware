#!/bin/bash

for package in com.miui.analytics com.xiaomi.mipicks com.miui.systemAdSolution com.miui.daemon com.xiaomi.ab com.xiaomi.glgm com.xiaomi.joyose com.xiaomi.payment com.miui.video com.miui.videoplayer com.miui.player com.xiaomi.scanner com.miui.yellowpage com.xiaomi.midrop com.miui.notes com.miui.weather2 com.miui.compass com.android.browser com.facebook.system com.facebook.appmanager com.facebook.services com.miui.cloudservice com.miui.cloudbackup com.miui.backup com.miui.cleaner com.xiaomi.xmsf com.miui.screenrecorder cn.wps.xiaomi.abroad.lite com.xiaomi.discover com.xiaomi.calendar com.xiaomi.barrage com.xiaomi.micloud.sdk com.xiaomi.account \
com.miui.msa.global com.miui.screenrecorder com.miui.gallery com.miui.mediaeditor com.miui.android.fashiongallery com.miui.qr com.miui.bugreport com.miui.phrase com.miui.mediaviewer com.miuix.editor com.miui.touchassistant com.miui.aod com.miui.misound com.miui.mishare.connectivity com.miui.micloudsync com.miui.miservice
do
    adb shell pm uninstall -k --user 0 "$package"
done

adb shell pm disable-user --user 0 com.miui.screenrecorder

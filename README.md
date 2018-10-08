# MyHookzz
Fork from HookZz-MASTER

# windows build Android
#>>> set path=%path%;D:\Android_SDK_Tools\cmake\3.6.4111459\bin
#>>> set ANDROID_NDK=D:\Android_SDK_Tools\ndk-bundle
## arm64
#>>> cmake .. -G "Android Gradle - Ninja" -DCMAKE_TOOLCHAIN_FILE=%ANDROID_NDK%\build\cmake\android.toolchain.cmake -DANDROID_NDK=%ANDROID_NDK% -DCMAKE_BUILD_TYPE=Release -DANDROID_ABI=arm64-v8a -DZPLATFORM=Android -DZARCH=arm64
#>>> ninja
## armv7
#>>> cmake .. -G "Android Gradle - Ninja" -DCMAKE_TOOLCHAIN_FILE=%ANDROID_NDK%\build\cmake\android.toolchain.cmake -DANDROID_NDK=%ANDROID_NDK% -DCMAKE_BUILD_TYPE=Release -DANDROID_ABI=armeabi-v7a -DZPLATFORM=Android -DZARCH=armv7
#>>> ninja
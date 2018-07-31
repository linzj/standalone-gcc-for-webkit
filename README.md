compile with command:
cmake -DCMAKE_TOOLCHAIN_FILE=../Tools/android/android.toolchain.cmake -DCMAKE_BUILD_TYPE=Debug -DANDROID_STANDALONE_TOOLCHAIN=dest-dir_for/standalone-gcc -DANDROID_ABI="armeabi-v7a with NEON"  -DPORT=Android   -G Ninja ..

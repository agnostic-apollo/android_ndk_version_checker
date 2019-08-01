# Android NDK Version Checker

Usage:

Run `get_ndk_version.sh` and `assert_ndk_version.sh` for full usage guide and also check the scripts themselves.
Also check `test.sh` for examples on how to use the commands in bash scripts.

Get Android NDK full version:  
	`get_ndk_version.sh a "$ANDROID_NDK_ROOT"`

Get Android NDK major version:  
	`get_ndk_version m "$ANDROID_NDK_ROOT"`

Check if Android NDK version is atleast 19.0.0:  
	`assert_ndk_version.sh 19.0.0 "$ANDROID_NDK_ROOT"`


Credits for original script:  
[jorgenpt](https://gist.github.com/jorgenpt/1961404)


Currently used [here](https://github.com/agnostic-apollo/Android-NDK-Cross-Compile-Build-Automator).




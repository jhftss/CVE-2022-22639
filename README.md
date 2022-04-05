# Details 
See Blog:

https://www.trendmicro.com/en_us/research/22/d/macos-suhelper-root-privilege-escalation-vulnerability-a-deep-di.html

# Exploitation of CVE-2022-22639
1. Compile with command:
`clang exploit.m -o /tmp/exploit -framework Foundation -fobjc-arc -fobjc-link-runtime /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/System/Library/PrivateFrameworks/SoftwareUpdate.framework/Versions/A/SoftwareUpdate.tbd`
2. Unzip **InstallAssistant.gz** to `/tmp` folder
3. run `/tmp/exploit`

# Demo
https://www.youtube.com/watch?v=-vbkTLHh874

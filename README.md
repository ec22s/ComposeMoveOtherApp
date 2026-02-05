# ComposeMoveOtherApp

フォーク元 https://github.com/momomomo111/ComposeMoveOtherApp

2026年2月 Java 21でビルドできるようにし、フォーク元にPull Requestしました → https://github.com/momomomo111/ComposeMoveOtherApp/pull/1

ビルド時は環境変数 `ANDROID_HOME` またはリポジトリのトップにファイル `local.properties` を置いてAndroid SDKへのパスを示す必要があります. 後者の場合、例えばmacでは以下のように
```
sdk.dir=/Users/ユーザ名/Library/Android/sdk
```

ビルドできた環境
```
Android Studio Otter 3 Feature Drop | 2025.2.3
Build #AI-252.28238.7.2523.14688667, built on January 9, 2026
Runtime version: 21.0.8+-14196175-b1038.72 x86_64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
Toolkit: sun.lwawt.macosx.LWCToolkit
macOS 15.7.3
GC: G1 Young Generation, G1 Concurrent GC, G1 Old Generation
Memory: 2048M
Cores: 20
Metal Rendering is ON
Registry:
  ide.experimental.ui=true
```

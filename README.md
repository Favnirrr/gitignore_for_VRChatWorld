# 概要
VRChatワールドのgit管理用gitignoreテンプレートです。
以下のignore情報を追加しています。
## Sample Assets
/[Aa]ssets/Scenes/VRCDefaultWorldScene*
/[Aa]ssets/UdonSharp*
XR/
## blend1ファイル
*.blend1
## VRChat related folder to be ignored
Assets/Udon/
Assets/VRChat Examples/
Assets/VRCSDK
## 有名外部アセットの無視
Assets/Samples/
Assets/Bakery/
Assets/Editor/
Assets/UdonSharp/
Assets/VRWorldToolkit/
## SerializedUdonPrograms
（Udonコンパイル時の自動生成ファイル）
Assets/SerializedUdonPrograms

# 参考
https://github.com/github/gitignore/blob/main/Unity.gitignore

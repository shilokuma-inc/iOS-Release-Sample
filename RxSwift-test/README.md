## 概要
RxSwift-Test

### 目的
- RxSwiftのPrivacy Manifest対応が不明なため、.privacy ファイルを含めなかった際にWarningが出るか検証するため。

### 手段
- 空のプロジェクトファイルにRxSwiftを CocoaPods で導入し本申請をかける

### 結果
以下のWarningが出た。
Privacy Manifest関連のWarningは発生しなかった
![](/Resources/Images/RxSwift-Application_1.png)
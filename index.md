# 導入方法

「[lilToon](https://lilxyzw.booth.pm/items/3087170)」を予めインポートしてください。

SnapCamera.unitypackageをインポート後、Assets > SnapCamera内に各種データが格納されています。


## VirtualLens2

__必ずろじらぼ様の[セットアップガイド](http://static.logicmachine.jp/vlens2/docs/setup/)をご覧になってセットアップを行って下さい。__ 以下、補足です。

- VirtualLens2を利用される方は __`SnapCamera_VirtualLens.prefab`__ を利用して下さい。

- Virtual Lens SettingsのCamera Objectでは、Root Objectに `SnapCamera_VirtualLens` をNon-Preview Rootに `SnapCamera_Mesh` を設定して下さい。

![](https://raw.githubusercontent.com/foxibis/snapcamera-docs/master/images/SC-manual_02.png)

- Hideable Meshesに `SnapCamera_Mesh` を設定するとカメラモデルの非表示表示オプションが使えるようになります。

![](https://github.com/foxibis/snapcamera-docs/blob/master/images/SC-manual_04.png?raw=true)

## VRCLens

__必ずひらびきWORKS様の[ドキュメント](https://docs.google.com/document/d/1YqKdZEr36GMuExzHze7eIEDZYBVd_6fJsRASOPaRFUc/edit?usp=sharing)をご覧になってからセットアップを行って下さい。__ 以下、補足です。

- VRCLensを利用される方は __`SnapCamera.prefab`__ をSceneに配置後、調整はせず(Position/RotationがXYZ0の状態)セットアップにてChange Camera Modelを押して下さい。その後VRC Lens SetupにてScaleなど調整して下さい。

- 個人的に使用しているパラメーターを添付するので参考にどうぞ

![](https://github.com/foxibis/snapcamera-docs/blob/master/images/SC-manual_03.png?raw=true)
# 更新履歴

| Data       | Version | About   |
|:----------:|:-------:|:--------|
| 2020/09/30 | 1.0     | 販売開始 |
| 2020/11/13 | 2.0     | モデルデーターを変更しました。(見た目は変わりません) <br> UV見直しに伴いテクスチャが大幅に変更されています。 <br> PSDを追加 <br> ストラップ(DynamicBoneセットアップ済)を追加 |
| 2021/04/27 | 2.1     | Boneを修正したため以前とDynamicBoneの挙動が変わっています <br> Prefab内構造を見直しセットアップがしやすくなっています <br> オンラインドキュメントを追加 |
| 2022/05/04 | 2.2     | シェーダーをlilToonに変更 <br> ストラップのPhysBones対応 <br> FBXのインポート設定を修正 |

# 規約

基本的に良識の範囲内でご利用いただければ問題ありません。

VN3ライセンスを採用しています。詳しくは[コチラ](https://drive.google.com/file/d/17SH3o9QpT2s8uz86N5zk5N1bJwi0FS5h/view?usp=sharing)


# お問い合わせ

本モデルデーターに関して不具合や質問等などございましたら下記へご連絡下さい。

Twitter [@FoxIbis](https://twitter.com/foxibis)

Discord ふぉっくす#9951

# Unity_GameFeat_Demo

__Q「Unityで、GameFeatSDKを使うコツは・・・」__
Unityで、GameFeatSDKを、機能させるためには、Manifestの設定が、必要です。
しかし、公式のアセットに付属しているManifestは、古く、最新のユニティに対応していないため、
一度、空のプロジェクトを作り、Android用にビルドし、そのapkから、Manifestを取り出し、移植することで、
エラーを回避する必要がありました、このManifestの修整は、アップデートされる度に必要だと思えます。

__Q「GameFeatUnitySDKは、単独で、使用可能か・・・」__
GameFeatUnitySDKには、GameFeatSDKが、読み込まれているために、相互にjarファイルが、必要です。
実際に、アプリ登録し、idを入れ、ストア公開すると、白の枠に、相互相客などの広告、表示されるものと思われます。
一応、表示までは、出来たので、ベースにご利用下さい。（Unity 2020.3.30f1を、利用・・・）

>https://www.gamefeat.net/



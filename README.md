### Аннотация


Unity3D WebView плагин для iOS и Android, для отображение данных в html формате, по верх основного окна приложения.

![Скриншот](IMG_0004.jpg)

На рисунке показано 

### Краткий комментарий

#### Unity 側

[Assets/Plugins/WebMediator.js](https://github.com/keijiro/unity-webview-integration/blob/master/unity/Assets/Plugins/WebMediator.js) が Unity 側の窓口となるスクリプトです。このスクリプトを通して web view の表示制御、配置マージン設定、指定 URL のロードを行うことができます。また、web view 内から送信されたメッセージをここから拾い上げることができます。詳しい使用方法についてはサンプルプロジェクトの [TestInterface.js](https://github.com/keijiro/unity-webview-integration/blob/master/unity/Assets/Scripts/TestInterface.js) を参照してください。

#### Web view 側

Web view 側からメッセージを送信するには [unity.js](https://github.com/keijiro/unity-webview-integration/blob/gh-pages/unity.js) をインポートし、この中で定義されている `UnityWebMediator` クラスを用いる必要があります。詳しい使用方法についてはサンプルプロジェクトの [index.html](https://github.com/keijiro/unity-webview-integration/blob/gh-pages/index.html) を参照してください。

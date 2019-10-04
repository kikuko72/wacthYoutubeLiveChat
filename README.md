# wacthYoutubeLiveChat
Youtubeのライブチャットの勢いを監視する感じです

クエリに以下のパラメータを指定してhtmlを開きます。
ライブチャットの勢いがしきい値を超えて加速するとビープ音が鳴ります。

 - **apiKey**: GCPのAPIキー(自分の)
 - **liveChatId**: ライブチャットID。https://www.googleapis.com/youtube/v3/videos?part=LiveStreamingDetails&id=pPzlpbramt8&key={YOUR_API_KEY} で取得できます。
 - **threshold**(Optional): 何%加速したら鳴らすか。デフォルト5。

beep音は次のページを参考にしました。:
JavaScript で Beep 音を鳴らす方法 - Qiita
https://qiita.com/isseium/items/12b215b6eab26acd2afe
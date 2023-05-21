# 3-cool-controller
3年生時の特別研究で作成した。研究題目は「理想のかっこいいコントローラ」である。

## How it started
人に魅せるためのロボット用コントローラを世間であまり見ないので作成したいと考え、班員と共同制作にあたった。
デザインは遊戯王に登場するデュエルディスクを参考にした。
任意の効果を持つカードを読み取り、その通りに動作するロボットとコントローラを製作した。

## Controller
RFIDを用いてカードリーダをいくつかコントローラを埋め込み、任意の場所に当てるとカードを読み取るようにしている。
また、かっこよさを引き出すために指紋認証を取り入れ、登録した人が触れることにより、カードを読み取れるようになる。
指紋認証により起動したとき起動音が鳴るようにしている。
RFIDのカードリーダー、指紋認証、ロボットとの通信、起動音、読み取られたカードの表示を行うためコンパクトかつモジュールが豊富なm5stackをコントローラ側のマイコンとしている。
ロボットにはm5stampを搭載し、bluetoothで通信する。
実際に制作したコントローラの全体を下に添付する。RFIDのカードリーダや指紋認証のモジュールは見えないように上から青い板で隠している。


![2023-05-21_22h55_56](https://github.com/hossyan/3-cool-controller/assets/118952234/66f4e845-4560-4015-bf2c-a8c4b0e8073e)


## Robot
ロボットは時間がなかったためosoyooが販売しているメカナムホイールのロボットにアームをつけ足して作るようにして作成した。

購入したロボットはこちら⇒[osoyoo メカナムホイール](https://www.amazon.co.jp/Arduino%E9%81%A9%E7%94%A8-%E3%82%B9%E3%83%9E%E3%83%BC%E3%83%88%E3%83%AD%E3%83%9C%E3%83%83%E3%83%88-360%C2%B0%E5%85%A8%E6%96%B9%E5%90%91%E7%A7%BB%E5%8B%95-directional-Arduino%E7%94%A8%E9%9B%BB%E5%AD%90%E9%83%A8%E5%93%81%E3%82%AD%E3%83%83%E3%83%88/dp/B082D5HPZD/ref=asc_df_B082D5HPZD/?tag=jpgo-22&linkCode=df0&hvadid=493939641561&hvpos=&hvnetw=g&hvrand=16296484007363475093&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1009522&hvtargid=pla-1238612417498&psc=1)

アームは平行リンクで動くようにしている。
全体像は以下の通り。


![2023-05-21_23h24_40](https://github.com/hossyan/3-cool-controller/assets/118952234/3522c880-721d-44a2-9c43-6b3d079523c0)

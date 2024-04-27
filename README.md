# techTeCraft
**techTeCraft**は、TECH☆TECHの公式Minecraftサーバーです。
基本的にTECH☆TECHのメンバーが遊ぶことができます。

# 基本情報
- Minecraft Java Edition 1.16.5
- MohistMC（PaperMC・Forgeフォーク）
- サバイバルモード
- 工業・建築・インフラ系

# 準備
大前提として、Minecraft Java Editionの有効なライセンスが必要です。
また、このサーバーはセキュリティ対策のため、ホワイトリスト方式を使っています。接続したいユーザーはDiscordで大渕にユーザーIDを伝えてください。何もせずに接続しても弾かれます。
## Java8のインストール
Minecraft1.16.5はJava8を要求します。既にインストールされているならそれを使いますが、ない場合は新たにインストールしてください。
お使いのOSとアーキテクチャに対応したものであれば、どのディストリビューションでも構いません。多くの場合はWindows x64か、macOS aarch64のどちらかだと思います。
[Amazon Corretto 8](https://docs.aws.amazon.com/ja_jp/corretto/latest/corretto-8-ug/downloads-list.html)
## インスタンスの作成
サーバーと同じMODを正確に導入する必要があるため、既存のインスタンスを使うよりも新規作成したほうがよいでしょう。
> Readmeでは[Prism Launcher](https://prismlauncher.org/download/)を想定して説明しますが、他のランチャーソフトでも基本操作は同じだと思います。
1. バージョンは1.16.5、MODローダーはForgeを選んでインスタンスを作成します。
2. MODは軽量化MODのみ導入してください。特にこだわりが無ければOptiFineを導入すれば良いです。お好みで。
3. シェーダーパックもお好みで導入してください。
4. 使用するJavaが正しく選択されていなければ修正してください。またメモリー割当も4GBなど小さいままだったら適宜増やしてください。

# MODの導入
ランチャーソフトのMOD導入機能は便利ですが、その時点で入手できる最新のリリースを導入してしまいます。MODのバージョンはサーバーとクライアントで一致させる必要があるので、今回は手動で導入してください。
DMCAの関係で、必要なファイル群をまとめて再配布することができないので、以下の一覧から一つづつダウンロードしてください。
## ストレージ系
- **Quantum Storage** `1.16.5-5.3.0` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/quantumstorage/download/3103918)
- **Iron Chests** `1.16.5-11.2.21` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/iron-chests/download/3543538)
- **Ender Storage** `1.16.5-2.8.0.170-universal` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/ender-storage-1-8/download/3737982)
## インベントリ系
- **Inventory Profiles Next** `forge-1.16-1.10.6` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/inventory-profiles-next/download/4753602)
- **JustEnoughItems** `1.16.5-7.8.0.1009` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/jei/download/4371666)
## 工業系
- **Mekanism** `1.16.5-10.1.2.457` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/mekanism/download/3659389)
- **Create** `1.16.5_v0.3.2g` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/create/download/3536025)
- **FlyWheel(Legacy)** `1.16-0.2.5` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/flywheel/download/3535459)
## インフラ系
- **Ultimate Car Mod** `1.16.5-1.0.17` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/ultimate-car-mod/download/3310670)
- **Transit Railway** `forge-1.16.5-3.2.0` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/minecraft-transit-railway/download/4358196)
## その他
- **libIPN** `forge-1.16-3.0.2` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/libipn/download/4574569)
- **Kotlin for Forge** `1.17.0-obf` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/kotlin-for-forge/download/3675495)
- **CodeChickenLib** `1.16.5-4.0.7.445-universal` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/codechicken-lib-1-8/download/3681973)
- **Architectury API** `1.32.68` [ダウンロード](https://www.curseforge.com/minecraft/mc-mods/architectury-api/download/4521290)
## 導入
MODの設定タブで`ファイルを追加`をクリックし、ダウンロードした.jarファイルを選択して開いてください。

# 接続
Minecraftを起動し、適宜設定を最適化したら、サーバーに接続します。
1. `マルチプレイ`メニューを開き、`サーバーを追加`をクリックしてください。
2. サーバー名はなんでも構いませんが、**techTeCraftサーバー**などの名前を推奨します。
3. サーバーアドレスは`techtecraft.nid-techtech.com`です。
	- サーバーを追加せずに、ダイレクト接続のメニューでこのアドレスを入力することもできます。
4. サーバー一覧を更新すると、サーバーがオンラインであればアンテナマークが立ちます。
5. サーバーを選択して接続します。サーバーのホワイトリストに登録されたユーザーIDと一致すれば、サーバーにログインできます。

# プラグイン
いくつかのプラグインを導入しています。以下の通りです。
- Bluemap
- Chairs
- Dead Chest
- DecentHolograms
- GSit
- Health Bar
- LunaChat
- LWC Extended

プラグインはMODと違って、クライアントには何も導入する必要がありません。
サーバーに接続するだけで各種機能が使えるようになります。
## BlueMap
インタラクティブな2D/3Dマップを使えるようにするプラグインです。
マップはブラウザベースで動作します。URLは[bluemap.nid-techtech.com](https://bluemap.nid-techtech.com)です。
閲覧にはメールアドレス認証が必要です。長岡造形大学から配布されたメールアドレスを入力し、送られてきた認証コードを入力してください。
## LunaChat
ローマ字で入力されたテキストチャットを自動で日本語に変換するプラグインです。
テキストチャットで日本語を入力するのは面倒ですが、このプラグインによってIME切替なしで日本語を送信できます。ただし誤変換など一切考慮してくれないので判断オブ判断になります。
# その他
私は今までサバイバルをプレイしたことが無いので、いろいろわかりません（インベントリの使い方とか空腹の概念とか夜間の安全確保とか）。ご教示お願いします。

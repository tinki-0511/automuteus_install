# AutoMuteUs 導入手順

## AutoMuteUsのインストール(初回のみ)
1. [AutoMuteUs](https://github.com/denverquane/automuteus)にアクセス  
1. GIF画像をクリック  
![bot_link](./img/bot_link.png)  
1. DiscordサーバーにAutoMuteUsインストールする  
![accept_bot](./img/accept_bot.png)  
![register](./img/register.png)  
1. Discordのユーザー設定からDMを許可する  
![DM_enable](./img/DM_enable.png)  

## AmongUsCaptureのインストール(ゲームのホストユーザーのみ。初回のみ)
DiscordとAmongUsを連携するアプリケーション  
1. [AmongUsCapture](https://github.com/denverquane/amonguscapture/releases/tag/2.4.4)にアクセス  
1. AmongUsCapture.exeを任意の場所にダウンロード  
![capture](./img/capture.png)  
1. 実行してインストール(Windowsの警告が出るので許可する)  
**インストール後はAmongUsCapture.exeの場所を移動させない**  
![capture_install1](./img/capture_install1.png)  
![capture_install2](./img/capture_install2.png)  

## 使用方法
### ホストの操作
AmongUsCaptureが起動している場合は終了させておく  
1. AmongUsで部屋を作成する  
1. Discordのチャットで`.au new`を入力する  
![au_new](./img/au_new.png)  
Main Menuが表示される  
![au_new_before](./img/au_new_before.png)  
1. AutoMuteUsからDMが届くのでリンクをクリックする    
![DM](./img/DM.png)  
![DM_link](./img/DM_link.png)  
1. AmongUsCaptureが実行され、Main Menuの表示が変わる  
自分のキャラクターの色のアイコンをクリックする  
![good_job](./img/good_job.png)  
1. Unlinkedが自分の名前になれば成功  
![icon_click](./img/icon_click.png)  

### ゲストの操作
ルームコードでゲームに参加し、自分の色のアイコンをクリック  
![join_game](./img/join_game.png)  

以上で設定は終了。  
ゲームを始めると自動でマイク・スピーカーがミュートになり、会議が始まるとミュートが解除されます。  

## ゲームの設定を変更したい場合
マップやインポスターの数を変えたい場合の手順  
1. ホストプレイヤーがルームを解体する  
1. ルームの設定を変更してルームを作成する  
1. Discordのチャットで`.au refresh`を入力する  
1. DiscordのMain Menuが更新される  
1. アイコンをクリックする  

## 終了方法
1. Discordのチャットで`.au end`を入力  
1. AmongUsCaptureを手動で終了させる  
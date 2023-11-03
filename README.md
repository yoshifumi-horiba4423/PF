# PF
# [アナタの通知表]

## サービス概要
* 「アナタの通知表」はオリジナル通知表を作成・共有することができるサービスです。通知表を作成してお世話になった人へ日常の感謝を伝えることが可能です。

## このサービスへの思い・作りたい理由
* 幼少期より何度も転校をした私は、人に感謝を伝えることでこれまで広い交友関係を築くことができました。
しかし多くの交友関係を持つことで、感謝の表現がマンネリ化したり感謝の度合いを伝えることが難しいと感じる時があったため、感謝の具合を分かりやすく表現したいと感じたことが本サービス作成のきっかけです。
人によっては手紙などの文章でうまく伝えられないこともあるため、誰でも簡単に分かりやすく表現できるように、通知表の「数字」を利用しました。
遠方に住む家族・友人・恋人などの通知表をもらう人は自分がどんな人間か改めて知る良いきっかけにもなるため、作る側・もらう側双方が幸せになることができます。

## 想定されるユーザー層
* 日頃の感謝を伝えたい人がいる人
* 感謝の思いを伝えることが苦手な人
* 自分の評価を客観的に知りたい人

## ユーザーの獲得について
* 作成した通知表・もらった通知表をSNSで共有することで認知を広げてユーザー獲得をする予定です。

## サービスの差別化ポイント・推しポイント
* 受手に合わせた通知表のカラーリングを変更できます。
* 家族向け・友人向け・夫婦向けのテンプレート通知表があり、利用シーンに応じた簡単な作成が可能です。
* 作成した通知表をX(旧Twitter)やLINEでURL共有が可能です。
* 作成した通知表は画像としても保存ができます。

## MVP
* 会員登録（ユーザーネーム、メールアドレス、パスワード）
* マイページ
  * 通知表テンプレート編集機能（評価項目変更、デザイン変更）
  * 作成済の通知表閲覧機能
* ログイン機能
* ログアウト機能
* 通知表作成機能
* 通知表のX/LINEシェア機能

## その後の機能
* 通知表への画像アップロード機能
* 通知表のコメント機能
* 次回の通知表作成提案通知（最終作成日から6ヶ月経過した場合に通知）
* 通知表カウント（もらった通知表をカウントできる）

## 機能の実装方針予定
Rails 6系、React、Twitter API

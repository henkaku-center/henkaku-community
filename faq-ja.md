# FAQ

## Coinvise botについて

### Q: チップコマンドを送ったら「Invalid format」が帰ってきました

1. 形式が正しかったか確認してください: `c!tip @tippee henkaku matic 10` （@user_to_tipはチップを受けるDiscordユーザーで、10は差し上げる$HENKAKUの数です）
1. `c!register 0x...`をもう一度送ってください。0x...はあなたのEthereumアドレスです
1. @coinvise-botからのDMで認証用のリンクが送られてきますので、ウォレットを使ってその認証を済ませてください（ETHやMATICがかかりません）
1. その後、チップコマンドを改めて送ってください

## Snapshotとproposal（提案）について

### Q: 私の投票力は私のアドレスの$HENKAKUと異なります

ある提案のための投票力は、その提案が公開されたときに投票者が持っていた$HENKAKUになります。投票するときに持っている$HENKAKUは増えてたとしても関係ありません。

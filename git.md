
# 全ファイルをステージング
git add -A

# 強制プッシュ
git push origin head -f

#　コミットログ変更
git rebase -i HEAD~~

# ローカルのブランチを削除
git branch -D <branch_name>

# コミットのコメント変更
git commit --amend

# Webリサーチ（裏取り付き）スキル

事実確認・調べもの・記事の正誤チェックなど、正確な答えと出典が必要なリサーチ用のスキル（SKILL.md）です。Claude Code のプラグインとしてそのまま入れられます。Cursor など SKILL.md 形式に対応した環境でも使えます。

- 必ずWebで確認し、記憶だけで答えない
- 公式情報を優先し、出典URLを付ける
- 結論から伝え、未確認の点は正直に書く
- 報告は短く：1行目が答え、全体3〜5行、出典はリンク1つ

## Claude Code に入れる

```
/plugin install web-research --marketplace spa77k/web-research-skill
```

古いバージョンの場合：

```
/plugin marketplace add spa77k/web-research-skill
/plugin install web-research@web-research-skill
```

入れたあとは「〇〇って本当？調べて」のように頼むと自動で使われます。`/web-research:web-research` で明示的に呼ぶこともできます。

スキル本体：[skills/web-research/SKILL.md](skills/web-research/SKILL.md)

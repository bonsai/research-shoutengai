# research-shoutengai

商店街を「場所」ではなく、地域の生活・商業・文化・人の関係として研究する。

## Research Model

```
商店街
├── location
├── history
├── shops
├── people
├── organizations
├── events
├── media
├── free_papers
├── culture
└── issues
```

## MACHINAVIとの関係

- `research-shoutengai` — 商店街を調査・研究するSoT
- `MACHINAVI` — 商店街を地域情報の一ソースとして収集・公開する
- `domain-shoutengai.jsonl` — MACHINAVIの収集入口
- `info.jsonl` — MACHINAVIが収集した地域情報

**research = 商店街について何が分かるか**  
**domain = どこを見るか**  
**info = 何が起きているか**

## Data

研究データは将来的にJSONLをcanonical formatとする。

- `data/shoutengai.jsonl`
- `data/shop.jsonl`
- `data/person.jsonl`
- `data/event.jsonl`
- `data/source.jsonl`

## Goal

商店街を「店の一覧」ではなく、

> 人・店・場所・歴史・イベント・メディアがつながった地域のデータ

として記録する。

# UCMail-docs

Official documentation and website for the **UCMail** ecosystem.

## Structure

```
docs/<locale>/   localized manuals, quick-start guides, keyboard shortcuts
site/            static website assets
```

## i18n coverage (target countries → locales)

| Country | Locales |
| --- | --- |
| South Africa | en, zu (Zulu), xh (Xhosa), af (Afrikaans) |
| Brazil | pt-BR |
| Chile | es |
| United States | en, es |
| India | hi, en |
| Indonesia | id |
| Japan | ja |
| Russia | ru |

**Canonical source: `docs/en/`.** All other locales translate from English; `pt-BR` is
maintained in parity by the author. Untranslated pages fall back to English.

## Contributing

Translations and fixes target the **`develop`** branch. Keep one file per page, mirroring
the `docs/en/` tree exactly (same filenames).

---
**Alex Jesus** · [`alexjesustech`](https://github.com/alexjesustech)

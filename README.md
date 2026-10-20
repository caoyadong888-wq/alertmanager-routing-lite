# Alertmanager Routing Templates (Lite)

## English

A severity-only Alertmanager route: critical to a PagerDuty placeholder, warning to a Slack placeholder, info to email, plus one inhibit rule and the Slack/PagerDuty template file.

Not in this subset: the team split, the email HTML template, the fan-out example, the two-team example, the local walker, and the bilingual routing guide.

### Deliverables

- `deliverables/alertmanager-severity.yml` — critical / warning / info receivers
- `deliverables/templates/slack_pager.tmpl` — `pack.slack.*` and `pack.pager.description`
- `examples/label-cases.txt` — four label rows for this file

Replace `REPLACE_ME` and `https://example.com/hooks/slack-oncall` before you load the file. Template paths are relative to `deliverables/`. Check upstream docs.

## 中文

只有严重级别、没有团队分支的 Alertmanager 路由：critical 到 PagerDuty 占位，warning 到 Slack 占位，info 到邮件。另有一条抑制规则和 Slack/PagerDuty 模板。

精简版不含：团队分支、邮件 HTML 模板、fan-out 示例、双团队示例、本地遍历脚本，以及中英路由说明。

### 交付文件

- `deliverables/alertmanager-severity.yml`
- `deliverables/templates/slack_pager.tmpl`
- `examples/label-cases.txt`

加载前请替换 `REPLACE_ME` 和 `https://example.com/hooks/slack-oncall`。模板路径相对 `deliverables/`。以官方文档为准（check upstream docs）。

Full version: GUMROAD_URL

# review-requirement

[English](#english) · [简体中文](#简体中文)

## English

`$review-requirement` reviews a draft requirement before implementation. It flags faulty assumptions, ambiguities, and gaps, then proposes a revised requirement in chat. The review is read-only. Implementation begins when you explicitly ask to proceed.

### Install in Codex

Run this in a terminal with Node.js 22.20 or later:

```bash
npx skills add ZhangNanNan1018/review-requirement --skill review-requirement -a codex -g
```

For a manual install, copy the whole [`skills/review-requirement/`](skills/review-requirement/) folder into `~/.agents/skills/` (`%USERPROFILE%\.agents\skills\` on Windows). If the skill picker doesn't show the new skill, restart Codex.

### Use

Select `$review-requirement` in the Codex prompt box and add your request:

```text
$review-requirement I want to add a CSV export to the orders page. By default, it should export all orders.
```

For this example, the skill might ask whether “all orders” means all orders matching the current filters or all orders the user has permission to view. It will propose wording for the requirement once the scope is clear.

## 简体中文

`$review-requirement` 用于在实施前评审需求。它会指出错误假设、歧义和关键遗漏，并在聊天里给出一版修订后的需求。评审期间保持只读，等你明确说开始再实施。

### 在 Codex 中安装

在装有 Node.js 22.20 或更新版本的终端执行下面的命令。

```bash
npx skills add ZhangNanNan1018/review-requirement --skill review-requirement -a codex -g
```

也可以手动安装。把整个 [`skills/review-requirement/`](skills/review-requirement/) 目录复制到 `~/.agents/skills/`，Windows 上对应 `%USERPROFILE%\.agents\skills\`。如果技能选择器里没出现，重启 Codex。

### 使用示例

在 Codex 输入框中选中 `$review-requirement`，然后写下需求。

```text
$review-requirement 我想给订单列表加 CSV 导出，默认导出全部订单。
```

技能可能会确认「全部订单」指当前筛选条件匹配的订单，还是用户有权查看的所有订单。范围明确后，它会给出相应的需求改写。

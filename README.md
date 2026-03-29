# mckinsey_zn
麦肯锡咨询skill，像一个顶级咨询专家一样处理各种复杂问题和决策。

## 安装

### 推荐 (clone 进claude的skills目录)

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/harnessbee/mckinsey_zh ~/.claude/skills/mckinsey_zh
```

### 手动安装（只移动SKILL.md文件）

需要先clone仓库，然后

```bash
cd mckinsey_zh
mkdir -p ~/.claude/skills/mckinsey_zh
cp SKILL.md ~/.claude/skills/mckinsey_zh/
```

## Usage

In Claude Code, invoke the skill:

```
/mckinsey_zh 分析08年经济危机
```

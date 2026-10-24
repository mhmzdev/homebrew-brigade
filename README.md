# homebrew-brigade

The Homebrew tap for [the Brigade](https://github.com/mhmzdev/claude-code-brigade): run several
Claude Code sessions like a professional kitchen.

```bash
brew tap mhmzdev/brigade
brew install bk
```

`bk open` starts the kitchen and sits you with the sous; `bk stop` pauses it; `bk open` again
resumes it. `bk help` for the rest. You need Claude Code installed and logged in.

`Formula/bk.rb` is written by the release workflow of `claude-code-brigade` on every release,
from the template in that repo. Don't edit it here; changes go to
[`Formula/bk.rb` there](https://github.com/mhmzdev/claude-code-brigade/blob/main/Formula/bk.rb).

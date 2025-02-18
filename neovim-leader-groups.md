# Leader

> Working Draft

A curated list of a grouping mechanism for neovim/vim Keybindings

The idea follows vim original idea of VERB --> NOUN

## [Rules]

Some rules I follow:

- Most common actions use the lowercase letter
- Less common actions use the uppercase letter
- Sometimes the uppercase variant means a bigger operation, like b (buffer), and
  B (Buffers)

## [Keybindings diagram]

```bash
Find
├── ● f - File         # f f     Find Files
├── ● b - Buffer       # f b     Find Buffer
├── ● s - Symbol       # f s     Find Symbol
├── ● k - Keybinding   # f k     Find Keybinding
├── ● g - Git
│   ├── ● b - Branch   # f g b   Find Git Branch
│   ├── ● c - Commit   # f g c   Find Git Commit
│   ├── ● s - Stash    # f g s   Find Git Stash
│   └── ● S - Status   # f g S   Find Git Status
├── ● h - Help         # f h     Find Help File
└── ● d - Diagnostic   # f d     Find Diagnostic

Toggle
├── ● n - Numbers      # t n     Toggle Relative Numbers
├── ● h - Hints        # t h     Toggle Inline Hints
├── ● f - Format       # t f     Toggle Format on Save
├── ● c - Conceal      # t c     Toggle Conceal
├── ● q - Quickfix     # t q     Toggle Quickfix
├── ● l - Lazy         # t l     Toggle Lazy Redraw
├── ● i - Lazy         # t i     Toggle Inspect Tree
├── ● b - Blame        # t b     Toggle Blame Buffer
└── ● d - Diff         # t d     Toggle Diff in Split

Open
├── ● m - Mason        # o m     Open Mason
├── ● L - Log          # o L     Log (lsp)
├── ● l - Lazy         # o l     Open Lazy
├── ● i - Info         # o m     Info (LSP)
├── ● d - Diagnostic   # s d     Show Diagnostic (current line)
├── ● a - Actions      # o a     Code Actions
├── ● e - Explorer     # o e     Open Explorer (neotree)
└── ● w - Welcome      # o w     Open Welcome Menu

Rename/Replace
├── ● s - Symbol       # r s     Rename Symbol (LSP)
├── ● b - Buffer       # r b     Rename Buffer (LSP)
└── ● w - Word         # r w     Replace Word Under cursor

Save
├── ● b - Buffer       # s b     Save Buffer
├── ● B - Buffers      # s B     Save Buffers
└── ● s - Session      # s s     Save Session

Close
├── ● b - Buffer       # c b     Close Buffer
├── ● B - Buffers      # c B     Close Buffers
├── ● o - Others       # c o     Close Other Buffers
└── ● w - Window       # c w     Close Window

## Single strokes

Quit     ── ● q - Quit neovim  # q        Quit neovim
Explorer ── ● e - Exporer      # q        Quit neovim
```

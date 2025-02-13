# Leader groups

DRAFT: A curated list of a grouping mechanism for neovim/vim Keybindings

The idea follows vim original idea of VERB --> NOUN

```bash
Find
├── ● f - Files        # f f     | Find Files
├── ● b - Buffers      # f b     | Find Buffer
├── ● s - Symbols      # f s     | Find Symbols
├── ● k - Keybindings  # f k     | Find Keybindings
├── ● g - Git
│   ├── ● b - Branches # f g b   | Find Git Branches
│   ├── ● c - Commits  # f g c   | Find Git Commits
│   ├── ● s - Stash    # f g s   | Find Git Stash
│   └── ● S - Status   # f g S   | Find Git Status
├── ● h - Help         # f h     | Find Help Files
└── ● d - Diagnostics  # f d     | Find Diagnostics

Toggle
├── ● n - Numbers      # t n     | Toggle Relative Numbers
├── ● h - Hints        # t h     | Toggle Inline Hints
├── ● f - Format       # t f     | Toggle Format on Save
├── ● c - Conceal      # t c     | Toggle Conceal
├── ● q - Quickfix     # t q     | Toggle Quickfix
│   ├── ● q - Quickfix # t q q   | Toggle Quickfix List
│   └── ● Q - Loclist  # t q Q   | Toggle Quickfix Loclist
├── ● l - Lazy         # t l     | Toggle Lazy Redraw
└── ● d - Diff         # t d     | Diff in Split

Open
├── ● l - Lazy         # o l     | Open Lazy
├── ● m - Mason        # o m     | Open Mason
└── ● w - Welcome      # o w     | Open Welcome Menu
```

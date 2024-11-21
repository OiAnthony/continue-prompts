# Continue Prompts

## Quick Start

1. Clone this repo

```bash
git clone https://github.com/oianthony/continue-prompts.git
```

2. Create symlink from prompts folder to your continue config

```bash
# Compatible with == v0.8.57  
ln -s continue-prompts/.prompts ~/.continue/.prompts

# Compatible with >= v0.9
ln -s continue-prompts/.prompts ~/.continue/prompts
```

## Notes

The continue prompt file directory has breaking changes in both v0.8.57 and v0.9

v0.8.57 global directory: ~/.continue/.prompts

v0.9 global directory: ~/.continue/prompts

Please choose the appropriate directory to create symlinks based on your continue version. You can also create symlinks for both directories.

**Note: Versions below v0.8.57 are not supported.**

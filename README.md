# Continue Prompts

A curated collection of Continue editor prompt files designed to enhance development efficiency and code quality.

## 📋 Prompt Files List

| Prompt File | Description |
|-------------|-------------|
| `commit.prompt` | Generate commit messages following Conventional Commits specification in English |
| `commit-zh.prompt` | Generate commit messages following Conventional Commits specification in Chinese |
| `code-review.prompt` | Comprehensive code review based on Google engineering practices |
| `code-smells.prompt` | Identify and fix code smells to improve code quality |
| `variable-naming.prompt` | Generate clear, descriptive variable and function naming suggestions |
| `prompt-generation.prompt` | Generate high-quality prompt files for Continue editor |
| `prompt-edit.prompt` | Edit and optimize existing prompt files |
| `mysql-table-designer.prompt` | Design and optimize MySQL database table structures |
| `fix-terminal.prompt` | Fix terminal command errors and issues |

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/oianthony/continue-prompts.git
```

### 2. Create Symbolic Links

Choose the appropriate directory based on your Continue version:

```bash
# Compatible with v0.8.57
ln -s continue-prompts/.prompts ~/.continue/.prompts

# Compatible with v0.9+
ln -s continue-prompts/.prompts ~/.continue/prompts
```

### 3. Restart Continue Editor

Restart your editor to load the new prompt files.

## 💡 Usage

1. Press `Cmd/Ctrl + Shift + P` in Continue editor to open the command palette
2. Type `@` to view available prompt files
3. Select the desired prompt file and follow the instructions

## 📝 Version Compatibility

| Continue Version | Prompt Files Directory |
|-----------------|------------------------|
| v0.8.57 | `~/.continue/.prompts` |
| v0.9+ | `~/.continue/prompts` |

**Note: Versions below v0.8.57 are not supported.**

It is recommended to create symbolic links for both directories to ensure compatibility:

```bash
ln -s continue-prompts/.prompts ~/.continue/.prompts
ln -s continue-prompts/.prompts ~/.continue/prompts
```

## 🤝 Contributing

Issues and Pull Requests are welcome to improve these prompt files!

## 📄 License

This project is licensed under the MIT License.

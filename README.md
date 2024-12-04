# 🐮 Termipals

Add joy to your terminal with ASCII art animals! Termipals brings life to your command line by summoning cute animal companions using simple commands, powered by a tiny LLM.

```bash
$ termipals moo

------------ < mooo! having a great day! > ------------
                                   \
                                    \
                                     \    ^__^
                                      \  (oo)\_______
                                         (__)\       )\/\
                                             ||----w |
                                             ||     ||
```

## ✨ Features

- **Tiny Footprint**: Uses a super-lightweight LLM (<50MB) for generating animals
- **Instant Setup**: Single pip install, LLM downloads only when needed
- **File Magic**: Inject animals into your markdown files
- **Smart Generation**: Creates contextual and fun ASCII art animals
- **Offline Support**: Works without internet once LLM is downloaded

## 🚀 Quick Start

```bash
# Install
pip install termipals

# Basic usage
termipals moo        # Show a cow
termipals meow       # Show a cat
termipals random     # Random animal

# Add to files
termipals moo README.md  # Add cow to start of README.md

# Generate new animals
termipals create hamster  # Generate ASCII art hamster
```

## 🏗 Architecture

- **Core**: Pure Python for maximum compatibility
- **LLM**: TinyLlama/phi-2 quantized to <50MB
- **Storage**: Simple file-based for easy customization
- **CLI**: Click for clean command-line interface

## 🔧 Technical Details

- Quantized LLM for tiny size (<50MB)
- ONNX runtime for fast inference
- Local caching of models and generated art
- Smart prompt engineering for ASCII generation

## 🤝 Contributing

Contributions welcome! See [CONTRIBUTING.md](docs/CONTRIBUTING.md)
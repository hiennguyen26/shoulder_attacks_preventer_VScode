# VSCode Inactivity Jumble Extension

## Overview

The VSCode Inactivity Jumble Extension enhances security against shoulder surfing attacks by automatically jumbling visible text in the editor when user inactivity is detected. Once activity resumes, the text is reverted to its original state. The extension uses a specified text file with literal strings or regex patterns to determine which text should be jumbled.

## Features

- Detects user inactivity and jumbles visible text.
- Restores original text upon detecting user activity.
- Supports literal string and regex pattern matching against a specified text file.
- Configurable inactivity duration.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/vscode-inactivity-jumble-extension.git
   cd vscode-inactivity-jumble-extension

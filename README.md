

# NetBeans Default Theme for Cursor IDE

A custom theme for Cursor IDE (based on VS Code) that replicates the default look and feel of NetBeans IDE.
## Overview

This theme brings the classic NetBeans color scheme to Cursor IDE, featuring:
- Light background with white editor and light gray sidebar.
- Green italic comments.
- Dark purple bold keywords.
- Orange variables (e.g., PHP `$variables`).
- Light blue strings and attribute values.
- Consistent styling for HTML, PHP, and other common file types.

## Installation

### Prerequisites
- Node.js and npm installed (download from [nodejs.org](https://nodejs.org/)).
- VS Code Extension CLI (`vsce`) installed globally: `npm install -g vsce`.
- Cursor IDE installed.

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/efreakiel/netbeans-default-theme.git
   cd netbeans-default-theme
   ```

2. **Package the Extension**
   Run the following command to create a `.vsix` file:
   ```bash
   vsce package
   ```
   This generates a file like `netbeans-default-theme-0.0.1.vsix`.

3. **Install in Cursor IDE**
   - Open Cursor IDE.
   - Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).
   - Click the "..." menu and select "Install from VSIX...".
   - Browse to and select the `.vsix` file.
   - Reload Cursor when prompted.

4. **Activate the Theme**
   - Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
   - Type "Preferences: Color Theme" and select it.
   - Choose "NetBeans Default" from the list.

## Usage

Once installed, the theme will apply to your Cursor IDE workspace. It is optimized for `.tpl` and `.php` files but works well with other languages too. Adjust the theme file (`themes/netbeans-default-color-theme.json`) if you need to tweak colors or scopes.

## Contributing

Feel free to fork this repository and submit pull requests for improvements or additional language support. Report issues or suggest features via the [Issues tab](https://github.com/efreakiel/netbeans-default-theme/issues).

## License

This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Inspired by the default theme of NetBeans IDE. Thanks to the Cursor and VS Code communities for their extensible platform.


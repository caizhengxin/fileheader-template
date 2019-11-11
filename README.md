# VSCode FileHeader Template

Extended ``VSCodeFileHeader`` does not exist template.

## Support

- EditorConfig
- Makefile
- Config

## Installation vscode extension

- [VSCodeFileHeader](https://github.com/caizhengxin/vscodefileheader)

## Usage

```python
{
    "fileheader.author": "JanKinCai",
    "fileheader.file_suffix_mapping": {
        ".pyx": "Python",
        ".pxd": "Python",
        ".editorconfig": "EditorConfig",
        "makefile": "Makefile",
        ".cfg": "Config",
        ".ini": "Config",
        ".conf": "Config",
    },
    "fileheader.ignore": [
        "cookiecutter-django",
        "cookiecutter-django-app",
        "cookiecutter-package",
        "cookiecutter-vscode",
        "cookiecutter",
        "*.tmpl"
    ],
    "fileheader.body": true,
    "fileheader.save": true,
    "fileheader.open": true,
    "fileheader.custom_template_path": "/home/jankincai/template/"
}
```

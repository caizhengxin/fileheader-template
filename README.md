# VSCode FileHeader Template

Extended ``VSCodeFileHeader`` does not exist template.

## Support

- Cython
- EditorConfig
- Makefile
- *.conf
- *.ini
- *.cfg
- setup.py

## Installation vscode extension

- [VSCodeFileHeader](https://github.com/caizhengxin/vscodefileheader)

## Usage

```python
{
    "fileheader.author": "Your name",
    "fileheader.file_suffix_mapping": {
        ".pyx": "Python",
        ".pxd": "Python",
        ".editorconfig": "EditorConfig",
        "makefile": "Makefile",
        ".cfg": "Config",
        ".ini": "Config",
        ".conf": "Config",
        "setup.py": "Setup",
    },
    "fileheader.body": true,
    "fileheader.custom_template_path": "xxx/template/"
}
```

## Custom header field

```python
{
    "fileheader.other_config": {
        "email": "Your email"
    }
}
# Need custom header template
```
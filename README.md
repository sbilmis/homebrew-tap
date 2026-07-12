# Homebrew tap for Zotero Project Manager

Install `zpm` directly:

```shell
brew install sbilmis/tap/zpm
```

Or add the tap first:

```shell
brew tap sbilmis/tap
brew install zpm
```

Then verify the installation:

```shell
zpm --version
```

In a `Brewfile`:

```ruby
tap "sbilmis/tap"
brew "zpm"
```

Project source and documentation: [sbilmis/zotero-project-manager](https://github.com/sbilmis/zotero-project-manager).

The formula installs released packages from [PyPI](https://pypi.org/project/zotero-project-manager/).

# Notion Calendar Recipe for AutoPKG
A simple recipe for downloading and packaging Notion Calendar using the AutoPKG CLI for automating packaging and software distribution on macOS.

## Usage
1. Install the latest version of AutoPKG from the [AutoPKG GitHub page](https://github.com/autopkg/autopkg/releases).
2. Install the latest version of the Notion Calendar recipe by running the following command:
```bash
autopkg repo-add
```
3. Run the Notion Calendar recipe by running the following command:
```bash
autopkg run NotionCalendar.pkg
```
4. The Notion Calendar package will be saved to the `~/Library/AutoPkg/Cache/` directory (or the directory specified in the AutoPKG configuration file).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT License
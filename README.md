# homebrew-cpdf

> [Homebrew] formula to install [cpdf], [IrisPen Air 7] and [Photoshop Lightroom CC 5.7] on macOS.

# Install

```bash
$ brew tap oncletom/brew
$ brew install cpdf
$ brew cask install adobe-photoshop-lightroom5
$ brew cask install irispen-air
```

# cpdf Usage

Type `cpdf -help` for more informations about the command options.

The following example illustrates how to split a multi-page PDF into individual files:

```bash
$ cpdf big.pdf -split -o page-%%.pdf
```

If `big.pdf` has 3 pages. It will then create 3 files: `page-01.pdf`, `page-02.pdf` and `page-03.pdf`.

# License

[MIT](LICENSE)

[Homebrew]: https://homebrew.sh
[cpdf]: https://www.coherentpdf.com
[Photoshop Lightroom CC 5.7]: https://helpx.adobe.com/download-install/kb/lightroom-downloads.html
[IrisPen Air 7]: https://www.irislink.com/EN-FR/c1922/IRISPen-7---Product-Support---Details.aspx

![](assets/icon.ico)

# chocolatey-superorca
> SuperOrca from "Pantaray Research Ltd." is a direct replacement to the "Orca" MSI Editor from Microsoft. SuperOrca may be used to examine and modify an MSI database in order to distribute a new MSI package. When QSetup delivers an MSI Editor, SuperOrca delivers an MSI Database Editor and let you discover the depth of MSI Database.

## Installation

[![Chocolatey](https://img.shields.io/chocolatey/v/superorca.svg)](https://chocolatey.org/packages/superorca) https://chocolatey.org/packages/superorca

    > choco install superorca

## Developing

Open [superorca.nuspec](superorca.nuspec) with the editor of your choice, to edit the package defintion.

The actual (un)installation is done in *.ps1*-files:

- [tools/chocolateyinstall.ps1](tools/chocolateyinstall.ps1)
- [tools/chocolateyuninstall.ps1](tools/chocolateyuininstall.ps1)

### Publishing

    > choco pack
    > choco push

## Contributions

Thanks goes to these wonderful people ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://www.fritz-elfert.de"><img src="https://avatars.githubusercontent.com/u/731252?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Fritz Elfert</b></sub></a><br /><a href="#maintenance-felfert" title="Maintenance">🚧</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification. Contributions of any kind welcome!

## License

chocolatey-superorca  is published under [WTFNMFPLv3](https://github.com/dittodhole/WTFNMFPLv3).

# SQL Compare downloads

This repository only hosts the release files of **SQL Compare**, the SQL Server schema, data and server
configuration comparison tool by [SQLTreeo](https://www.sqltreeo.com/sqlcompare). The installed application
reads the releases here to offer automatic updates.

- **Download:** the `SqlCompare-win-Setup.exe` asset of the [latest release](../../releases/latest)
  (Windows 10/11, 64-bit, no .NET installation needed). `SqlCompare-win-Portable.zip` runs without installing.
- **Command line:** `SqlCompare-cli-<version>-win-x64.zip` contains `sqlcompare.exe` for build pipelines.
- **Product page, pricing and license keys:** https://www.sqltreeo.com/sqlcompare
- **Support:** https://www.sqltreeo.com

SQL Compare is commercial software. It is licensed, not sold: see [LICENSE.txt](LICENSE.txt) (end-user
license agreement). The first start on a computer begins a free 30-day trial with every feature enabled;
comparing stays free afterwards, deploying, scripting and report export require a license key.
Third-party open-source components are listed in `THIRD-PARTY-NOTICES.txt` inside every download.

The `.nupkg` and `releases.*.json` files are used by the updater and are not meant to be downloaded manually.

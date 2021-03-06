<h1 align='center'>
  <img src='https://imgur.com/svn8Jrw.jpg' alt='screenshot' />
  <br />
  <center>
    <a href='https://zap.jackmallers.com'>Zap</a>
  </center>
</h1>

Zap is a free Lightning Network wallet focused on user experience and ease of use, with the overall goal of helping the cryptocurrency community scale Bitcoin and other cryptocurrencies.

The UI for Zap is created using
[Electron](https://electron.atom.io/) + [React](https://facebook.github.io/react/) + [Redux](https://github.com/reactjs/redux/tree/master/docs).

We have an active [slack](https://join.slack.com/t/zaphq/shared_invite/enQtMzMxMzIzNDU0NTY3LTgyM2QwYzAyZTA5OTAyMjEwMTQxZmZmZmZkNWUzMTU2MmMyNmMxNjY4Y2VjY2FiYTRkMTkwMTRlMTE4YjM2MWY) channel where you can join the discussion on development, design and product.

## Installing

***Note:*** *If you would like to use a full bitcoin node, please see the [advanced usage](https://github.com/LN-Zap/zap-desktop/blob/master/ADVANCED.md) page.*

Download the [latest release](https://github.com/LN-Zap/zap-desktop/releases) for your appropriate OS and follow the instructions below.

### macOS

Once you have the .zip file downloaded, simply **double click** on the file to unzip.

Navigate to the newly extracted folder, then drag-and-drop the `Zap.app` file to the `Applications` folder.

Unmount the image and navigate to `Applications` folder.

Finally, **double click** on the `Zap.app` file.

### Windows

Once you have the .exe file downloaded, simply **double click** on the file.

### Linux

Once you have the .zip file downloaded, simply **double click** the file to unzip or run the following command:

```bash
unzip file.zip
```

You have the option to either install Zap through the [.deb](#.deb-file) or [.AppImage](#.appimage-file) files.

#### .deb File

Once you have the .deb file extracted, you can install Zap by **double clicking** on the file or through the `dpkg` command:

```bash
sudo dpkg -i file.deb
```

If this is your first time installing zap, you may have some unmet dependencies. This can be resolved with the following command:

```bash
sudo apt-get -f install
```

To run Zap you can either navigate through the GUI or run the following command:

```bash
zap-desktop
```

#### .AppImage File

Once you have the .AppImage file extracted, you can either **double click** the file or by running in the cli:

```bash
./file.AppImage
```

## Advanced Usage
If you would like to install from source or run a full bitcoin node, please see the [advanced usage](https://github.com/LN-Zap/zap-desktop/blob/master/ADVANCED.md) page.

### Contributing
If you would like to help contribute to the project, please see the [contributing guide](https://github.com/LN-Zap/zap-desktop/blob/master/CONTRIBUTING.md).

## Q & A (Quality and Assurance)

***Note:*** *If you are having problems with Zap, please report the issue in [GitHub](https://github.com/LN-Zap/zap-desktop/issues) or on [slack](https://join.slack.com/t/zaphq/shared_invite/enQtMzMxMzIzNDU0NTY3LTgyM2QwYzAyZTA5OTAyMjEwMTQxZmZmZmZkNWUzMTU2MmMyNmMxNjY4Y2VjY2FiYTRkMTkwMTRlMTE4YjM2MWY) with screenshots and/or how to reproduce the bug/error.*

A good product not only has good software tests but also checks the quality of the UX/UI. Putting ourselves in the shoes of a user is a very important design principle of Zap.

### Example User Stories
`User wants to connect to a peer`

`User wants to open a channel`

`User wants to create a payment request`

`User wants to make a payment`

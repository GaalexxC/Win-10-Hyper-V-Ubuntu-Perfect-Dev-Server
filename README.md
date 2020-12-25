![devCUHead](https://www.devcu.net/mediasrc/github-banner.png?V=1.0)

## ** Become a Patron/Supporter of devCU **
	
**Please support our Open Source Projects and keep this software free**

- Patrons and Donators have access to Beta and Release version up to 2 weeks before the public

[![donate](https://www.devcu.net/mediasrc/patronize_devcu.png)](https://www.patreon.com/devcu/) [![donate](https://www.devcu.net/mediasrc/support_devcu.png?v=1)](https://www.devcu.com/clients/donations/)

## Windows 10 Hyper-V / Ubuntu 18 / 20 Perfect Dev Server

Setting up a native Linux development environment on Windows 10 is not only easy but a great way to get the feel for a live production environment for you application. Windows 10 has finally made Hyper-V a viable alternative to other Windows Linux dev environments such as Xampp which in my opinion had its day and is no longer needed. Why bother? When you can have a real Linux environment like Ubuntu running in all its glory. Of course you can choose any Linux flavor you are comfortable with Debian or Fedora core that is compatible with Hyper-V gen 1 or gen 2.

Its about a 15 minute setup give or take and once completed you can start developing immediately. Now if its your first time then it may take much longer but once you get the hang of it creating containers and servers will be fast and easy as pie.

## Covered

- Hyper-V Setup and configuration (1 minute)
- Ubuntu Server 18 / 20 install and configuration (5 minutes)
- Software installs and configurations (6 minutes)
- Yada, Yada, Yada (120 seconds)
- Start Developing! (a lifetime)

## Required

- Secondary internal or external drive (Highly recommend not to install your Hyper-V container on the main (C:) drive) Especially if you are Windows Insider Program participant, you never know what they will screw up in the next release. Plus a secondary drive will act as a backup as well.
- 100GB of space recommended at least 50GB is needed and that’s cutting it close. If you plan on creating several different users and home directories for dev, master, production, etc then I suggest the higher value. Also depending on your application needs, if its just php, python, perl, ruby files etc you’re good with a lower value. But if you have large media files needed for application then use the space accordingly.
- Decent amount of memory (4GB at least, the more the better for performance). I usually set aside 1-2GB with the dynamic memory option ticked in case more is needed. Again depending on your application needs set this value accordingly.
- Hyper-V enabled in Windows 10 obviously.
- Ubuntu 16/17 or Debian 8/9 image (.iso)
- 4 cups of coffee

## Security

- Since this will be a local server install we don’t have to go crazy with the security aspects but I will show best practices that can be carried over to a public production environment so users understand some simple configurations that mean a whole lot when creating a publicly accessed server.

## Installed Programs

- Of course whatever your applications requirements are is what you will install. I will just demonstrate a basic PHP7 based server for PHP development such as Laravel 5 development or any other PHP framework.

1. Nginx Mainline/Stable/Source Build ( Either using: apt / my bash autosetup / custom compiled with latest OpenSSL)
2. PHP7x w/dependencies
3. Percona MySQL Server 5.7 ( Or Oracle MySQL or MariaDB whatever is to your liking)
4. vsFTPd for FTP access
5. User and directory setup to get going

Installing Git, NodeJS/NPM, Ruby Gems, Python, what have you... I will leave up to the user as this is a personal preference depending on ones application needs.

## Highly Reccommended!

I recommend using my [ASAS](https://github.com/GaalexxC/ASAS) bash script to automate everything after the Ubuntu OS install. This will cut the install process in half and will not only install the required software but configure everything for you as well. Ready to go out of the box...

So lets get started, the step by step is on the [wiki pages](https://github.com/GaalexxC/Win-10-Hyper-V-Ubuntu-16.x-Perfect-Dev-Server/wiki/Getting-Started)

## License

Use it and Enjoy License to develop wistfully




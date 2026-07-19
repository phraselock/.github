# PhraseLock - Your Login Wallet

PhraseLock is a full service password and credential wallet with self-hosted backend and private communication channel. It gives you the utmost control over your credentials and how to apply them. Everything between your smartphone and your computer is pure open source.


## Architecture at a glance

PhraseLock works out of the box and you have the choice to use the public channel or to run your own infrastructure by installing PhraseLock-Bridge. If you want to use e.g. KeyPass as a main source for your credentials, **PhraseLock-Bridge** is mandatory.

<br/>
<img src="img/1.svg" width="1700" alt="Modul-Abhängigkeiten">
<br/>

## Repositories

| Repo | What it is |
|---|---|
| [PhraseLock-Bridge](https://github.com/phraselock/PhraseLock-Bridge) | Native shell script installers that turns a Linux server (Debina, Ubuntu) into your **private channel** between the **PhraseLock app** on your smartphone and the **PhraseLock-Port** Installation on your PC or Mac. Minimum requirement is just a Raspberry Pi or a virtual private server in the smallest configuration you can by for.|
| [plp-custom](https://github.com/phraselock/plp-custom) | **plp-custom** is a single .jar serive installed by PhraseLock-Bridge. It servers client certificate distribution for MQTT and license verification.|
| [PhraseLock-Backend](https://github.com/phraselock/plp-backend) | **PhraseLock-Backend** provides natively support of `Keepass`. It gives you the opportunity to manage your credentials and login-parameters centralised managed by `KeyyPassXC` or whatever you prefer. |

## License

PhraseLock-Bridge is licensed under the MIT License — see
[LICENSE](https://github.com/phraselock/PhraseLock-Bridge/blob/main/LICENSE)
for details.

## Keyring support
Since Pinegrow 10, you may want to override Pinegrow's permissions to use the system keyring  on the session bussince it doesn't use the Secrets portal:
```sh
--talk-name=org.freedesktop.secrets
--talk-name=org.kde.kwalletd6```

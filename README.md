# pass

Simplified access to passbolt CLI.

## Configuration

Create a configuration file `~/.ssh/passbolt.json` by running:

```bash
passbolt configure --config ~/.ssh/passbolt.json --serverAddress https://passbolt-instance --userPassword '1234' --userPrivateKeyFile 'keys/privatekey.asc'
```

## Usage

```bash
pass "SEARCH TERM"
```

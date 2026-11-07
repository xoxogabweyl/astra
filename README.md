# astraV2

A fast, free fruit-hopping script with smart server selection, filtering, and webhook notifications.

## Features

- **Server time**: reads the server's uptime/time so you can pick servers more effectively.
- **Smart hop**: hops between servers intelligently instead of joining at random.
- **String filter**: filter fruits by name or keyword so you only look for what you want.
- **Priority fruits**: set a priority list; higher-priority fruits are targeted first.
- **Skip capped/owned fruits**: automatically ignores fruits you already own or can't hold anymore (storage capped).
- **Webhook**: sends a notification to your Discord webhook when something is found.
- **Fast**: quick hopping with minimal delay between servers.
- **Free**: no key system, no payment, no catch.

## Usage

1. Open your executor.
2. Execute it.

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/xoxogabweyl/astra/refs/heads/main/astraV2"))()
```

## Configuration

Edit the config at the top of the script before running:

| Option | Description |
| --- | --- |
| Priority fruits | List of fruits to target first, in order |
| String filter | Keywords/names to include or match |
| Webhook URL | Your Discord webhook for notifications |

> Option names may differ slightly depending on the script version. Check the top of `astraV2` for the exact fields.

## Notes

- Use at your own risk. Using scripts may violate the game's Terms of Service.
- Issues and suggestions are welcome; open an issue or a pull request.

## License

Released under the [MIT License](./LICENSE).

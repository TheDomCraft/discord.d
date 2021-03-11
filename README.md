# discord.d

Discord API library written in D.

This is **very incomplete** and may never be finished. Only a very basic gateway connection is implemented.

### Installation

- Install [DMD](https://dlang.org/) (tested on 2.084.0)
- Clone the repository
- Run `dub` in the main directory

### Example

```d
import client;

enum string token = "Bot TOKEN";

void main()
{
	Client client = new Client();
	client.run(token);
}
```

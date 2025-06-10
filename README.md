[view readme](https://github.com/nathan-websculpt/weth-substream/tree/main/main_proj)

## Getting Started
```bash
git clone git@github.com:nathan-websculpt/weth-substream.git <dir_name>
cd <dir_name>/main_proj
substreams build

substreams auth
<FOLLOW DIRECTIONS>
 . ./.substreams.env <AUTH_TOKEN_NO_QUOTES>
substreams gui -e mainnet.eth.streamingfast.io:443 substreams.yaml map_events -s 22675435 -t +1


```

# HLS Radio

Using HLS for an internet radio like this is very non-standard, but it does very nicely split the problem into:
- Have HLS-compatible content (`to_hls.pluto`)
- Schedule content into a continuous HLS playlist (`libhlsradio.pluto`)

## Practical Use Case: Bootleg FH6 Radios

The `horizon.pluto` uses this to play bootleg FH6 radios. You can listen to this live on [radio.goddess.sh](https://radio.goddess.sh).

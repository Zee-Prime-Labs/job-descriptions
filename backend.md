
# Senior Backend Developer - Go / Rust

## Zee Prime Labs

We are a fast-growing team of blockchain developers and traders backed by private investment company. Our goal is to build and run crypto hedge fund. Currently, we are focused on development of automated trading systems for crypto markets.

If you are senior Go / Rust backend developer with passion for concurrent data processing, low latency systems, AI, automated systems - you would be a great fit! ;) Knowledge of blockchains is advantage, not requirement.
If you are an active trader, you would probably love this job. For others, trading knowledge is advantage, not requirement.

Your working hours have to be at least partially compatible with working hours in UTC+1 TZ.

## What We Do

Our goal is to build a fully automated algorithmic trading system. Primarily, we are interested in market neutral strategies which are based on market mechanics - not on prediction of bigger market movements. Examples of such strategies are arbitrages and market making (we develop other strategies, too). For this, we are building robust data infrastructure. We collect data from various CEXes (centralized exchanges) and DEXes (decentralized exchanges).

Components of our infrastructure are designed as low latency, highly concurrent data processing services. Data collectors are self-adjusting - they periodically check all tradable pairs and switch on/off workers accordingly. For example, one such collector now has 1378 workers which process data concurrently. All our services are written in Go. To have an idea about data flow - currently we are processing about 4 GB of market data per hour - and that's just the beginning ;) Basically, we are building a mirror of accurate state of all relevant trading venues in one place. That is the data layer. Above it, there is a strategy layer and next is trading execution layer, which are reacting to data streams in near real-time manner.

For our team we are looking for senior Go backend developer (Rust is also nice). If you have 3+ years of Go backend development with experience of building highly concurrent data intensive services, you would find a great opportunity in our team...

Feel free to reach out if you have any questions / want to know more: jobs@zplabs.io

[Back to all positions](README.md)

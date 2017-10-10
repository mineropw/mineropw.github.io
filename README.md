[Minero](http://minero.pw) is a JavaScript Crypto Miner. 

It uses [CoinHive](https://coinhive.com)’s miner to mine Monero (XMR), and connects to [minerXMR pool](https://minexmr.com) using a [Stratum Proxy](https://github.com/cazala/coin-hive-stratum). The API combines mineXMR and [ShapeShift.io](https://shapeshift.io) APIs to retrieve stats and convert currencies. ShapeShift is also used to convert Monero to the desired currency when a payment is done. The CLI is a wrapper of [coin-hive CLI](https://github.com/cazala/coin-hive). The UI was made in React using [CRA](https://github.com/facebookincubator/create-react-app) and allows you to [see your stats](https://minero.pw/#/currencies/BTC/addresses/176sh81PQupUsFyX6hNL2PTYydSuL7Wu73), it is hosted in [GitHub pages](https://github.com/mineropw/mineropw.github.io). The proxy and the API are both hosted in [now.sh](https://zeit.co/now).

All the pieces are hosted for free and the sources are public.

Minero is a PoC and is the result of a self-hatred fuelled narcotics induced 48hs-straight coding extravaganza held during a rainy weekend in October, 2017. Don’t expect this code to be rock solid.

If you happen to find any bugs, or if you think I might be breaking some ToS, reach me out [@juancazala](https://twitter.com/juancazala).

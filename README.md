# 👷 `worker` Random User

A free random user generate api. Limited with `100.000` request per day.

[`index.js`](https://github.com/cloudflare/worker-template/blob/master/index.js) is the content of the Workers script.

#### Usgae

<pre><b>GET</b> https://random-user.npthanh.workers.dev/ </pre>

```
user: {
  id: 100,
  name: {
    _first: "Idaline",
    _last: "Gass"
  },
  email: "igass2r@freewebs.com",
  url_avatar: "https://robohash.org/repellendusblanditiisquia.bmp?size=50x50&set=set1",
  gender: "Female",
  location: {
    city: "Coronda",
    country: "Argentina"
  },
  contact: {
    phone: "+54 224 190 9266",
    bitcoin_address: "1CXYNZ8Sd6RrAwMn2AA7i6wKnXgeQS7vEk"
  }
}
```

 ## Development
 Created using [Cloudflare Workers](https://workers.dev)
 <br />
 Install [Wrangler](https://github.com/cloudflare/wrangler) to build

 - `❯ wrangler generate random.user https://github.com/greatMonster11/effective-octo-garbanzo`
- `❯ wrangler preview`

## License

MIT

# 👷 `worker-template` Hello World

A template for kick starting a Cloudflare worker project.

[`index.js`](https://github.com/cloudflare/worker-template/blob/master/index.js) is the content of the Workers script.

#### Wrangler

To generate using [wrangler](https://github.com/cloudflare/wrangler)

```
wrangler generate projectname https://github.com/cloudflare/worker-template
```

Further documentation for Wrangler can be found [here](https://developers.cloudflare.com/workers/tooling/wrangler).


### Wrangler useful command

**로컬에서 사이트 띄워서 테스트하는 커맨드**

```wrangler dev```

**배포하기 위한 커맨드**
 
- `wrangler login`
- `wrangler publish`

**wrangler의 auth token 확인하는 커맨드**

`vi .wrangler/config/default.toml`
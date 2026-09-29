# ios-vip

备份来源：https://reven.jsforbaby.workers.dev/reven/

## 文件清单

| 文件 | 类型 | 大小 | 说明 |
|---|---|---|---|
| [`iTunes.lpx`](./iTunes.lpx) | Loon 插件 | ~1.1 KB | iTunes / Apple 内购自动查询并注入最贵套餐凭证 |
| [`reven.lpx`](./reven.lpx) | Loon 插件 | ~1.4 KB | RevenueCat / Superwall / Adapty 通杀解锁 |
| [`loon-itunes.js`](./loon-itunes.js) | Loon 脚本 | ~370 KB | iTunes.lpx 的 script-path 后端 |
| [`loon-redirect.js`](./loon-redirect.js) | Loon 脚本 | ~4.4 KB | reven.lpx 的 script-path 后端 |

## 原始下载链接

- `https://reven.jsforbaby.workers.dev/reven/iTunes.lpx`
- `https://reven.jsforbaby.workers.dev/reven/reven.lpx`
- `https://reven.jsforbaby.workers.dev/reven/loon-itunes.js`
- `https://reven.jsforbaby.workers.dev/reven/loon-redirect.js`

## 备份时间

2026-09-29 23:02:04 UTC

## 注意事项

- `.lpx` 是 **Loon Plugin eXtension** 文件（纯文本），直接拷贝到 Loon 插件目录即可导入
- `.lpx` 中 `script-path=` 默认指向 `reven.jsforbaby.workers.dev`，**导入前无需改 URL**（脚本会从原作者 CDN 拉取）
- 本仓库保留的 `.js` 仅作存档用途，并非自托管——如需自托管请同步修改 `.lpx` 中的 `script-path` 指向 `raw.githubusercontent.com/jackbba/ios-vip/main/...`

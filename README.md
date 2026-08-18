# Loon-Rules

> 个人自用的 Loon 分流规则集。

## 仓库说明

本仓库用于统一收纳个人使用的 Loon 分流规则。每个服务对应一个独立文件，互不合并、互不影响，可按需单独订阅。

- 现有 Emby 规则保持独立，更新其他服务时不会修改 `Emby.list`。
- Binance 使用独立的 `Binance.list`，可单独添加、更新或停用。
- 后续新增服务时继续创建新的 `.list` 文件，不把不同服务混入同一规则集。

## 规则集

| 服务 | 规则文件 | 订阅地址 |
| --- | --- | --- |
| Emby | [`Emby.list`](./Emby.list) | [Raw](https://raw.githubusercontent.com/LuxJon/Loon-Rules/main/Emby.list) |
| Binance | [`Binance.list`](./Binance.list) | [Raw](https://raw.githubusercontent.com/LuxJon/Loon-Rules/main/Binance.list) |

## 使用方式

在 Loon 中添加远程规则时，复制上表对应的 `Raw` 地址。每个文件都是独立订阅，更新其中一个规则集不会改变其他规则集的地址或内容。

## 维护约定

- 每个服务对应一个独立的 `.list` 文件。
- 新规则集使用清晰的服务名称，例如 `Binance.list`。
- 已发布文件不随意改名或移动，以保持现有订阅地址长期有效。
- 规则采用 Loon 支持的标准格式，例如 `DOMAIN`、`DOMAIN-SUFFIX` 和 `IP-CIDR`。

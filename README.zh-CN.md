# Muthur Command DNS 插件（CoreDNS）

英文文档: [`README.md`](./README.md)

由 Supervisor 管理的 **DNS** 插件容器，面向 **Muthur Command OS**。

基于 **`ghcr.io/muthur-command/base`** 构建；OCI 标签使用 **`io.mcos.*`**。

Corefile 中仍保留与上游 Supervisor 栈兼容的解析名（如 `local.hass.io` / `hassio`）；与 **Muthur Command** 栈服务别名、迁移域名的对齐见 **P3《DNS 别名表》**（若适用）。

## 来源

- **上游：** [home-assistant/plugin-dns](https://github.com/home-assistant/plugin-dns) — Home Assistant Supervisor 的 DNS（CoreDNS）插件容器，本仓库由其移植而来。
- **本仓库：** **Muthur Command** 维护此 fork，供 **Muthur Command OS** 使用；行为可能随时间与上游产生差异。
- **许可：** 自上游继承的代码仍为 **Apache-2.0**；详见 **LICENSE**（按 fork 要求保留上游版权 / NOTICE）。

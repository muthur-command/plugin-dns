# MCOS DNS 插件（CoreDNS）

由 Supervisor 管理的 **DNS** 插件容器，面向 **MCOS**。

基于 **`ghcr.io/muthur-command/base`** 构建；OCI 标签使用 **`io.mcio.*`**。

Corefile 中仍保留与上游 Supervisor 栈兼容的解析名（如 `local.hass.io` / `hassio`）；与 MC 栈服务别名、迁移域名的对齐见 **P3《DNS 别名表》**（若适用）。

## 许可证

见 **LICENSE**（Apache-2.0；按 fork 要求保留上游版权 / NOTICE）。

# API 参考

[English](api.md) | [文档索引](README.zh-CN.md)

本清单由本仓库 package 的 `go doc -short` 生成，用于快速查看公共面。精确语义以源码和测试为准。

## 包

### `gnalloy.org/handler-traffic`

包名：`traffic`

```text
var ErrInvalidConfig = errors.New("gnalloy/handler/traffic: invalid config") ...
func MessageSize(msg any) int
type ClockMillis func() int64
type Config struct{ ... }
type Controller struct{ ... }
    func NewController(cfg Config) (*Controller, error)
type Handler struct{ ... }
    func NewChannelHandler(cfg Config) (*Handler, error)
    func NewHandler(controller *Controller) *Handler
type Limiter interface{ ... }
type Snapshot struct{ ... }
```

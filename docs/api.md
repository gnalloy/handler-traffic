# API Reference

[简体中文](api.zh-CN.md) | [Docs Index](README.md)

This inventory is generated from `go doc -short` for the packages in this repository. It is a quick public-surface map; source files and tests remain the authority for exact semantics.

## Packages

### `gnalloy.org/handler-traffic`

Package name: `traffic`

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

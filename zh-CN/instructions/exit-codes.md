# Exit codes

### 171

一个比当前版本更加新的修订版或者先行修订版已经存在。

比如，当我们想发布 `1.1.0` 但是 `1.1.3` 已经存在了，那么这个是不允许的

### 172

当发布一个稳定版本时，该稳定版本已经存在。

比如，当我们想发布 `1.1.4`，但是 `1.1.4` 已经存在，则这个是不允许的。

### 173

当发布一个先行版本时，对应的稳定版本已经存在

比如，当我们先想发布 `1.1.4-alpha` 时，`1.1.4` 已经存在，则这个是不允许的。


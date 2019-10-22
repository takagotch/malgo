### malgo
---
https://github.com/gen2brain/malgo

```go
// sizes_test.go

func TestRawSizes(t *testing.T) {
  assert.Equal(t, unsafe.Sizeof(ContextConfig{}), rawContextConfigSize, "ContextConfig size mismatch")
  assert.Equal(t, unsafe.Sizeof(DeviceConfig{}), rawDeviceConfigSize, "DeviceConfig size mismatch")
  assert.Equal(t, unsafe.Sizeof(DeviceInfo{}), rawDeviceInfoSize, "DeviceInfo size mismatch")
}




```

```
```

```
```



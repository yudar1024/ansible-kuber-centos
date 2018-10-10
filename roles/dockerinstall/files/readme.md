# 相关说明

## daemon.json
```
    "storage-driver": "overlay2",
    "storage-opts": [
      "overlay2.override_kernel_check=true"
    ]
```

上文的配置只有在linux 内核为低版本（3.10)时需要

# docker 版本 17.03.2 之前配置为 --graph=/opt/docker

# docker 版本 17.04.x 之后配置为 --data-root=/opt/docker 
---
title : flowchart
layout :  blog
tag : cm
---
# Test
```mermaid
flowchart TD
  start([Start]) --> a{A}
  a --> |Yes| b[PUT 'Hello']
  a ---> |No| a
  b --> e([End])
```

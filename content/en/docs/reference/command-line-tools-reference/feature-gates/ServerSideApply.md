---
title: ServerSideApply
content_type: feature_gate
_build:
  list: never
  render: false

stages:
  - stage: alpha 
    defaultValue: false
    fromVersion: "1.14"
    toVersion: "1.15"
  - stage: beta
    defaultValue: true
    fromVersion: "1.16"  
    toVersion: "1.21" 
  - stage: stable
    defaultValue: true
    fromVersion: "1.22"  
    toVersion: "1.31"

removed: true
---
Enables the [Sever Side Apply (SSA)](/docs/reference/using-api/server-side-apply/)
feature on the API Server.

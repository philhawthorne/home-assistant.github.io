---
layout: page
title: "Hyperion"
description: "Instructions how to integrate Hyperion into Home Assistant."
date: 2015-10-25 22:43
sidebar: true
comments: false
sharing: true
footer: true
ha_category: Light
ha_release: 0.7.6
---

This platform allows you to integrate your [Hyperion](https://github.com/tvdzwan/hyperion/wiki) into Home Assistant.

```yaml
# Example configuration.yaml entry
light:
  - platform: hyperion
```

Configuration variables:

- **host** (*Optional*): To enable the automatic addition of lights on startup.
- **port** (*Optional*): A list of devices with their ip address and a custom name to use in the frontend.

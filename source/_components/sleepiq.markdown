---
layout: page
title: "SleepIQ"
description: "Instructions for how to integrate SleepIQ sensors within Home Assistant."
date: 2016-08-28 8:56
sidebar: true
comments: false
sharing: true
footer: true
logo: sleepiq
ha_category: Hub
featured: true
---

The SleepIQ platfor lets you view sensor data from [SleepIQ by SleepNumber](http://www.sleepnumber.com/sn/en/sleepiq-sleep-tracker).
In particular, it lets you see the occupancy and current SleepNumber (ie current firmness) of each side of a SleepNumber bed.

You will need an account on [SleepIQ](https://sleepiq.sleepnumber.com/) to use this component.

To set it up, add the following information to your `configuration.yaml` file:

```yaml
sleepiq:
  username: you@example.com
  password: omgsecure
```

Configuration variables:

- **username** (*Required*): Your SleepIQ username (usually an email address)
- **password** (*Required*): Your SleepIQ password

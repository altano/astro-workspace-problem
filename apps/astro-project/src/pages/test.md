---
setup: |
  import { Image } from '@astrojs/image/components'
  import testImage from './test.png'
title: Hello world!
publishDate: 12 Sep 2021
name: Nate Moore
value: 128
description: Just a Hello World Post!
---

<Image src={testImage} width={640} />

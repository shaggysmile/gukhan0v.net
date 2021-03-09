---
title: Hello World
date: "2021-03-09T12:00:00.000Z"
description: "This is my first post on my new fake blog! How exciting!
I'm sure I'll write a lot more interesting things in the future."
---

This is my first post on my new fake blog! How exciting!
I'm sure I'll write a lot more interesting things in the future.
Oh, and here's a great quote from this Wikipedia on
[salted duck eggs](https://en.wikipedia.org/wiki/Salted_duck_egg).

You can also write code blocks here!

```ts
import {
  AxiosInstance,
} from '@/plugins/axios-instance';
import {
  AxiosInstance as AxiosInstanceType,
} from '@/plugins/axios-instance/types';
import {
  BaseApiService as BaseApiServiceType,
} from '@/services/types';

export class BaseApiService implements BaseApiServiceType {
  public http: AxiosInstanceType;

  constructor(baseUrl: string, useAuthToken: boolean) {
    this.http = new AxiosInstance({
      useAuthToken,
      axios: {
        baseURL: baseUrl,
      },
    });
  }
}
```

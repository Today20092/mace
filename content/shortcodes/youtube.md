---
authors: ["will-faught"]
categories: ["paige", "shortcodes"]
description: "Demonstration of the Paige YouTube shortcode."
tags: ["videos", "youtube"]
title: "YouTube Shortcode"
---

Paige provides a `paige/youtube` shortcode for playing YouTube videos.

<!--more-->

## Basic

Code:

```go-text-template
{{</* paige/youtube "dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube "dQw4w9WgXcQ" >}}

## Autoplay parameter

Code:

```go-text-template
{{</* paige/youtube autoplay=true video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube autoplay=true video="dQw4w9WgXcQ" >}}

## Controls parameter

Code:

```go-text-template
{{</* paige/youtube controls=true video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube controls=true video="dQw4w9WgXcQ" >}}

## Description parameter

Code:

```go-text-template
{{</* paige/youtube description="My title" video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube description="My title" video="dQw4w9WgXcQ" >}}

## End parameter

Code:

```go-text-template
{{</* paige/youtube end=20 video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube end=20 video="dQw4w9WgXcQ" >}}

## Fullscreen parameter

Code:

```go-text-template
{{</* paige/youtube fullscreen=false video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube fullscreen=false video="dQw4w9WgXcQ" >}}

## Height parameter

Code:

```go-text-template
{{</* paige/youtube height="10rem" video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube height="10rem" video="dQw4w9WgXcQ" >}}

## List parameter

Code:

```go-text-template
{{</* paige/youtube list="PLOstxpSiJGlClyRnCiubdXJcUvwgHcrVH" video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube list="PLOstxpSiJGlClyRnCiubdXJcUvwgHcrVH" video="dQw4w9WgXcQ" >}}

## Loop parameter

Code:

```go-text-template
{{</* paige/youtube loop=true video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube loop=true video="dQw4w9WgXcQ" >}}

## Maxheight parameter

Code:

```go-text-template
{{</* paige/youtube maxheight="10rem" video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube maxheight="10rem" video="dQw4w9WgXcQ" >}}

## Maxwidth parameter

Code:

```go-text-template
{{</* paige/youtube maxwidth="50%" video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube maxwidth="50%" video="dQw4w9WgXcQ" >}}

## Mute parameter

Code:

```go-text-template
{{</* paige/youtube mute=true video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube mute=true video="dQw4w9WgXcQ" >}}

## Start parameter

Code:

```go-text-template
{{</* paige/youtube start=10 video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube start=10 video="dQw4w9WgXcQ" >}}

## Video parameter

Code:

```go-text-template
{{</* paige/youtube video="dQw4w9WgXcQ" */>}}
```

Result:

{{< paige/youtube video="dQw4w9WgXcQ" >}}

## Width parameter

Code:

```go-text-template
{{</* paige/youtube video="dQw4w9WgXcQ" width="50%" */>}}
```

Result:

{{< paige/youtube video="dQw4w9WgXcQ" width="50%" >}}

## Figure

Code:

```go-text-template
{{</* paige/figure caption="YouTube" */>}}
{{</* paige/youtube video="dQw4w9WgXcQ" */>}}
{{</* /paige/figure */>}}
```

Result:

{{< paige/figure caption="YouTube" >}}
{{< paige/youtube video="dQw4w9WgXcQ" >}}
{{< /paige/figure >}}

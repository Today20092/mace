---
authors: ["will-faught"]
categories: ["paige", "shortcodes"]
description: "Demonstration of the Paige gallery shortcode."
tags: ["figures", "gallery", "images"]
title: "Gallery Shortcode"
---

Paige provides a `paige/gallery` shortcode for displaying a list of images.

<!--more-->

## Align parameter

Code:

```go-text-template
{{</* paige/gallery align="start" */>}}
{{</* paige/image height="20rem" src="1-2.jpg" */>}}
{{</* paige/image height="10rem" src="2-2.jpg" */>}}
{{</* /paige/gallery /*/>}}
```

Result:

{{< paige/gallery align="start" >}}
{{< paige/image height="20rem" src="1-2.jpg" >}}
{{< paige/image height="10rem" src="2-2.jpg" >}}
{{< /paige/gallery >}}

---

Code:

```go-text-template
{{</* paige/gallery align="center" */>}}
{{</* paige/image height="20rem" src="1-2.jpg" */>}}
{{</* paige/image height="10rem" src="2-2.jpg" */>}}
{{</* /paige/gallery /*/>}}
```

Result:

{{< paige/gallery align="center" >}}
{{< paige/image height="20rem" src="1-2.jpg" >}}
{{< paige/image height="10rem" src="2-2.jpg" >}}
{{< /paige/gallery >}}

---

Code:

```go-text-template
{{</* paige/gallery align="end" */>}}
{{</* paige/image height="20rem" src="1-2.jpg" */>}}
{{</* paige/image height="10rem" src="2-2.jpg" */>}}
{{</* /paige/gallery /*/>}}
```

Result:

{{< paige/gallery align="end" >}}
{{< paige/image height="20rem" src="1-2.jpg" >}}
{{< paige/image height="10rem" src="2-2.jpg" >}}
{{< /paige/gallery >}}

## Fetchpriority parameter

Code:

```go-text-template
{{</* paige/gallery fetchpriority="high" images="*-2.jpg" /*/>}}
```

Result:

{{< paige/gallery fetchpriority="high" images="*-2.jpg" />}}

---

Code:

```go-text-template
{{</* paige/gallery fetchpriority="low" images="*-2.jpg" /*/>}}
```

Result:

{{< paige/gallery fetchpriority="low" images="*-2.jpg" />}}

## Height parameter

Code:

```go-text-template
{{</* paige/gallery height="10rem" images="*-2.jpg" /*/>}}
```

Result:

{{< paige/gallery height="10rem" images="*-2.jpg" />}}

---

Code:

```go-text-template
{{</* paige/gallery height="20rem" images="*-2.jpg" /*/>}}
```

Result:

{{< paige/gallery height="20rem" images="*-2.jpg" />}}

## Images parameter

Code:

```go-text-template
{{</* paige/gallery images="1-2.jpg" /*/>}}
```

Result:

{{< paige/gallery images="1-2.jpg" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" />}}

## Justify parameter

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" justify="start" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" justify="start" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" justify="center" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" justify="center" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" justify="end" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" justify="end" />}}

## Linked parameter

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" linked="unprocessed" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" linked="unprocessed" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" linked="default" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" linked="default" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" linked="r180" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" linked="r180" />}}

## Loading parameter

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" loading="eager" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" loading="eager" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" loading="lazy" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" loading="lazy" />}}

## Maxheight parameter

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" maxheight="10rem" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" maxheight="10rem" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" maxheight="20rem" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" maxheight="20rem" />}}

## Maxwidth parameter

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" maxwidth="10rem" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" maxwidth="10rem" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" maxwidth="20rem" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" maxwidth="20rem" />}}

## Process parameter

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" process="default" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" process="default" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" process="300x300 center crop lanczos picture r180 webp" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" process="300x300 center crop lanczos picture r180 webp" />}}

## Type

Code:

```go-text-template
{{</* paige/gallery images="*.jpg" maxheight="10rem" type="filled-rows" /*/>}}
```

Result:

{{< paige/gallery images="*.jpg" maxheight="10rem" type="filled-rows" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*.jpg" type="grid" /*/>}}
```

Result:

{{< paige/gallery images="*.jpg" type="grid" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*.jpg" maxheight="10rem" type="rows" /*/>}}
```

Result:

{{< paige/gallery images="*.jpg" maxheight="10rem" type="rows" />}}

## Width parameter

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" width="10rem" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" width="10rem" />}}

---

Code:

```go-text-template
{{</* paige/gallery images="*-2.jpg" width="20rem" /*/>}}
```

Result:

{{< paige/gallery images="*-2.jpg" width="20rem" />}}

## Figure

Code:

```go-text-template
{{</* paige/figure caption="Gallery" /*/>}}
{{</* paige/gallery */>}}
{{</* paige/figure caption="Image 1" /*/>}}
{{</* paige/image src="1-2.jpg" /*/>}}
{{</* /paige/figure */>}}
{{</* paige/figure caption="Image 2" /*/>}}
{{</* paige/image src="2-2.jpg" /*/>}}
{{</* /paige/figure */>}}
{{</* paige/figure caption="Image 3" /*/>}}
{{</* paige/image src="3.jpg" /*/>}}
{{</* /paige/figure */>}}
{{</* paige/figure caption="Image 4" /*/>}}
{{</* paige/image src="4.jpg" /*/>}}
{{</* /paige/figure */>}}
{{</* /paige/gallery */>}}
{{</* /paige/figure */>}}
```

Result:

{{< paige/figure caption="Gallery" >}}
{{< paige/gallery >}}
{{< paige/figure caption="Image 1" >}}
{{< paige/image src="1-2.jpg" >}}
{{< /paige/figure >}}
{{< paige/figure caption="Image 2" >}}
{{< paige/image src="2-2.jpg" >}}
{{< /paige/figure >}}
{{< paige/figure caption="Image 3" >}}
{{< paige/image src="3.jpg" >}}
{{< /paige/figure >}}
{{< paige/figure caption="Image 4" >}}
{{< paige/image src="4.jpg" >}}
{{< /paige/figure >}}
{{< /paige/gallery >}}
{{< /paige/figure >}}

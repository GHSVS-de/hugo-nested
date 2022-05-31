---
title: Spülwiese
description: Durcheinander-Zeugs
---

{{< ghsvs/callout "success" >}}
{{< ghsvs/code >}}
{{ $img := resources.GetRemote "https://ghsvs.de/images/avatar-ghsvs.de.jpg" }}
{{ $img := $img.Content | resources.FromString "assets/images/avatar-ghsvs.de.jpg" }}
<img src="{{ $img.RelPermalink }}">
Pfad ist {{ $img.RelPermalink }}.
{{< /ghsvs/code >}}
{{< /ghsvs/callout >}}

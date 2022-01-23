---
title: SudoTV 剧集
layout: base
localization: zh-CN
---

# {{ page.title }}

## 剧集

{% include series/series-link.html
    href="video-cover-generator"
    series=site.data.series.video-cover-generator
%}

{% include series/series-link.html
    href="what-to-play"
    series=site.data.series.what-to-play
%}

{% include series/series-link.html
    href="clone-bilibili"
    series=site.data.series.clone-bilibili
%}

## 欲了解更多

{% include navigation/absolute-link.html
    external=true
    with-origin=true
    href="https://sudo.tv/reprint/series"
    title="如何转载剧集"
    description="查看您转载 SudoTV 剧集的权利和限制"
%}
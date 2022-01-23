---
title: SudoTV Series
layout: base
localization: en-US
---

# {{ page.title }}

## Series

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

## Learn More

{% include navigation/absolute-link.html
    external=true
    with-origin=true
    href="https://sudo.tv/reprint/series"
    title="How to Reprint Series"
    description="View your right and limitations to reprint SudoTV Series"
%}
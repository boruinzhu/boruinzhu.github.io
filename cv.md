---
layout: page
title: CV
date: 2022-08-23
permalink: /cv/
---

Or download as [PDF]({{ site.url }}/assets/cv.pdf).
# <embed src="https://{{ site.url }}/assets/cv.pdf" type="application/pdf"/>

<div>
 <div id="adobe-dc-view" style="height: 55vh; width: 50vw"></div>
 <script src="https://documentcloud.adobe.com/view-sdk/viewer.js"></script>
 <script type="text/javascript">
    document.addEventListener("adobe_dc_view_sdk.ready", function()
    {
        var adobeDCView = new AdobeDC.View({clientId: "52234b276d33457396444dc2a35e6508", divId: "adobe-dc-view"});
        adobeDCView.previewFile(
       {
          content:   {location: {url: "/assets/cv.pdf"}},
          metaData: {fileName: "cv.pdf"}
       });
    });
 </script>
</div>

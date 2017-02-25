---
title: "Microsoft Media Platform Content Map | Microsoft Docs"
author: rick-anderson
description: "The Microsoft Media Platform is a complete technology platform for deploying a highly available, highly scalable, Smooth Streaming media delivery environment..."
ms.author: aspnetcontent
manager: wpickett
ms.date: 02/09/2011
ms.topic: article
ms.assetid: 
ms.technology: dotnet-webforms
ms.prod: .net-framework
msc.legacyurl: /learn/media/smooth-streaming/microsoft-media-platform-content-map
msc.type: authoredcontent
---
Microsoft Media Platform Content Map
====================
by Dave Nelson

The Microsoft Media Platform is a complete technology platform for deploying a highly available, highly scalable, Smooth Streaming media delivery environment. The platform contains the following technologies:

- **Content preparation**. [Microsoft Expression Encoder](http://expression.microsoft.com/cc136533.aspx), [IIS Transform Manager](../../../downloads/microsoft/transform-manager.md)
- **Content delivery**. [IIS Media Services](/media)
- **Content playback**. [Microsoft Silverlight](https://www.microsoft.com/silverlight/)

This portal page is designed to help you to deploy the Microsoft Media Platform by providing links to the best available best practices and guidance, organized in the following categories:

- [Creating Smooth Streams](microsoft-media-platform-content-map.md#create)
- [Delivering Smooth Streams](microsoft-media-platform-content-map.md#deliver)
- [Managing Smooth Streams](microsoft-media-platform-content-map.md#manage)
- [Playing Smooth Streams](microsoft-media-platform-content-map.md#play)
- [Progressively Downloading Media](microsoft-media-platform-content-map.md#download)
- [Troubleshooting](microsoft-media-platform-content-map.md#fix)

<a id="create"></a>

## Creating Smooth Streams

| **Scenario** | **Resources** |
| --- | --- |
| **Create on-demand Smooth Streams** | [Creating a Silverlight Project](https://msdn.microsoft.com/en-us/library/ff723878(Expression.40).aspx) Use Expression Encoder to create a media file that is optimized for Smooth Streaming playback and embed the media file in a Silverlight player template. [Creating a Transcoding Project](https://msdn.microsoft.com/en-us/library/ff723883(Expression.40).aspx) Use Expression Encoder to edit digital media sources and encode them as Smooth Streams that are compatible with VC-1 or H.264 codecs, without using Silverlight player templates. [Transforming Media Files to On-Demand Smooth Streams](../transform-manager/transforming-media-files-to-on-demand-smooth-streams.md) Use Transform Manager to convert media files to Smooth Streams for Silverlight clients. [Transforming Media Files to Apple HTTP Live Streams](../transform-manager/transforming-media-files-to-apple-http-live-streams.md) Use Transform Manager to convert media files to Smooth Streams for Apple mobile digital devices. [Transforming On-Demand Smooth Streams to Apple HTTP Live Streams](../transform-manager/transforming-on-demand-smooth-streams-to-apple-http-live-streams.md) Use Transform Manager to convert on-demand Smooth Streams for playback on Apple devices. [Smooth Streaming Encoding for Windows Phone](https://blogs.iis.net/vsood/archive/2010/12/04/iis-smooth-streaming-encoding-for-windows-phone-7.aspx) Create Smooth Streams for Silverlight clients on Windows Phone. [Smooth Streaming Format SDK - Sample Application](https://blogs.iis.net/thalesc/archive/2010/03/15/iis-smooth-streaming-format-sdk-sample-application.aspx) Use the sample muxing application in the [Smooth Streaming Format SDK](../../../downloads/microsoft/smooth-streaming-format-sdk.md) to generate on-demand Smooth Streams and manifests from media files encoded in WMA, WMV/VC-1, H.264, or AAC-LC formats. [Smooth Streaming Format SDK](../../../downloads/microsoft/smooth-streaming-format-sdk.md) Create software programs that package encoded audio and video bitstreams for on-demand Smooth Streaming scenarios. |
| **Create live Smooth Streams** | [Live Smooth Streaming in Expression Encoder 4](https://blogs.msdn.com/b/expressionencoder/archive/2010/09/22/10042763.aspx) Use Expression Encoder to create a live Smooth Streaming broadcast from live and file-based sources. [Apple HTTP Live Streaming with IIS Media Services](../live-smooth-streaming/apple-http-live-streaming-with-iis-media-services.md) Create a live Smooth Streaming broadcast for Apple mobile digital devices. [Smooth Streaming Encoding for Windows Phone](https://blogs.iis.net/vsood/archive/2010/12/04/iis-smooth-streaming-encoding-for-windows-phone-7.aspx) Create a live Smooth Streaming broadcast for Silverlight clients on Windows Phone. [How to do Live Streaming with the Smooth Streaming Format SDK](https://blogs.iis.net/thalesc/archive/2011/02/08/how-to-do-live-streaming-with-the-smooth-streaming-format-sdk.aspx) Use sample code in this blog post with the [Smooth Streaming Format SDK](../../../downloads/microsoft/smooth-streaming-format-sdk.md) to add live Smooth Streaming functionality to encoders. [Smooth Streaming Format SDK](../../../downloads/microsoft/smooth-streaming-format-sdk.md) Create software programs that package encoded audio and video bitstreams for live Smooth Streaming scenarios. |
| **Protect Smooth Streams** | [Enabling PlayReady DRM with Smooth Streaming](smooth-streaming-primer.md#drm) Encrypt on-demand and live Smooth Streams for Silverlight clients by using Microsoft PlayReady Digital Rights Management (DRM). [Encrypting On-Demand Smooth Streams](../transform-manager/encrypting-on-demand-smooth-streams.md) Use Transform Manager to encrypt previously encoded Smooth Streaming presentations with PlayReady DRM. |

<a id="deliver"></a>

## Delivering Smooth Streams

| **Scenario** | **Resources** |
| --- | --- |
| **Deliver on-demand Smooth Streams** | [Getting Started with Smooth Streaming](../on-demand-smooth-streaming/getting-started-with-iis-smooth-streaming.md) Configure a Web server to deliver on-demand Smooth Streams to Silverlight clients on desktop computers and mobile devices (including Windows Phone). [Delivering Transform Manager Output to Clients](../transform-manager/delivering-transform-manager-output-to-clients.md) Configure a Web server to deliver on-demand Smooth Streams to Silverlight clients and to Apple mobile digital devices. [Streaming Live or On-Demand Video from IIS7 to iOS Devices and Silverlight Clients](http://www.hanselman.com/blog/StreamingLiveOrOnDemandVideoFromIIS7ToIOSDevicesIPhoneiPadAndSilverlightClients.aspx) Convert media files to Smooth Streams for Silverlight clients and Apple devices. |
| **Deliver live Smooth Streams** | [Getting Started with Live Smooth Streaming](../live-smooth-streaming/getting-started-with-iis-live-smooth-streaming.md) Configure a Web server to deliver live Smooth Streams to Silverlight clients on desktop computers and mobile devices (including Windows Phone). [Apple HTTP Live Streaming with IIS Media Services](../live-smooth-streaming/apple-http-live-streaming-with-iis-media-services.md) Configure a Web server to deliver live Smooth Streams to Apple mobile digital devices. [Streaming Live or On-Demand Video from IIS7 to iOS Devices and Silverlight Clients](http://www.hanselman.com/blog/StreamingLiveOrOnDemandVideoFromIIS7ToIOSDevicesIPhoneiPadAndSilverlightClients.aspx) Deliver live Smooth Streams to Silverlight clients and Apple devices. |
| **Set up live Smooth Streaming encoders for high availability** | [How to Build Scalable and Robust Live Smooth Streaming Server Solutions](https://blogs.iis.net/samzhang/archive/2009/12/16/how-to-build-scalable-and-robust-live-smooth-streaming-server-solutions.aspx) Configure encoders for failover and redundancy in order to guarantee delivery of streams. [How to do network auto-recovery from Expression Encoder 4](https://blogs.iis.net/samzhang/archive/2011/01/19/how-to-do-network-auto-recovery-from-expression-encoder-4.aspx) Configure your Live Smooth Streaming encoder for network resiliancy. |
| **Set up a live Smooth Streaming server network for high availability** | [How to Build Scalable and Robust Live Smooth Streaming Server Solutions](https://blogs.iis.net/samzhang/archive/2009/12/16/how-to-build-scalable-and-robust-live-smooth-streaming-server-solutions.aspx) Create a high-performance live Smooth Streaming server network. [Edge Caching for Media Delivery](../iis-media-services/edge-caching-for-media-delivery.md) Use edge-caching features in [IIS Application Request Routing](../../../downloads/microsoft/application-request-routing.md) to increase scalability, save money, and improve user experiences when delivering audio and video. |

<a id="manage"></a>

## Managing Smooth Streams

| **Scenario** | **Resources** |
| --- | --- |
| **Adjust track availability in on-demand Smooth Streams** | [Managing On-Demand Presentations](../on-demand-smooth-streaming/managing-on-demand-presentations.md) Trim steams from on-demand Smooth Streaming presentations to save bandwidth, or to make different streams in the presentation available to different audience segments. |
| **Monitor live Smooth Streaming publishing point runtime status** | [New Live Smooth Streaming UI Explained](https://blogs.iis.net/samzhang/archive/2010/11/01/new-live-smooth-streaming-ui-explained.aspx) View stream, track, and connection information exposed by Runtime Status and Control (RSCA) APIs and leverage this information for troubleshooting purposes. |
| **Configure advanced attributes for Live Smooth Streaming publishing points** | [Live Smooth Streaming Publishing Point Advanced Settings](https://blogs.iis.net/samzhang/archive/2010/11/01/live-smooth-streaming-publishing-point-advanced-settings.aspx) Configure properties in Live Smooth Streaming publishing point definition (.isml) files for advanced streaming scenarios (for example, configuring publishing point auto-restart). |
| **Manage Live Smooth Streaming publishing points programatically** | [Smooth Streaming Management REST Services](https://msdn.microsoft.com/en-us/library/hh239768(v=VS.90).aspx) Use Representational State Transfer (REST) APIs to create or delete publishing points; enumerate the publishing points on a website; query the setting, state, or statistics of publishing points; or update the state of publishing points in IIS Media Services 4.1. |
| **Authenticate live Smooth Streams on distributed server networks** | [Syndicating Live Smooth Streams between Servers](../live-smooth-streaming/syndicating-live-smooth-streams-between-servers.md) |
| **Authenticate encoder connections to Live Smooth Streaming publishing points** | [How to Authenticate ONLY the Encoder Streams for Live Smooth Streaming](https://blogs.iis.net/samzhang/archive/2011/03/29/how-to-only-authenticate-encoder-streams-but-not-the-clients-for-live-smooth-streaming.aspx) |
| **Track user engagement with Smooth Streaming assets** | [Advanced Logging](../../../downloads/microsoft/advanced-logging.md) Monitor and measure user engagement with Smooth Streaming assets in order to deploy media more profitably. |

<a id="play"></a>

## Playing Smooth Streams

| **Scenario** | **Resources** |
| --- | --- |
| **Deploy a Smooth Streaming Silverlight player without coding** | [Getting Started with Smooth Streaming](../on-demand-smooth-streaming/getting-started-with-iis-smooth-streaming.md) Get up-and-running quickly by deploying a sample Smooth Streaming player for on-demand Smooth Streaming playback. [Getting Started with Live Smooth Streaming](../live-smooth-streaming/getting-started-with-iis-live-smooth-streaming.md) Get up-and-running quickly by deploying a sample Smooth Streaming player for live Smooth Streaming playback. |
| **Build a Smooth Streaming Silverlight player** | [Building your first Smooth Streaming Player using SSME](https://blogs.iis.net/vsood/archive/2009/10/14/building-your-first-smooth-streaming-player.aspx) Enable Smooth Streaming video playback, with basic controls such as Play, Pause, and Stop, in a Silverlight-enabled Web browser. [Smooth Streaming Client](https://msdn.microsoft.com/en-us/library/hh943091(v=vs.90)) Use the Smooth Streaming Client SDKs to implement advanced Smooth Streaming playback scenarios in Silverlight applications. |
| **Enable Smooth Streaming playback on Apple mobile digital devices** | [Creating an HTML 5 page for use in Safari](../live-smooth-streaming/apple-http-live-streaming-with-iis-media-services.md#html5) Create an HTML 5 page that can be used by iPhone and iPad devices to play Smooth Streams. |

<a id="download"></a>

## Progressively Downloading Media

| **Scenario** | **Resources** |
| --- | --- |
| **Save bandwidth by sending only what is watched** | [Bit Rate Throttling](../../../downloads/microsoft/bit-rate-throttling.md) Reduce network costs by metering the download speed of media and data files. |
| **Create a server-side playlist to control client playback of media files** | [Creating a Simple Playlist](../web-playlists/web-playlists-for-iis-7-creating-a-simple-playlist.md) Create server-controlled sequences of digital media content and prevent caching of the content on client computers. |
| **Monetize playlist content with dynamic advertisements** | [Adding HTTPD Media Entries](../web-playlists/web-playlists-for-iis-7-creating-a-simple-playlist.md#httpd) Insert dynamic in-stream or pre-roll video ads based on the session history and configurable server-side rules. |
| **Convert Windows Media Player playlist files to server-side playlists in IIS** | [Using Windows Media Player Playlist Files in Web Playlists](../web-playlists/using-windows-media-player-playlist-files-in-web-playlists.md) Create server-side versions of Windows Media Player client-side playlist (.wpl) files. |

<a id="fix"></a>

## Troubleshooting

| **Scenario** | **Resources** |
| --- | --- |
| **View known issues** | Review Microsoft Media Platform feature Readme files to see if a solution for the issue that you're experiencing has been published. Readme files are available for the following features: - [IIS Media Services](../iis-media-services/iis-media-services-readme.md) (includes sections for Live Smooth Streaming, Smooth Streaming, Bit Rate Throttling, and Web Playlists). - [IIS Transform Manager](../transform-manager/iis-transform-manager-readme.md) - [Smooth Streaming Client](smooth-streaming-client-readme.md) - [Smooth Streaming Format SDK](iis-smooth-streaming-format-sdk-readme.md) - [IIS Advanced Logging](../../extensions/advanced-logging-module/advanced-logging-readme.md) Search the following forums to see if your issue has been addressed previously: - [Expression Encoder Forum](http://social.expression.microsoft.com/Forums/en-US/encoder/) - [IIS Media Forum](https://forums.iis.net/1145.aspx) - [Silverlight.net Forums](http://forums.silverlight.net/forums/) |
| **Troubleshoot IIS Media server errors** | [Troubleshooting a Web Server Error](../../troubleshoot.md) Learn about HTTP errors and Web server troubleshooting techniques in IIS 7. [Failed Requests Tracing module for IIS 7](../../troubleshoot/using-failed-request-tracing/troubleshooting-failed-requests-using-tracing-in-iis.md) Record failed requests in log files for later analysis. [Fiddler Web Debugger](http://www.fiddler2.com/fiddler2/) Analyze the HTTP traffic between clients and IIS Media servers. | ![Note](microsoft-media-platform-content-map/_static/image1.gif) > [!NOTE]
 > - You might be asked to provide failed request tracing or Fiddler logs when you ask Microsoft for help. Providing these logs can help Microsoft to investigate your problem more efficiently, and might reduce support costs if you seek help from Microsoft Support. | | --- | |
| **Troubleshoot live Smooth Streaming issues** | Troubleshooting guidance for live Smooth Streaming is provided in the following collection of blog posts: - [Part 1 (Basics)](https://blogs.iis.net/samzhang/archive/2011/03/07/how-to-troubleshoot-live-smooth-streaming-issues-part-1.aspx). Reviews the basic design of Live Smooth Streaming and the protocols that are used. - [Part 2 (Publishing Point UI and States)](https://blogs.iis.net/samzhang/archive/2011/03/07/how-to-troubleshoot-live-smooth-streaming-issues-part-2.aspx). Reviews the diagnostic information that is available in the Live Smooth Streaming user interface. - [Part 3 (Event Logs)](https://blogs.iis.net/samzhang/archive/2011/03/08/how-to-troubleshoot-live-smooth-streaming-issues-part-3-event-logs.aspx). Reviews the Live Smooth Streaming event logs in Event Viewer. - [Part 4 (Performance Counters)](https://blogs.iis.net/samzhang/archive/2011/03/08/how-to-troubleshoot-live-smooth-streaming-issues-part-4-performance-counters.aspx). Reviews the performance counters in Performance Monitor for tracking live Smooth Streaming status. - [Part 5 (Client Manifest)](https://blogs.iis.net/samzhang/archive/2011/03/10/how-to-troubleshoot-live-smooth-streaming-issues-part-5-client-manifest.aspx). Describes the information in client manifest (.ismc) files that you can use for troubleshooting. - [Part 6 (IIS Logs and Others)](https://blogs.iis.net/samzhang/archive/2011/03/11/how-to-troubleshoot-live-smooth-streaming-issues-part-6-iis-logs-and-others.aspx). Describes how to gather Smooth Streaming client request information and response codes in logs and how to parse and analyze the data. - [Part 7 (Putting It Together)](https://blogs.iis.net/samzhang/archive/2011/03/14/how-to-troubleshoot-live-smooth-streaming-issues-part-7-end.aspx). Provides a "real-world" troubleshooting example. |
| **Troubleshoot Silverlight MediaElement errors** | [Troubleshooting the Silverlight MediaElement 4001 Error](https://blogs.msdn.com/b/randomnumber/archive/2009/02/09/troubleshooting-the-silverlight-mediaelement-4001-error.aspx) |
| **Get help** | Post questions and ask for troubleshooting guidance from other users and Microsoft team members on the following forums: - [Expression Encoder Forum](http://social.expression.microsoft.com/Forums/en-US/encoder/) - [IIS Media Forum](https://forums.iis.net/1145.aspx) - [Silverlight.net Forums](http://forums.silverlight.net/forums/) Get assistance from [Microsoft Support](https://support.microsoft.com/common/international.aspx?RDPATH=dm;en-us;select&amp;target=assistance) for the following products (charges may apply): - [Expression Encoder](https://support.microsoft.com/ph/12897) - [IIS Media Services](/media) 3 and 4 (includes Live Smooth Streaming, Smooth Streaming, Bit Rate Throttling, and Web Playlists) - [Smooth Streaming Client](../../../downloads/microsoft/smooth-streaming.md) 1.0, 1.1, 1.5, and 2.0 - [Advanced Logging](../../../downloads/microsoft/advanced-logging.md) 1.0 - [Microsoft Silverlight](https://support.microsoft.com/ph/12929) |
  
  
[Discuss in IIS Forums](https://forums.iis.net/1145.aspx)
---
title: Using Your CGM Data
updated: 2023-04-04 17:36:50Z
created: 2023-04-04 17:36:43Z
latitude: 47.46683840
longitude: -122.34053050
altitude: 0.0000
---

# Using Your CGM Data

Websites and apps that help you track glucose numbers.

## Use the Personal Science App

The best way to analyze your CGM data is with the CGM app from Personal Science (makers of this web site). You can upload your data and study it for free using the open source software [here](https://github.com/personalscience/taster).  Uses Docker.  Requires a little setup, but it will let you upload a CSV file and generate plots like this:

![](images/glucose_Levels_After_Eating_Rice.jpg)


## Abbott Labs Official

The most important software for Freestyle Libre downloading is the officially-supported one here:

<https://provider.myfreestyle.com/freestyle-libre-resources.html>

Create an account on Libreview and then you can download your data as a CSV file here:

<https://www.libreview.com/meter>

![Libreview main page](images/freestyle-download.jpg "image_tooltip")

Then click here: <https://www.libreview.com/glucosereports>

![Click to download](images/freestyle-download-click.jpg "image_tooltip")

If you have the Abbott custom reader device, you can also download a Mac or Windows version of Freestyle Libre personal CGM

![Freestyle Libre Software](images/freestyle-software.png "image_tooltip")

## International versions

Freestyle Libre devices sold in other countries will generally work everywhere if you use the app downloaded specifically for that country.

This [table by [Chuck Kub](https://www.facebook.com/photo.php?fbid=1835069433269419&set=gm.751003141928341&type=3&theater&ifg=1)] is a little old, but gives a sense of which models are available in which countries.

**China:** buy a reader plus 3 14-day sensor packs [through Taobao](https://item.jd.com/32498232197.html) for about 1800 RMB (USD\$270)

## Third Party

Many organizations now offer ways to upload and use your Freestyle (or other CGM) data.

+--------------------------------------------------------------------------------------------------------------------------------------------------------------------+---+-------------------------------------------------------------------------------------------------------+
| **Nightscout**                                                                                                                                                     |   | ![alt_text](images/nightscout-logo.png "image_tooltip"){alt="alt_text"} <http://www.nightscout.info/> |
|                                                                                                                                                                    |   |                                                                                                       |
| \"an open source, DIY project that allows real time access to a CGM data via personal website, smartwatch viewers, or apps and widgets available for smartphones\" |   |                                                                                                       |
|                                                                                                                                                                    |   |                                                                                                       |
| See their app <https://spike-app.com/>                                                                                                                             |   |                                                                                                       |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------+---+-------------------------------------------------------------------------------------------------------+
| **Diasend**                                                                                                                                                        |   | ![alt_text](images/diasend-logo.png "image_tooltip"){alt="alt_text"} <https://diasend.com/us>         |
|                                                                                                                                                                    |   |                                                                                                       |
| (formerly called[ Glooko](https://www-int.glooko.com/)) tries to let you upload data from anywhere                                                                 |   |                                                                                                       |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------+---+-------------------------------------------------------------------------------------------------------+
| **Tidepool** <https://app.tidepool.org/patients>                                                                                                                   |   | ![alt_text](images/tidepool-logo.png "image_tooltip"){alt="alt_text"}                                 |
|                                                                                                                                                                    |   |                                                                                                       |
| Open-source non-profit place to upload glucose data                                                                                                                |   | <https://tidepool.org>                                                                                |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------+---+-------------------------------------------------------------------------------------------------------+
| **Diabetes:M**                                                                                                                                                     |   | ![alt_text](images/miaomiao-logo.png "image_tooltip"){alt="alt_text"}                                 |
|                                                                                                                                                                    |   |                                                                                                       |
|                                                                                                                                                                    |   | https://diabetes-m.com/                                                                               |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------+---+-------------------------------------------------------------------------------------------------------+
| **Glimp** : popular Android app                                                                                                                                    |   | ![alt_text](images/glimp-logo.png "image_tooltip"){alt="alt_text"}                                    |
|                                                                                                                                                                    |   |                                                                                                       |
|                                                                                                                                                                    |   | <https://play.google.com/store/apps/details?id=it.ct.glicemia>                                        |
+--------------------------------------------------------------------------------------------------------------------------------------------------------------------+---+-------------------------------------------------------------------------------------------------------+

# Open Source Software

-   [cgmr](https://github.com/personalscience/cgmr) is an open-source R package that lets you read and process CGM data from Abbott Freestyle Libre. Includes functions to calculate iAUC and do side-by-side analyses comparing different food types over time.

-   **Nightscout xDrip+**: <https://github.com/JoernL/xDrip-plus>

    -   supports wireless connections to G4, G5, G6, Medtrum A6, Libre via NFC and Bluetooth, 630G, 640G, 670G pumps and Eversense CGM via companion apps. Bluetooth Glucose Meters such as the Contour Next One, AccuChek Guide, Verio Flex & Diamond Mini as well as devices like the Pendiq 2.0 Insulin Pen
    -   44 contributors, very active since Nov 2014 (latest checkin Dec 2018)
    -   

-   **OpenLibreReader** iOS: <https://github.com/blueToolz/openLibreReader-iOS->

    -   a project to connect the various Libre Transmitters to the iPhone.
    -   [Blog post](https://unendlichkeit.net/wordpress/openlibrereader-and-status/?lang=en) (Jan 2018) summarizing goals and status.
    -   latest commit Apr 2018; Started in Nov 2017 by 2 Germans

-   <https://github.com/UPetersen/LibreMonitor> iOS NFC reader, includes hardware instructions

    -   last active: Nov 2018. Started in 2016 by 3 guys from Germany

-   **nahog / freestyle-libre-parser-viewer:** [https://github.com/nahog/freestyle-libre-parser-v tiewer](https://github.com/nahog/freestyle-libre-parser-viewer)

    -   A parser library and viewer for CSV generated by the Abbott Freestyle Libre flash glucose meter.
    -   From 2016, last commit June 2018; One guy from Ireland

-   [cgmnalysis](https://cran.r-project.org/web/packages/cgmanalysis/index.html): R Package on CRAN and [Github](https://github.com/childhealthbiostatscore/R-Packages) cleans up data from multiple CGM devices

    -   Last update October 2019

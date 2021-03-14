---
title: 'gnssmapper (python)'
tags:
- research
date: 2018-02-25 19:07:50 +0000
banner_image: "/uploads/2018/02/25/car.jpg"
sub_heading: 'Tools for generating 3D maps from GNSS data'
slug: ''
---
GnssMapper provides tools for generating 3D maps by using Global Navigation Satellite System (GNSS) data. It is connected to a research project at the University of Glasgow, which investigates methods for using crowdsourced GNSS data for mapping. It is written in Python and built upon GeoPandas objects.

It provides the following capabilities:

- read 'raw' GNSS data from Google's gnsslogger app, available for Android phones
- process data into a set of observations
- estimate building heights based on the observations
- simulate observations for algorithm testing

It does not include any functionality for processing GNSS data in order to estimate position, and assumes position data is available from the log file, or calculated elsewhere.

For more details see:

GnssMapper github repository
GnssMapper documentation

---
title: 1.25 Police Body Cameras (summary)
created: '2020-11-12T12:21:18.286376'
modified: '2020-11-12T12:21:18.286386'
state: active
type: dataset
tags:
  - Body Worn Camera
  - Bwc
  - Safe And Secure Communities
groups:
  - Local Government
csv_url: 'https://data.tempe.gov/datasets/822fb9f6a4d9429da3ab7fe42f6a4f7b_0.csv'
json_url: ''
layout: post

---
<p>This dataset contains annual data, including number of events (count of arrivals to calls for service, up to one per officer per call), and number of events with at least one matching video. This data is the basis for the compliance percentage for Performance Measure 1.25.</p><p><br /></p><p>This page provides data for the Police Body Cameras performance measure. </p><p><br /></p><p>The performance measure dashboard is available at <a href='https://safe-and-secure-communities-tempegov.hub.arcgis.com/pages/police-body-cameras' rel='nofollow ugc' target='_blank'>1.25 Police Body Cameras</a>.</p><p><br /></p><p><b>Additional Information</b></p><p><br /></p><p>Source: Police calls for service, officer activity, axon metadata.</p><p>Contact: Noah Fritz</p><p>Contact E-Mail: Noah_Fritz@tempe.gov</p><p>Data Source Type: Excel</p><p>Preparation Method: 1. Calls for service. Police calls for service are limited to the time period under consideration. Cancelled calls, test calls, and callback call types are removed. 2. Officer unit history. Raw unit history data may contain two officers per unit. Data is split and recombined so that each officer maintains an inpidual record. Unit history is limited to calls for service at which an officer has a documented arrival, and at which an officer spent at least one minute at the scene. When an officer has multiple arrivals to a single call, the first arrival and last clear time are selected to calculate the duration of the call, then superfluous arrivals are removed. Records in which Unit history is matched to the calls for service dataset by primary key (call number). 3. Axon meta data. Axon meta data is matched to unit history first on officer, then on month and week, in a full outer join. Data is next matched on the call number reported in the metadata, and then to call number based on video recorded date/time and officer unit history date/time. Records are selected where there is either a match on call number or on date/time.</p><p>Publish Frequency: Annually</p><p>Publish Method: Manual</p><p><a href='https://gis.tempe.gov/design/data-dictionary/1.25%20Police%20Body%20Camers%20(summary)/' rel='nofollow ugc' target='_blank'>Data Dictionary</a><br /></p>

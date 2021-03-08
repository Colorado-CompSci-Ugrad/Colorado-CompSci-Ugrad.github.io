---
title: Help@CS Applied
keywords: procedure, applied, staff
sidebar: helpatcs_sidebar
permalink: helpatcs_procedures_applied.html
folder: helpatcs
---

## Introduction
A second instance of Moodle is used to host online only classes. All of the documentation for the CS Moodle will work here. However, the Context information below would be used instead of that referenced in the documentation.

Help@CS supports the `applied.cs.colorado.edu` website as well as the `moodle.cs.colorado.edu` LMS.

## Context
```
gcloud auth login
gcloud config set project csel-stage-161517
gcloud container clusters get-credentials applied-prod --zone us-west1-a
kubectl config use-context gke_csel-stage-161517_us-west1-a_applied-prod
kubectl config set-context gke_csel-stage-161517_us-west1-a_applied-prod --namespace applied-prod
```

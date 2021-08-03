---
title: Audit log of material Studio events
sidebar_title: Audit log (enterprise only)
description: Download a log of all material events that have occured in your account
---

As of July 2021, [Studio Enterprise](http://apollographql.com/pricing) offers an audit log of all material events that have ocurred in your organization. You can find the interface to request an export of auditable events under the "Audit" tab of your organization's homepage.

![image](https://user-images.githubusercontent.com/5922187/127679934-e862077a-0ce0-4e3a-89db-ad9e621111ff.png)

## How it works

Actions taken in your organization will appear in exported logs about 10-15 minutes after they have occcurred. When creating an audit export, you will be able to specify a **time range** and filter actions taken by a specific **user**, or actions taken on a specific **graph**. If you need to export a log with a complex filter, please contact us at [support@apollographql.com](mailto:support@apollographql.com).

Audit exports can sometimes take a few minutes to process. Studio will email you with a link to your export when it's ready, and you will also be able to find that link in the audit exports table. Audit export files will be available to download for 30 days.

Only **Organization Admins** can request audit exports.

## Audited events

All material changes to your Studio account are logged in the audit log. This includes:
- Graph Changes
  - graphs created and deleted
  - graph titles, descriptions, or avatars changed
  - API keys created, renamed, or deleted
  - datadog configuration changed
  - hidden/visible property changed
  - graph role overrides changed
  - variants created

- User Changes
  - user added to or removed from org
  - user role changed in org
  - beta features toggled on/off
  - user API keys created, renamed, or deleted
  - password changed or password reset attempted
  - avatar or email changed
  - submitted a support ticket
  - email verified
  - user deleted

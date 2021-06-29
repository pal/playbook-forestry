---
layout: default
has_children: true
title: Management Roles
nav_order: 
published: false

---
## Requirements for technical solution

In order to make it really easy and streamlined to use and edit the Playbook, it’s imperative to have a strong and simple technical solution running things.

![](/assets/images/appar.png)

Here are some requirements:

* Should work great in mobile and desktop
* Login using Google account required
* Support custom components and redirections
  * SSO to support-systems or operations dashboard
  * Register time and expenses
  * Plan my vacation
  * View/Join video conferences
  * Download existing software such as anti-virus
* Each page should have a ‘Edit this page’
  * Changes are either smallish ‘push as new version’ or larger/more uncertain ‘push as new suggestion’
    * A new suggestion is (like) a branch with a pull-request and submitting that allows comments and a preview-URL to be generated
    * This should not live too long however, but rather the author should ping some people or (slack) channels about the suggested edit and a decision to abandon or merge should be done fairly soon
  * Changes are version controlled, and traceable back to the logged in person - not requiring a github account
  * User should be able to edit using WYSIWYG or Markdown
  * Easy to inline static and live media (video, images, figma-files, google docs etc)
* All content, design and logic is under version control and has automated deployment with support for branches as well as local development
* All pages should display changelog on demand, as well as _last edited at X by Y_ information
---
layout: post
title: "MFC 윈도우 최상위에 나타나도록 설정"
excerpt: "MFC 윈도우를 최상위에 나타나도록 설정하는 방법입니다."
date: 2018-06-19 18:19:00
categories: [MFC]
tags: [MFC, Dialog]
comments: true
---

MFC 윈도우를 최상위에 나타나도록 설정하는 방법입니다.

`::SetWindowPos(GetSafeHwnd(),  HWND_TOPMOST , 0, 0, 0, 0, SWP_NOMOVE | SWP_NOSIZE); `
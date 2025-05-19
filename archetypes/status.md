---
date: '{{ time.Now.Format "2006-01-02 13:18" }}'
title: "{{ humanize .File.ContentBaseName | title }}"
type: status
---

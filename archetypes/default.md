+++
date = '{{ time.Now.Format "02-01-2006" }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++

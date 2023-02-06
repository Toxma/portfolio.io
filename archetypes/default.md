+++
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date | time.Format ":date_short"}}
menu = "main"
+++

+++
date = '2026-02-01'
draft = true
title = 'Test Post'
weight = '5'
+++
# Test Markdown post

Include a single line of code:

```sh
bazgab@localhost ~/blog/bazgab.github.io (main)$ ls

```

And now multiple lines of code:

```sh
bazgab@localhost ~/blog/bazgab.github.io (main)$ zypper lr
Repository priorities in effect:                                                                                                                                                   (See 'zypper lr -P' for details)
      90 (raised priority)  :  1 repository
      99 (default priority) : 12 repositories

#  | Alias                       | Name                                         | Enabled | GPG Check | Refresh
---+-----------------------------+----------------------------------------------+---------+-----------+--------
 1 | GNOME_Apps                  | GNOME Applications (16.0)                    | Yes     | (r ) Yes  | No
 2 | Leap                        | Leap 16.0                                    | No      | ----      | ----
 3 | Leap-16.0-standard          | Leap-16.0-standard                           | Yes     | (r ) Yes  | No
 4 | SUSE_CA                     | SUSE Internal CA Certificate (16.0)          | Yes     | (r ) Yes  | No
 5 | devel_languages_go          | devel_languages_go                           | Yes     | (r ) Yes  | No
 6 | games                       | games                                        | Yes     | (r ) Yes  | No
 7 | google-chrome               | google-chrome                                | Yes     | (r ) Yes  | Yes
 8 | kubernetes                  | Kubernetes                                   | Yes     | (r ) Yes  | No
 9 | openSUSE:repo-non-oss       | repo-non-oss (16.0)                          | No      | ----      | ----
10 | openSUSE:repo-non-oss-debug | repo-non-oss-debug (16.0)                    | No      | ----      | ----
11 | openSUSE:repo-openh264      | repo-openh264 (16.0)                         | Yes     | (r ) Yes  | Yes
12 | openSUSE:repo-oss           | repo-oss (16.0)                              | Yes     | (r ) Yes  | Yes
13 | openSUSE:repo-oss-debug     | repo-oss-debug (16.0)                        | No      | ----      | ----
14 | openSUSE:repo-oss-source    | repo-oss-source (16.0)                       | No      | ----      | ----
15 | packman-essentials          | packman-essentials                           | Yes     | (r ) Yes  | Yes
16 | scc-devel                   | scc-devel                                    | Yes     | (r ) Yes  | No
17 | systemsmanagement_SCC_RMT   | systemsmanagement:SCC:RMT (openSUSE_Factory) | Yes     | (r ) Yes  | Yes
18 | tools                       | tools                                        | Yes     | (r ) Yes  | No

```
Testing tables:

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

This is a now a simple way to test footnotes[^first]

[^first]: footnotes are an easy way of referencing future articles and contains other interesting information


One of the toughest parts would be to give out warnings to certain things such as:

> the only way to give out warnings is to use these big block quotes, let's see how it looks.

And some more text here because why not

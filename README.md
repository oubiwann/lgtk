# ℓGTK

*An LFE GTK 2.0 API that wraps the Erlang gtknode library*

[![][lgtk-logo]][lgtk-logo-large]

[lgtk-logo]: resources/images/lGTK-logo.png
[lgtk-logo-large]: resources/images/lGTK-logo-large.png


## Introduction

As od as it may seem, LFE and GTK are actually a very good combination. LFE is a language that runs on a VM that was built to support highly-concurrent communications betewen native (Erlang/BEAM) and non-native (Ports) code. Due to its inherent message passing, LFE supports asynchronous calls. In addition to generic software servers, LFE also supports event servers -- both are useful integrating with GUI main loops and managing signals. Furthermore, due to LFE's support of distribution, it is possible to create GTK GUIs that manage or interact with light-weight language processes that run on multiple cores or even on remote systems.


## Dependencies

* Erlang
* ``rebar``
* GNU ``make``
* ``libglade2`` and its development files

If you would like to use the dark theme included in ``priv``, you will also need:

* ``gtk2-engines``
* ``gtk2-engines-pixbuf``


## Building

```bash
$ make
```

This will:

1. Download all the dependencies
1. Compile source (as well as that of its dependencies), and
1. Bring up a GTK window.


## Usage

TBD

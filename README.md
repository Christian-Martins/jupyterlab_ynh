# JupyterLab for YunoHost

[![Integration level](https://dash.yunohost.org/integration/jupyterlab.svg)](https://ci-apps.yunohost.org/jenkins/job/jupyterlab%20%28Community%29/lastBuild/consoleFull)
[![Install jupyterlab with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=jupyterlab)

> *This package allow you to install jupyterlab quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
JupyterLab is the next-generation user interface for Project Jupyter offering all the familiar building blocks of the classic Jupyter Notebook (notebook, terminal, text editor, file browser, rich outputs, etc.) in a flexible and powerful user interface. JupyterLab will eventually replace the classic Jupyter Notebook.

**Shipped version:** v0.35.4

## Screenshots

![](https://raw.githubusercontent.com/jupyterlab/jupyterlab/3e3a2c9e295703ff6d441589423e284cc6d5c245/docs/source/images/jupyterlab.png)

## Demo

* [Try it on Binder](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/master?urlpath=lab/tree/demo)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH.

## Documentation

 * Official documentation: [Link to the official documentation of this app](https://jupyterlab.readthedocs.io/en/stable/)

## YunoHost specific features

#### Multi-users support

LDAP auth supported? **Yes**
Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64b - [![](https://ci-apps.yunohost.org/ci/logs/jupyterlab%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/jupyterlab/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/jupyterlab%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/jupyterlab/)
* Jessie x86-64b - [![](https://ci-stretch.nohost.me/ci/logs/jupyterlab%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/jupyterlab/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/jupyterlab_ynh/issues
 * App website: https://jupyter.org/index.html
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/jupyterlab_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/jupyterlab_ynh/tree/testing --debug
or
sudo yunohost app upgrade jupyterlab -u https://github.com/YunoHost-Apps/jupyterlab_ynh/tree/testing --debug
```

# Liferay portal installation

This is a small guide to setup `liferay-portal` on your development machine.

For the moment this document is "macOS" (and MacOS X) specific but I'll add notes
for linux and windows later on.

## Basic Requirements

- [git](https://git-scm.com/)

This guide assumes that:

- `git` is installed and configured on your machine

- You have a GitHub account and are part of the `liferay` organization.

- We'll install more things later on so make sure you have the correct permissions
  on your machine and a few GB's of storage avaialbe on your HDD.


Additionally on Mac, you'll also install

- [homebrew](https://brew.sh/)

## Getting the source code

1. Login to your GitHub account.

2. Fork the [liferay-portal](https://github.com/liferay/liferay-portal) repository to your account.

3. Clone the liferay-portal repository

```shell
# Replace YOUR_GITHUB_USERNAME with your GitHub user name.

git clone git@github.com:YOUR_GITHUB_USERNAME/liferay-portal.git
```

4. Wait ...

## Installing the required software

You'll also need to have the following tools installed on your machine

- [Apache Ant](https://ant.apache.org/)
- [Java JDK8](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [MySQL 5.7](https://dev.mysql.com/downloads/mysql/5.7.html)
- [nodejs](https://nodejs.org/en/download/)

Let's go throught them one by one:


- **Java JDK8**

Open your browser and visit [this](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) URL.

You'll need to accept the license agreement (by clicking in a radio button
somewhere next to the downloads list)  before you can
download anything.

Once that's done, you can download the Java SE Development package for your
operating system.

There are usually 2 versions (the two latest released) on the page, choose the
"newest" one and execute the installer once download is complete.

Follow the installation process and make sure everything completes succesfully.

Open a terminal and make sure you can execute the `java` command

```shell
java --version
```

**NOTE**: If your operating system has a package manager or a tool that allows
you to

- **node.js**

Open your browser and visit [this](https://nodejs.org/en/download/) URL.

Download the installer for your operating system.





For `ant` and `mysql` we'll be using `homebrew`:

```shell
brew install ant mysql@5.7
```

## Setup



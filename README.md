# 📚 Prose-App

[![Build Status](https://img.shields.io/github/actions/workflow/status/duongnguyen1010/my-prose-duongnt/build.yml?branch=main&style=for-the-badge)](https://github.com/duongnguyen1010/my-prose-duongnt/actions)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

![Java Version](https://img.shields.io/badge/Java-17%2B-orange?style=flat&logo=openjdk)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apache-maven)
[![GitHub last commit](https://img.shields.io/github/last-commit/duongnguyen1010/my-prose-duongnt)](https://github.com/duongnguyen1010/my-prose-duongnt/commits/main)
[![GitHub Issues](https://img.shields.io/github/issues/duongnguyen1010/my-prose-duongnt)](https://github.com/duongnguyen1010/my-prose-duongnt/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/duongnguyen1010/my-prose-duongnt)](https://github.com/duongnguyen1010/my-prose-duongnt/pulls)
[![GitHub Contributors](https://img.shields.io/github/contributors/duongnguyen1010/my-prose-duongnt)](https://github.com/duongnguyen1010/my-prose-duongnt/graphs/contributors)

A simple Java project that uses the [`prose-builder`](https://github.com/duongnguyen1010/my-prose-duongnt/) library from GitHub Packages. This project demonstrates how to integrate external libraries via Maven and how to implement custom versions of the `Sentence` and `Prose` interfaces. The app generates text composed of multiple sentences.

## ✨ Features

- ✅ Integration of external Maven libraries via GitHub Packages
- ✅ Custom implementations of `Sentence` and `Prose` interfaces
- ✅ Automatic generation of structured multi-sentence text
- ✅ Lightweight setup for easy understanding and extension
- ✅ Maven-based dependency management

## 🛠️ Technologies Used

- **Java 17+**
- **Maven**
- **GitHub Packages** (as package source)
- **prose-builder** (external library)

## 📦 Installation & Setup

```bash
# Clone the repository
git clone git@github.com:duongnguyen1010/my-prose-duongnt.git
cd my-prose-duongnt

# Compile and build with Maven
mvn clean compile

# Package into JAR
mvn package
# Zero Permission Handler Windows

A compatibility library that provides a no-operation implementation for Windows in the [permission_handler](https://pub.dev/packages/permission_handler) package.

## Overview

This library addresses compatibility issues with the default Windows implementation of permission_handler, particularly on Windows 7 systems where the standard implementation fails to function properly. By providing a minimal, non-functional implementation, it allows applications using permission_handler to run on Windows without encountering runtime errors.

## Key Features

- Disables Windows-specific permission handling functionality
- Ensures compatibility with Windows 7 and other legacy Windows versions
- Maintains application stability by preventing permission-related crashes
- Drop-in replacement for the default permission_handler_windows package

## Installation

Add the following dependency override to your `pubspec.yaml` file:

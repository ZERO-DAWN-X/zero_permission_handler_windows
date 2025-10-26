# zero_permission_handler_windows

This library disables Windows support in [permission_handler](https://pub.dev/packages/permission_handler).

The existing windows implementation does not work in Windows 7.

## Usage

```yaml
dependency_overrides:
  permission_handler_windows:
    git:
      url: https://github.com/nxive/zero_permission_handler_windows.git
```

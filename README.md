# GetX - Forked by rai-ms

> Stable fork of [GetX](https://pub.dev/packages/get) (v4.7.3) maintained for use in **Akku OTT** and related Flutter projects.

## Why this fork?

The original GetX package on pub.dev can occasionally face availability issues or breaking changes. This fork ensures:

- **Stable dependency** - No surprises from upstream changes
- **Always available** - Not dependent on pub.dev uptime
- **Team accessible** - Any developer on the team can pull this directly

## Version

- **Base version**: GetX `4.7.3` (from [pub.dev/packages/get](https://pub.dev/packages/get))
- **Original author**: [jonataslaw](https://github.com/jonataslaw/getx)
- **License**: MIT (same as original)

## Usage

Add this to your `pubspec.yaml`:

```yaml
dependencies:
  get:
    git:
      url: https://github.com/rai-ms/getx.git
      ref: main
```

Then run:

```bash
flutter pub get
```

## What's included

Everything from GetX v4.7.3:

- **State Management** - Reactive (Rx) and Simple (GetBuilder) state management
- **Route Management** - Navigation without context, named routes, middleware
- **Dependency Injection** - `Get.put()`, `Get.lazyPut()`, `Get.find()`, bindings
- **GetConnect** - HTTP client with interceptors
- **GetStorage** alternative utilities
- **Internationalization** - Multi-language support
- **Utilities** - Extensions, platform detection, form validation

## Documentation

For full documentation, refer to the original GetX docs:

- [State Management](documentation/en_US/state_management.md)
- [Route Management](documentation/en_US/route_management.md)
- [Dependency Management](documentation/en_US/dependency_management.md)

## Maintained by

**rai-ms** - For internal use in Akku OTT and Genzit Solution projects.

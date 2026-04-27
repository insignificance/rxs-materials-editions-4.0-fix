# RxSwift: Reactive Programming with Swift: Materials (Fixed Version)

This is a **fixed version** of the RxSwift: Reactive Programming with Swift materials, updated to support modern iOS development environments.

This repo contains all the downloadable materials and projects associated with the **[RxSwift: Reactive Programming with Swift](https://store.raywenderlich.com/products/rxswift)** from [raywenderlich.com](https://www.raywenderlich.com).

Each edition has its own branch, named `editions/[EDITION]`. The default branch for this repo is for the most recent edition.

## Fixes Applied

### iOS Deployment Target
- Updated all projects from iOS 11.1/12.0/12.1/13.0 to **iOS 15.6**
- Updated `IPHONEOS_DEPLOYMENT_TARGET` in all `.pbxproj` files

### Dependency Versions
| Library | Old Version | New Version |
|---------|-------------|-------------|
| RxSwift | 5.1.1 | **6.5.0** |
| RxCocoa | 5.1.1 | **6.5.0** |
| RxRelay | 5.1.1 | **6.5.0** |
| RxTest | 5.1.1 | **6.5.0** |
| RxBlocking | 5.1.1 | **6.5.0** |
| RxDataSources | 4.0.1 | **5.0.0** |
| RxTimelane | 1.0.9 | **3.0.2** |
| RealmSwift | 5.1.0 | **10.21.0** |
| RxRealm | 3.0.0 | **5.0.4** |

### Breaking Changes
- **RxRealmDataSources** 0.3.0 has been removed from projects (not compatible with RxSwift 6.x)
- All CocoaPods dependencies have been reinstalled with updated versions

## Requirements

- **Xcode 13+**
- **iOS 15.6+**
- **CocoaPods 1.10+**

## Usage

1. Clone this repository
2. Navigate to any project directory
3. Run `pod install` (if not already installed)
4. Open the `.xcworkspace` file in Xcode

## Release History

| Branch                                                                           | Edition | Release Date |
| -------------------------------------------------------------------------------- |:-------:|:------------:|
| [editions/4.0](https://github.com/raywenderlich/rxs-materials/tree/editions/4.0) | 4.0     | 2020-08-11   |
| [main](https://github.com/insignificance/rxs-materials-editions-4.0-fix) | 4.0 Fixed | 2026-04-27 |

## Original Repository

This is a fork/fix of the original [raywenderlich/rxs-materials](https://github.com/raywenderlich/rxs-materials) repository.

## License

See [LICENCE](LICENCE) file for details.

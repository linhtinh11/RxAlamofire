# Change Log
All notable changes to this project will be documented in this file.

---

## Master

#### Updated

#### Fixed

## 4.1.0

#### Updated

* Rename `RxProgress.totalBytesWritten` to `RxProgress.bytesRemaining`.
* Rename `RxProgress.totalBytesExpectedToWrite` to `RxProgress.totalBytes`.
* Convert `RxProgress.bytesRemaining` from a stored- to a computed-property.
* Convert `RxProgress.floatValue` from a function to a computed-property.
* Add `Equatable` conformation to `RxProgress`.
* Add Swift Package Manager support.
* Add helper methods for validation to `Observable<DataRequest>`.
* Add helper methods for common response types to `Observable<DataRequest>`.

#### Fixed

* Fix SPM Support
* Unify download and upload progress handling.
* Fix `Reactive<DataRequest>.progress` logic so it actually completes.

## 0.5.0
 * Fixing issues (
   [#2](https://github.com/oddbit/flutter_facebook_app_events/issues/2), 
   [#4](https://github.com/oddbit/flutter_facebook_app_events/issues/4) and 
   [#8](https://github.com/oddbit/flutter_facebook_app_events/issues/8): breaking configuration change for Android. See the README with information on what to add in `AndroidManifest.xml`
   
## 0.4.0 
 * Breaking name change of `logActivateApp` to `logActivatedApp`
 * Adding shorthand log methods
    - logDeactivatedApp
    - logCompletedRegistration
    - logRated
    - logViewContent

## 0.3.0 
  * Add sample of shorthand log methods for app events.
    - logActivateApp
  
## 0.2.1
 * Bug fixing.
 
## 0.2.0
 * Adding app events 
    - `logPushNotificationOpen`
    - `flush`
    - `getApplicationId`

## 0.1.0
* First initial release supporting some basic functionality
  - `clearUserData`
  - `clearUserID`
  - `logEvent`
  - `setUserData`
  - `setUserID`
  - `updateUserProperties`

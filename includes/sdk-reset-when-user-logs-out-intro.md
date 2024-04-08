`reset` is a shortcut to anonymize users after they log out, by:

* setting `userId` to `null`
* setting `deviceId` to a new value based on current configuration

With an empty `userId` and a completely new `deviceId`, the current user would appear as a brand new user in dashboard.

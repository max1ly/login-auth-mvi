# Assessment for Login functionality

This is a basic implementation of login functionality that relies on authentication to grant access to a system or application

# What's done

Implementing the MVI architecture which includes Reducers and Middlewares requires a little more
boilerplate code comparing to classic MVVM. But once it's all set, the next features (like user profile screen) was
much pleasurable to work with.

I ended up with single activity application, where Jetpack Navigation library were used for
navigation between fragments.

`Dagger Hilt` is used for dependency injection, this only required two modules.

`Retrofit2` and `Gson` libraries are for handling network calls and parsing JSON accordingly.

`AccountManager` for storing and retrieving authentication token from Android system.

# What's missing

Couldn't get my head around to make `AuthenticationAPIClient` working with the initial authorization
instead of using `WebAuthProvider` with it's dependency on webview authorization method.
Otherwise I think it would be easier with the MVI structure here, as the webview authorization
strictly requires Activity to launch.

Unfortunately I couldn't use Jetpack Compose, as it would require few extra days to learn it little deeper
to my existing knowledge about it.

Didn't write any Unit tests, as I ran out of time I dedicated for myself to accomplish this task.

# Overall

Thanks for the opportunity, it was fun

# Screenshots

![](screenshots/2022-02-28-09-51-47-emulator-5554.png) ![](screenshots/2022-02-28-09-53-10-emulator-5554.png) ![](screenshots/2022-02-28-09-55-09-emulator-5554.png)

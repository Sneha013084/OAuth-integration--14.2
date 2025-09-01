# OAuth-integration--14.2

How an attacker can do CSRF in OAuth:

When you click Login with Google,your app sends you to Google and then gets an authorization code back.

An attacker could trick you into clicking a fake login link that actually gives back their authorization code.

Your app can’t tell the difference, so it might accidentally log you in with the attacker’s account instead of your own.

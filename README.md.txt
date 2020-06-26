Web API Document
Action | HTTP Method | Relative URI
-- | -- | --
Getting the user information for the account | GET | api/Account/UserInfo
Logging out of the current account | POST | api/Account/Logout
Manage Account information with return url and generate state. | GET | api/Account/ManageInfo?returnUrl={returnUrl}&generateState={generateState}
Change the Password for an existing account | POST | api/Account/ChangePassword
Set a password for a new account | POST | api/Account/SetPassword
Add an External Login Account | POST | api/Account/AddExternalLogin
Remove an Account | POST | api/Account/RemoveLogin
Getting an external Login Account Information with the provider and an error string. | GET | api/Account/ExternalLogin?provider={provider}&error={error}
Manage an external Account information with return url and generate state. | GET | api/Account/ExternalLogins?returnUrl={returnUrl}&generateState={generateState}
Register an account | POST | api/Account/Register
Register for an account with external login information. | POST | api/Account/RegisterExternal

# Error Codes in Sketchub API

Error Code | Possible Meaning
-----------|-----------------
ERR_INVALID_PARAMETER | The parameter value or format sent as key is not valid
ERR_PROFILE_NOT_FOUND | Profile not found
ERR_PROJECT_PRIVATE | User dont have permission to view the project because it is private
ERR_PROJECT_NOT_FOUND | The project not exists
ERR_INTERNAL_SERVER | Something is wrong on server side, ask support to fix the issue
ERR_QUOTA_EXCEEDED | You have exceeded the API queries limit
ERR_TOO_MUCH_REQUESTS | These error may occur when user is using Sketchub too much, solve the captcha
ERR_SHA256_TIMESTAMP_EXPIRED | Token expired, please enable "Automatic adjust time" in settings of your device if you are facing this problem again
ERR_PROJECT_SLOTS_EXCEEDED | The user exceeded his slots, he/she need to upgrade his paid plans
ERR_SHA256_ACCESS_DENIED | Invalid SHA256
ERR_DECRYPTION_FAILED | Recent encryption to emails and password is not done
ERR_ACCOUNT_BANNED | The user's account is banned
ERR_INVALID_USERNAME | Invalid username
ERR_INVALID_EMAIL | Invalid email
ERR_INVALID_USERNAME | The username contains invalid characters
ERR_EMAIL_PROVIDER_BANNED | The email provider is either not trusted or is remote mail box provider
ERR_ACCOUNT_ALREADY_EXISTS | If user is trying to create already existing account
ERR_USERNAME_TAKEN | The username is already taken
ERR_INTERNAL_EMAIL | Email servers are not working


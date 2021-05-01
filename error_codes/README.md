# Error Codes in Sketchub API

Error Code | Possible Meaning
-----------|-----------------
ERR_INVALID_PARAMETER | The parameter value or format sent as key is not valid
ERR_PROFILE_NOT_FOUND | Profile/account not found
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
ERR_ACCESS_DENIED | The user dont have permission to do something
ERR_INVALID_ARGUMENT | For example, trying to delete project which doesnt exists
OK | Dont trust OK for request status, it is not always provided, try to work from "status" key in the object
ERR_PROJECT_FILES_NOT_FOUND | When project is uploaded but files are not
ERR_EMPTY_PROJECT_DETAILS | Some project details are not provided while uploaded
ERR_PROJECT_DETAILS_CHAR_EXCEEDED | Some project details increased its text limit
ERR_EMAIL_COOLDOWN | There is 5 minutes of email cooldown, but if you follow "message" it will give you accurate time left for sending next email. Still then ask user to check spam
ERR_ACCOUNT_NOT_VERIFIED | The account user trying to access hasn't verified the email yet

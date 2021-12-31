# Error Codes in Sketchub API

Error Code | Possible Meaning
-----------|-----------------
ERR_ACCOUNT_ALREADY_EXISTS | If user is trying to create already existing account
ERR_ACCESS_DENIED | The user dont have permission to do something
ERR_ACCOUNT_BANNED | The user's account is banned, check "message" for ban reason
ERR_ACCOUNT_NOT_VERIFIED | The account user trying to access hasn't verified the email yet
ERR_API_QUOTA_EXCEEDED | You have exceeded the API queries limit
ERR_API_KEY_INVALID | The API key is invalid
ERR_COMMENT_COOLDOWN | The user did too much comments, ask them to wait for few minutes
ERR_COMMENTS_DISABLED | That specific project have disabled comments
ERR_CONTAINS_BADWORD | One of the input contains bad word
ERR_DECRYPTION_FAILED | Recent encryption to emails and password is not done
ERR_EMAIL_COOLDOWN | There is 5 minutes of email cooldown, but if you follow "message" it will give you accurate time left for sending next email. Still then ask user to check spam
ERR_EMAIL_PROVIDER_BANNED | The email provider is either not trusted or is remote mail box provider
ERR_EMPTY_PROJECT_DETAILS | Some project details are not provided while uploaded
ERR_INVALID_CAPTCHA | Invalid Captcha Response
ERR_INTERNAL_EMAIL | Email servers are not working
ERR_INTERNAL_SERVER | Something is wrong on server side, ask support to fix the issue
ERR_INVALID_ARGUMENT | For example, trying to delete project which doesnt exists
ERR_INVALID_EMAIL | Invalid email
ERR_INVALID_PARAMETER | The parameter value or format sent as key is not valid, it will also return this code for example, you are not limiting the message length in comments
ERR_INVALID_PASSWORD | Invalid password while doing authentication
ERR_INVALID_USERNAME | The username contains invalid characters
OK | Dont trust OK for request status, it is not always provided, try to work from "status" key in the object
ERR_PROJECT_DETAILS_CHAR_EXCEEDED | Some project details increased its text limit
ERR_PROJECT_FILES_NOT_FOUND | When project is uploaded but files are not
ERR_PROJECT_ICON_SIZE_EXCEEDED | When project icon size is exceeded while uploading
ERR_PROFILE_NOT_FOUND | Profile/account not found
ERR_PROJECT_NOT_FOUND | The project not exists
ERR_PROJECT_PRIVATE | User dont have permission to view the project because it is private
ERR_PROJECT_SCREENSHOT_SIZE_EXCEEDED | When a project screenshot size is exceeded while uploading
ERR_PROJECT_SIZE_EXCEEDED | The user have exceeded the limit of attachment size
ERR_PROJECT_SLOTS_EXCEEDED | The user exceeded his slots, he/she need to upgrade his paid plans
ERR_REPORT_COOLDOWN | Cooldown for abuse report
ERR_SHA256_ACCESS_DENIED | Invalid SHA256
ERR_SHA256_TIMESTAMP_EXPIRED | Token expired, please enable "Automatic adjust time" in settings of your device if you are facing this problem again
ERR_JWT_TOKEN_EXPIRED | JWT Token expired
ERR_TOO_MUCH_REQUESTS | These error may occur when user is using Sketchub too much, solve the captcha
ERR_USERNAME_TAKEN | The username is already taken
ERR_VERIFY_IP_MAIL | An IP verification email is sent

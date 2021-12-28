## Multi Factor Authentication - MFA

- MFA `adds extra security` because it `requires users to provide unique authentication` `from an AWS supported MFA mechanism` in addition to their regular sign-in credentials when they access AWS websites or services

## MFA Methods

1. Virtual MFA devices

- `A software app` that runs on a phone or other device and emulates a physical device

- The device `generates a six-digit numeric code` based upon a time-synchronized one-time password algorithm

- Supported MFA Application
  - Authy
  - Duo Mobile
  - LastPass Authenticator
  - Microsoft Authenticator
  - Google Authenticator
  - Symantec VIP

2. U2F security key

- This is `a physical device` that you `plug into a USB port on your computer`

- U2F is `an open authentication standard hosted by the FIDO Alliance`

3. Hardware MFA device

- `A hardware device` that `generates a six-digit numeric code` based upon a time-synchronized one-time password algorithm

- Each MFA device `assigned to a user must be unique`. A user `cannot type a code from another user's device to be authenticated`

4. SMS text message-based MFA

- The IAM user settings `include the phone number of the user's SMS-compatible mobile device`. When the user signs in, `AWS sends a six-digit numeric code` `by SMS text message to the user's mobile device`

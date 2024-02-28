# sendMail
Send Mail using Node js
The function `sendVarificationCodeOnMail` sends a verification code email to a specified email
 * address using nodemailer and checks for network availability before sending.
 * @returns The `sendVarificationCodeOnMail` function is being exported for external use. This function
 * sends a verification email to the provided email address with a verification code. It checks if the
 * network is available before sending the email. If the email is sent successfully, it returns `true`.
 * If there is an error during the process, it logs the error message and returns `false`.

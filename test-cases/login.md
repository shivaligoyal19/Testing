# Login Module - Test Cases

| **Test ID** | **Title**               | **Preconditions**           | **Steps**                                                                    | **Expected Result**                 | **Status**   |
|-------------|-------------------------|-----------------------------|----------------------------------------------------------------------------- |-------------------------------------|--------------|
| TC-001      | Login with valid user   | User account exists         | 1. Go to login page <br> 2. Enter valid username/password <br> 3. Click Login| User is redirected to dashboard     | Not Tested   |
| TC-002      | Login with wrong pass   | User account exists         | 1. Go to login page <br> 2. Enter wrong password <br> 3. Click Login         | Error message: "Invalid credentials"| Not Tested   |
| TC-003      | Reset password workflow | User email is verified      | 1. Click **Forgot Password** <br> 2. Enter email <br> 3. Check inbox         | Password reset email is received    | Not Tested   |

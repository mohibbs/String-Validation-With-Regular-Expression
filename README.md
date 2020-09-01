# Regular-Expression-Validation
Password REGEX with min 6 chars, max 16 chars, at least one Letter and one Number and may Contain Special Characters

#
 - var regularExpression = /^(?=.*[0-9])(?=.*[a-z])(?=.*[A-Z])(?=.*[!@#$%^&*])[a-zA-Z0-9!@#$%^&*]{6,16}$/;
 - console.log(regularExpression.test('Aa2@@8'));

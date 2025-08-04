public String encode(String message, int keyVal) {
String output = "";
char key = (char) keyVal;
for (int x = 0; x < message.length(); x++) {
char input = message.charAt(x);
if (input >= 'A' && input <= 'z')
{

}
else if (input >='a' && input <= 'z')
{

}
else if (input >= '0' && input <= '9')
{
input += (keyVal% 10);
if (input > '9')
input -= 10;
if (input < '0')
input += 10;

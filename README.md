# Remove-Only-Special-Characters-in-Java-Program
Many times I see that there is Remove Special Characters(!,@,#,$,%,&amp;,*) , Numbers(1234567890) , Spaces between Words nut there is no any program on Remove only Special Characters . So that's why I make this project.

#[^a-zA-Z0-9-\\s()] - This is Regular Expression which removes only Special Charaters from a String.
^ = Negation or Starting a Line. But if We can put on Strting that will not remove REGEX under this negation. Because this is negation.
a-z = Remove only small Alphabetsfrom String.
A-Z = Remove only Capital Alphabets from String.
0-9 = Remove only Numbers from String.
\\s() = Remove only Spaces between Words from String.

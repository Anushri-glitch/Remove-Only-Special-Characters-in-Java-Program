# Remove-Only-Special-Characters-in-Java-Program
Many times I see that there is Remove Special Characters(!,@,#,$,%,&amp;,*) , Numbers(1234567890) , Spaces between Words nut there is no any program on Remove only Special Characters . So that's why I make this project.

//Program for remove  only Special Charaters from String Other than Alphabets , Numbers and spaces.

import java.util.Scanner;
public class Best
{
    public static void main(String[] args)
    {
        String input;
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a String : ");
        input = sc.nextLine();
        System.out.println();
        System.out.println("Output String :" + input.replaceAll("[^a-zA-Z0-9-\\s()]+",""));
    }
}

#[^a-zA-Z0-9-\\s()] - This is Regular Expression which removes only Special Charaters from a String.
^ = Negation or Starting a Line. But if We can put on Strting that will not remove REGEX under this negation. Because this is negation.
a-z = Remove only small Alphabetsfrom String.
A-Z = Remove only Capital Alphabets from String.
0-9 = Remove only Numbers from String.
\\s() = Remove only Spaces between Words from String.

# ADCRJY_19BCAA06-adc.aditya.ac.in
import java.util.*;
class reddy
{
static int minimumLength(String s)
{
	int maxOcc = 0, n = s.length();
	int arr[] = new int[26];
	for (int i = 0; i < n; i++)
		arr[s.charAt(i) - 'a']++;
	for (int i = 0; i < 26; i++)
		if (arr[i] > maxOcc)
			maxOcc = arr[i];
	return (n - maxOcc);
}
	public static void main (String[] args) 
    {
	String str = "afddewqd";
	System.out.println( minimumLength(str));
	}
}
.............................................
 Output
5

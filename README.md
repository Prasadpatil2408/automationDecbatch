# automationDecbatch
public static void main(String[] args) {
		String s1="SILENT";
		String s2="LISTEN";
		char c1[]=s1.toCharArray();
		char c2[]=s2.toCharArray();
		if(c1.length!=c2.length)
		{
			System.out.println("not anagram");
		}
		Arrays.sort(c1);
		Arrays.sort(c2);
		for(int i=0;i<=c1.length-1;i++)
		{
			if(c1[i]!=c2[i])
			{
				System.out.println("not anagram");
			}else {
				System.out.println("anagram");
				System.exit(0);
			}
		}
	



# learning
public class oddPositioning
{

    static int oddPos(){
        int[] a={32, 11, 45, 65, 76, 77, 90};
        String spaces=" ";
        for(int i=0; i<a.length; i++)
        {
            if (a[i]%2 == 1)
            {
                spaces= spaces + a[i] + " ";

            }
        }
        System.out.println(spaces);
        return 0;
    }

    public static void main(String[] args)
    {
        System.out.println(oddPos());
    }
}

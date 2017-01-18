static void Main(string[] args)
        {
            int a, b,sum;
            a = 1;
            b = 1;
            sum = 0;
            for (int i = 0; i < 5; i++)
            {
              // Console.WriteLine("a="+a + " b=" + b );
                sum += add(ref a,b);
            }
            Console.WriteLine("Total Sum=" +sum);
        //    Console.ReadKey();

        }
        public static int add(ref int a,int b)
        {
            int temp1=2;
            int temp2=3;
            int temp3=4;
            int temp = a + b;
            a = temp;
            temp1 = temp2 * temp3;
            Console.Write("Temporary Sum ="+temp+"\n");
            return temp;
        }

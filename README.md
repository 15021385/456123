# 456123
int a1, a2, a3, m1, m2;
            a1 = int.Parse(Console.ReadLine());
            a2 = int.Parse(Console.ReadLine());
            a3 = int.Parse(Console.ReadLine());
            m1 = a3 - a2;
            m2 = a2 - a1;
            if (m1 == m2)
            {
                Console.WriteLine("yes");
            }
            else
            {
                Console.WriteLine("no");

            }
            Console.ReadLine();
            else
            {
                r1 = 365 - 186 + ((m1 - 7) * 30 + d1);
            }
            if (m1 < 7)
            {
                r2 = 365 - ((m2 - 1) * 31 + d2);
            }
            else
            {
                r2 = 186 + ((m2 - 7) * 30 + d2);
            }
            r3 = (y2 - (y1 + 1)) * 365;
            r = (r3 + r1 + r2) ;
            Console.WriteLine(r);
            Console.ReadLine();

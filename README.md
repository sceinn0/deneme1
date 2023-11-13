# deneme1
rapci efekt denene
Random rs=new Random();
	  int sayi;
        for (int i = 0; i < 100; i++)
        {
            sayi=rs.Next(1,11);

            if (sayi==1)
            {
                Console.WriteLine("Jagged");
				Console.Clear(); 
            }
			else if (sayi==2)
            {
                Console.WriteLine("Ceza");
			    Console.Clear(); 
            }
			else if (sayi==3)
            {
                Console.WriteLine("Sagopa Kajmer");
				Console.Clear();
            }
			else if (sayi==4)
            {
                Console.WriteLine("Allame");
				Console.Clear();
            }
			else if (sayi==5)
            {
                Console.WriteLine("Joker");
				Console.Clear();
            }
			else if (sayi==6)
            {
                Console.WriteLine("Hidra");
				Console.Clear();
            }
			else if (sayi==7)
            {
                Console.WriteLine("Sehinsah");
				Console.Clear();
            }
			else if (sayi==8)
            {
                Console.WriteLine("Stabil");
				Console.Clear();
            }
			else if (sayi==9)
            {
                Console.WriteLine("Sansar Salvo");
				Console.Clear();
            }
			else
            {
                Console.WriteLine("Saian");
				Console.Clear();
            }

        }
		sayi=rs.Next(1,10);
		if (sayi==1)
            {
                Console.WriteLine("Jagged");
            }
			else if (sayi==2)
            {
                Console.WriteLine("Ceza");
            }
			else if (sayi==3)
            {
                Console.WriteLine("Sagopa Kajmer");
            }
			else if (sayi==4)
            {
                Console.WriteLine("Allame");
            }
			else if (sayi==5)
            {
                Console.WriteLine("Joker");
            }
			else if (sayi==6)
            {
                Console.WriteLine("Hidra");
            }
			else if (sayi==7)
            {
                Console.WriteLine("Sehinsah");
            }
			else if (sayi==8)
            {
                Console.WriteLine("Stabil");
            }
			else if (sayi==9)
            {
                Console.WriteLine("Sansar Salvo");
            }
			else
            {
                Console.WriteLine("Saian");
            }
			Console.ReadKey();

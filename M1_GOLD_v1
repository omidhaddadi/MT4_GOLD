
int start()

  {

   double lot_buy_01=0.1,lot_sell_01=0.1,lot_buy_02=0.1,lot_sell_02=0.1;

   double stoploss=(1000*Point);

   double takeprofit=(5000*Point);

   int DXPeriod=20,j=0;

   int wait_minute=1;

   int    starti,i=DXPeriod,counted_bars=IndicatorCounted();

   int q,p,m,n,total_order=OrdersTotal();

   double bestbuy,bestsell,adx,acc_equity=AccountEquity();

   double sar_value,bb_up_value,bb_low_value,envel_up_value,envel_low_value,max_bb_envel,min_bb_envel;


       

      for(int k=total_order-1; k>=0; k--)

         {

                if (OrderSelect(k, SELECT_BY_POS)){

                     if(OrderType()==OP_BUY ){q=1;}

                     if(OrderType()==OP_SELL){p=1;}

               }

         }

 

Enter file contents here$Title EUPHEMIA - A market coupling algorithm using BCH (BCHMKTCOUPLING,SEQ=2626)
$ontext
The task is to identify the orders (demand and supply) that should be accepted in multi-bidding area electricity market.
The objective is to maximise the consumer surplus+supplier surplus+congestion rent.

The CG method is implemented using BCH. The running LP solver calls
out to a BCH pricing call and that supplies new columns.

$offtext
$eolcom //

Sets
         N       nodes    /N1,N2,N3,N4,N5,N6,N7,N8,N9,N10,N11*N50/
         Gen     number of generators    /G1*G10/
         Cons    number of consumers     /S1*S10/
         BA      bidding areas /BA1*BA8/
         ATC(N,N) Available Transmission Capacities /#N.#N/
         BidVol(N,Gen)
         l       order type //;

Parameters
         demandprice(i)    demandprice   /dp1  45
                          dp2  36
                          dp3  31
                          dp4  14/

         demandvolume(i)   demandvolumes   /dv1  100
                          dp2  200
                          dp3  300
                          dp4  500/

         supplyprice(i)

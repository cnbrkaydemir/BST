#Find the root of Bst

7, 5, 1, 8, 3, 6, 0, 9, 4, 2 //Rememeber the property of Bst where left side is smaller and right side is bigger


7 //First element is at the root


    7  //
  /   //  Add 5
5    //


        7  //
      /   //  Add 1
    5    //
  /
1


        7     //
      /  \    //  Add 8
    5     8    //
  /
1


        7     //
      /  \    //  Add 3
    5     8   //
  /           //
1             //
  \           //
    3



        7     //
      /  \    //  Add 6
    5     8   //
  /   \        //
1      6       //
  \           //
    3
    


          7     //
        /  \    //  Add 0
      5     8   //
    /   \        //
   1      6       //
  / \           //
 0   3
    
     
         7          //
        /  \        //  Add 9
      5     8       //
    /   \     \     //
   1      6    9   //
  / \             //
 0   3
    


         7            //
        /  \          //  Add 4
      5     8         //
    /   \     \      //
   1      6    9    //
  / \              //
 0   3            //
      \
       4
       
    
         7            //
        /  \          //  Add 2
      5     8         //
    /   \     \      //
   1      6    9    //
  / \              //
 0    3            //
     / \
    2   4
    
    
    









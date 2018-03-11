# dragvisuals
 - Vim global plugin for dragging virtual blocks


- Last change: Tue Jul 24 07:19:35 EST 2012 
- Maintainer: Damian Conway 
- License: This file is placed in the public domain.


- Add the following (uncommented) to your .vimrc...                  
   ```                                                                 
   runtime plugin/dragvisuals.vim                              
                                                                
    vmap  <expr>  <LEFT>   DVB_Drag('left')                     
   
    vmap  <expr>  <RIGHT>  DVB_Drag('right')                    
   
    vmap  <expr>  <DOWN>   DVB_Drag('down')                         
   
    vmap  <expr>  <UP>     DVB_Drag('up')                           
                                                               
    let g:DVB_TrimWS = 1                                        
                                                                   
   Or, if you use the arrow keys for normal motions, choose           
  four other keys for block dragging. For example:                   
                                                                
   vmap  <expr>  h        DVB_Drag('left')                         
   
   vmap  <expr>  l        DVB_Drag('right')                    
   
   vmap  <expr>  j        DVB_Drag('down')                         
   
   vmap  <expr>  k        DVB_Drag('up')                           
                                                                     
  Or:                                                                
                                                                     
    vmap  <expr>  <S-LEFT>   DVB_Drag('left')                       
    
    vmap  <expr>  <S-RIGHT>  DVB_Drag('right')                      
    
    vmap  <expr>  <S-DOWN>   DVB_Drag('down')                       
    
    vmap  <expr>  <S-UP>     DVB_Drag('up')                         
                                                                     
    Or even:                                                       
                                                                     
     vmap  <expr>   <LEFT><LEFT>   DVB_Drag('left')                  
    
     vmap  <expr>  <RIGHT><RIGHT>  DVB_Drag('right')             
    
     vmap  <expr>   <DOWN><DOWN>   DVB_Drag('down')                  
    
     vmap  <expr>     <UP><UP>     DVB_Drag('up')    

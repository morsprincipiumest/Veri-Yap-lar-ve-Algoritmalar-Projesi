# Proje 3 

1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap

```
Root sayımız 7 olsun.

                        7   
                       /            Aşama 1
                      5



                        7   
                       /      
                      5             Aşama 2
                     /    
                    1


                        7   
                       / \     
                      5   8         Aşama 3
                     /    
                    1


                        7   
                       / \     
                      5   8      
                     /              Aşama 4
                    1
                     \
                      3       


                        7   
                       / \     
                      5   8      
                     / \            Aşama 5
                    1   6        
                     \
                      3

                      
                        7   
                       / \     
                      5   8      
                     / \            Aşama 6
                    1   6        
                   / \
                  0   3
                  

                        7   
                       / \     
                      5   8      
                     / \   \         Aşama 7
                    1   6   9     
                   / \
                  0   3
                       \
                        4


                        7   
                       / \     
                      5   8      
                     / \   \         Aşama 8
                    1   6   9     
                   / \
                  0   3
                     / \
                    2   4

```
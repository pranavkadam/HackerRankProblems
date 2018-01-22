/*
  Remove all duplicate elements from a sorted linked list
  Node is defined as 
  struct Node
  {
     int data;
     struct Node *next;
  }
*/
Node* RemoveDuplicates(Node *head)
{
    if(head==nullptr){
        return nullptr;
    }
    if(head->next==nullptr){
        return head;
    }
    Node *trav=new Node;
    
    
    trav=head;
    
    
   // if(trav->data == trav1->data){
     //   head->next=nullptr;
       // delete trav1;
        //return head;
    //}
    
    while(trav->next!=nullptr){
        //
        if(trav->data==trav->next->data){
             Node *temp=new Node;
             temp=trav->next;
             trav->next=trav->next->next;
             delete temp;
           
        }
        else{
            trav=trav->next;
        }
        
        
    }
    return head;
    
   
}

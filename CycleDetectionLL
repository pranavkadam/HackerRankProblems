/*
Detect a cycle in a linked list. Note that the head pointer may be 'NULL' if the list is empty.

A Node is defined as: 
    struct Node {
        int data;
        struct Node* next;
    }
*/

bool has_cycle(Node* head) {
    if(head==nullptr){
        return false;
    }
    if(head->next==nullptr){
        return false;
    }
    Node* fast=new Node;
    Node* slow=new Node;
    
    fast=head->next;
    slow=head;
    
    while(fast->next!=nullptr){
        fast=fast->next->next;
        slow=slow->next;
        
        if(fast==slow){
            return true;
        }
    }
    
    return false;
    
  
}

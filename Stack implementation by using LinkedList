public class StackLL {
    Node head;
    class Node{
        int data;
        Node next;
        Node(int data){
            this.data=data;
            this.next=null;
        }
    }
    public boolean isEmpty(){
        return head==null;
    }
    public void push(int data){
        Node newNode=new Node(data);
        if(isEmpty()){
            head=newNode;
            return;
        }
        newNode.next=head;
        head=newNode;
    }
    public void pop(){
        if(isEmpty()){
            head=null;
            return;
        }
        head=head.next;
    }
    public void peek(){
        if(isEmpty()){
            System.out.println("Empty List");
            return;
        }
        System.out.println(head.data);
    }
    public static void main(String[] args){
        StackLL list=new StackLL();
        list.push(67);
        list.push(56);
        list.push(32);
        list.push(78);
        while(!list.isEmpty()){
            list.peek();
            list.pop();
        }
    }
}

import java.util.*;
public class ArrayListStack {
        static ArrayList<Integer> list=new ArrayList<>();
        public static boolean isEmpty(){
            return list.size()==0;
        }
        public static void push(int data){
            list.add(data);
        }
        public static int pop(){
            if(isEmpty()){
                System.out.println("Empty list");
                return -1;
            }
            int top=list.get(list.size()-1);
            list.remove(list.size()-1);
            return top;
        }
        public static int peek(){
            if(isEmpty()){
                System.out.println("Empty list");
                return -1;
            }
            int top=list.get(list.size()-1);
            return top;
        }
    public static void main(String[] args){
        ArrayListStack.push(67);
        ArrayListStack.push(98);
        ArrayListStack.push(34);
        ArrayListStack.push(90);
        while(!ArrayListStack.isEmpty()){
            System.out.println(ArrayListStack.peek());
            ArrayListStack.pop();
        }    
    }
}

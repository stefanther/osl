# osl

public class Queue {
    
    int front, rear;
    String[] antri;
    
    public Queue(int size){
        antri = new String[size];
        front = 0;
        rear = -1;
    }
    
    public void insert(String n){
        antri[++rear] = n;
    }
    
    public String delete(){
        return antri[front++];
    }
    
    public static void main(String[] args) {
    }
    
}

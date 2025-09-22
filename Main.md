# Main
    
    public class Main {
        public static void main(String[] args) {
            MyQueue queue = new MyQueue(5);
            queue.enQueue(1);
            queue.enQueue(2);
            queue.enQueue(3);
            queue.enQueue(4);
            queue.display();
            queue.deQueue();
            queue.display();
            queue.enQueue(5);
            queue.display();
        }
    }

# 1. Stack
### description
1. LIFO (Last In First Out)   

2. Variable: top (array의 index)   

3. Initialize: top = -1   

# 2. Queue
### description
1. FIFO (First In First Out)   

2. Variable: front, rear (rear: array의 index)   

## 2.1 Queue (no circular)
### description
1. Initialize: front = rear = -1   

2. dequeue할 때마다 front가 1씩 줄어드는데 다시 늘어나지 않아서 reuse 불가 => circular queue로 해결   

## 2.2 Circular Queue
### description
1. Initialize: front = rear = 0   

2. State:   
    * Empty state: front = rear   

    * Full state: (rear + 1) % queue_size = front   

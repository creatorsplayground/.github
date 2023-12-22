# Creator's playground

# Creator's playground

- Good to see you!
- We can easily create ideas that were only in your imagination.

```mermaid
flowchart TB
  subgraph user[ ]
    direction TB
    creator1([Creator])
    creator2([Creator])
    creator3([Creator])
  end
  subgraph cm[ ]
    direction LR
      subgraph cm1[ ]
        direction TB
        community1([Community])
        topic1([Topic])
        topic2([Topic])
        thread1([Thread])
        thread2([Thread])
        thread3([Thread])
        thread4([Thread])
        community1---topic1
        community1---topic2
        topic1---thread1
        topic1---thread2
        topic2---thread3
        topic2---thread4
      end

      subgraph cm2[ ]
        direction TB
        community2([Community])
        topic3([Topic])
        topic4([Topic])
        thread5([Thread])
        thread6([Thread])
        thread7([Thread])
        thread8([Thread])
        community2---topic3
        community2---topic4
        topic3---thread5
        topic3---thread6
        topic4---thread7
        topic4---thread8
      end
      cm1~~~cm2
  end
  creator1---cm
  creator2---cm
  creator3---cm
```
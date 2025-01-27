# AI102: Use AI for Peer-to-Peer Networking and Game Development

## **Course Overview**
This course introduces students to peer-to-peer (P2P) networking through Java programming. Students will learn how to design and implement simple 1-1 games, focusing on communication protocols, latency handling, and maintaining game state consistency.

The course culminates in a term project where students demo their implementation of one of three games:
  1. **Guess the Number**
  2. **Battleship**,
  3. **Word Chain**.

## **Week-by-Week Breakdown**
### **Week 1: Introduction to Networking and Peer-to-Peer Communication**
- **Topics Covered**:
  - What is networking? Overview of client-server vs. peer-to-peer models.
  - Basics of Java networking (`Socket` and `ServerSocket` classes).
  - Establishing a basic connection between two peers.
- **Hands-On Activity**:
  - Write a simple program where two peers exchange "Hello, World!" messages.
- **Key Concepts**:
  - IP addresses and ports.
  - How peers connect without a central server.

### **Week 2: Designing Communication Protocols**
- **Topics Covered**:
  - What is a protocol? Designing message formats using JSON.
  - Encoding and decoding messages in Java.
  - Handling errors (e.g., malformed messages).
- **Hands-On Activity**:
  - Define and implement a simple protocol for sending text messages between peers.
- **Key Concepts**:
  - Protocol schema design.
  - Parsing JSON in Java using libraries like `jackson`.

### **Week 3: Turn-Based Communication and State Management**
- **Topics Covered**:
  - Managing turn-based interactions in P2P games.
  - Synchronizing game state between peers.
  - Handling dropped or delayed messages (basic retries).
- **Hands-On Activity**:
  - Implement a basic turn-based interaction where players alternate sending numbers (e.g., a "ping-pong" simulation).
- **Key Concepts**:
  - Turn-taking logic.
  - Maintaining consistent state across peers.

### **Week 4: Handling Latency and Timeouts**
- **Topics Covered**:
  - What is latency? How does it affect P2P communication?
  - Implementing timeouts for unresponsive peers.
  - Strategies for handling dropped connections gracefully.
- **Hands-On Activity**:
  - Extend the turn-based interaction to include timeouts (e.g., if one peer doesn't respond within X seconds, the other wins).
- **Key Concepts**:
  - Latency in networks.
  - Using Java's `Socket.setSoTimeout()` for managing timeouts.

### **Week 5: Game Logic Implementation**
- **Topics Covered**:
  - Implementing game-specific logic for Guess the Number, Battleship, and Word Chain.
    - *Guess the Number*: Validating guesses and providing feedback (higher/lower).
    - *Battleship*: Representing grids and tracking hits/misses.
    - *Word Chain*: Validating words and ensuring they follow the rules.
- **Hands-On Activity**:
  - Start implementing one of the three games using the protocols taught earlier.
- **Key Concepts**:
  - Game-specific protocol extensions (e.g., sending guesses or grid coordinates).
  - Validating inputs.

### **Week 6: Advanced Features and Testing**
- **Topics Covered**:
  - Testing P2P games for edge cases (e.g., invalid inputs, dropped messages).
  - Adding optional features like tracking scores or replaying moves.
- **Hands-On Activity**:
  - Test each other's implementations by playing their games in pairs.
- **Key Concepts**:
  - Debugging P2P applications.
  - Extending functionality while maintaining protocol compatibility.

### **Week 7-8: In-Class Exercise Time**
- Students will have dedicated time to work on their term projects in class with guidance from the instructor.
- Focus on finalizing game logic, testing communication protocols, and ensuring smooth gameplay.

### **Week 9: Final Demo Day**
- Each student presents their implementation of one of the three games (**Guess the Number**, **Battleship**, or **Word Chain**) to the class.
- Peers play each other's games to test functionality and provide feedback.
- Emphasis on explaining their protocol design, handling of latency/errors, and overall implementation.

## **Key Takeaways**
By the end of this course, students will:
  1. Understand how peer-to-peer networking works in Java.
  2. Be able to design and implement communication protocols for turn-based games.
  3. Learn how to handle real-world challenges like latency, dropped connections, and state synchronization.

This syllabus balances foundational teaching with practical application, culminating in a fun, demo-able project that reinforces key networking concepts!

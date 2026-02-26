Day 17 - Docker Networks

Date: 26-02-2026

Objective: To understand Docker networking and how containers communicate with each other.

Introduction:
Docker networking allows containers to communicate with each other and with the outside world.
Each container runs in isolation, but Docker provides networking features to enable communication.
Types of Docker Networks:
1. Bridge Network (Default)
- Used for containers on the same host.
- Automatically created when Docker is installed.



2. Host Network
- Shares host’s networking.
- No isolation between container and host.

3. None Network
- Disables networking.

4. Custom Bridge Network
- User-defined network for better control.
Docker Network Commands Practiced:

docker network ls  
Lists available networks

docker network create mynetwork  
Creates a custom network

docker network inspect mynetwork  
Shows network details

docker network rm mynetwork  
Removes a network

Running Containers on Same Network:



docker run -d --name container1 --network mynetwork nginx  

docker run -d --name container2 --network mynetwork nginx  
Containers on same network can communicate using container names.

Importance in DevOps:



- Enables microservices communication

- Supports multi-container applications

- Required for Docker Compose setups

Conclusion:



Today I learned how Docker networking works and how containers communicate using bridge and custom networks.


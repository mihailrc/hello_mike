## Deploying hello world in ESP
 - you app has 2 parts: code and how to run it (dev + ops)
 - code:
   - write your code. You can use any language - for this I am using python
   - package your code into a Docker container - use Docker file
   - publish to an image repository
 - how to run it:
   - k8s manifests
   - concepts:
     - namespaces - organize your apps
     - pods - running your app in k8s
     - deployments - scalability and fault tolerance
     - services - expose an app running in pods, load balancing
     - service mesh - gateway to ESP - inteligent routing, certs, exposing things to the world
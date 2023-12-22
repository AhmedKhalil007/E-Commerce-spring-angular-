# Start your image with a node base image
FROM java:8

# Copy local directories to the current local directory of our docker image (/app)
COPY ${WORKSPACE}/ecom-backend/target/ecommerce-0.0.1-SNAPSHOT.jar ecommerce-0.0.1-SNAPSHOT.jar 



ENTRYPOINT ["java","-jar","ecommerce-0.0.1-SNAPSHOT.jar"]

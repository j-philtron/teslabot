# HW Week 13 Q&A
Below are the answers to the associated questions for the week 13 homework assignment.

## The questions and the answers:

1. What is the definition of a serverless application?

 - A serverless application is one that is run in the cloud without the app developer needing to manage the physical infrastructure (computer) that
 the app is running on. The developer usually doesn't pay for downtime. This allows the developer to focus on the application, instead of needing to
 worry about managing a server.


2. What is the definition of model serving and what are the two types?

 - Model serving is when an ML model is hosted (on the cloud or on-premises) and the functions are made available for users to interact with. The two
 types of model serving are batch and online. Batch deployment is when the model is fed a chunk of data and (typically) run on a schedule. The output 
 is then written to a file or table. Online deployment is when the model has an endpoint available such that users/applications can send requests to 
 the model and get a response on demand.


3. What are 3 advantages of deploying using Model Serving methods vs. deploying on GitHub Pages or HuggingFace for free?

 - Several advantages are: scalability, better help/support, control over hardware, better security, and reliability (automatic load-balancer operations).


4. What Is Machine Learning Inference? How Does Machine Learning Inference work? Please walk us through an example.

 - ML inference is when an ML model is used to process live input data and produce an output. It happens when the ML model has been trained and then 
 deployed. Users can then interact with the model, feeding it input and receiving output. An example is the sentiment analysis model in this repo. The 
 model was trained, deployed, and then we could feed it input (text) and receive output (positive/negative indication and a score) in real time.

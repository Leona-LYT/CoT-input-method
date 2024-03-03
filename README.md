# Chain of Thought for Input Method using Few-Shot ChatGPT

### Descriptions
This repository explores a novel approach for input method processing using the Chain of Thought (CoT) technique, particularly focused on integrating ChatGPT with WeChat for real-time inference and personalized fine-tuning. By analyzing the user's historical records, we first imitate their historical responses to grasp the user's language habits, etc., using CoT to better mimic user replies. The ultimate goal is to generate replies that are more in line with the user's habits based on their provided history.


### Key Features
#### Real-Time Inference: 
Process and output predictions directly within WeChat conversations provided by users in real-time.
#### Personalized Response: 
Customize the model based on individual user data for more accurate predictions. This includes mimicking the user's historical answers to better understand and replicate their language habits, thus providing responses that closely match their style and preferences.
#### Chain of Thought Processing:
Utilize CoT for improved understanding and processing of text prompts.
#### Integration with ChatGPT: 
Harness the power of Few-Shot ChatGPT for state-of-the-art performance in text prediction.


### Basic Steps
#### 1. Read data from WeChat chat history given by users.
#### 2. Process the text prompt using the CoT method.
#### 3. Output the prediction to users. 
Deliver the personalized prediction to users, ensuring it aligns with their usual communication style.
#### 4. Personalize and fine-tune the model.(future)

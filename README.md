# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 212222230112

### Aim: 
Scenario-Based Report Development Utilizing Diverse Prompting Techniques

### Algorithm:  
The goal of this experiment is to design and develop an AI-powered chatbot that can handle customer inquiries, provide support, and improve customer experience in a retail environment. Create prompts using various AI prompting techniques to guide your experiment, data collection, analysis, and report creation

### 1. Direct Instruction Prompts
Objective: Provide quick, specific replies to customer queries.
Prompt Pattern:
Prompt:
"When a user asks, 'Where is my order?', reply: 'Your order is currently in transit and expected to arrive by [delivery date].'"

### 2. Contextual Prompting
Objective: Use prior customer data or chat history for context-aware replies.
Prompt Pattern:
Prompt:
"If a customer previously complained about a delayed order, respond with: 'I remember you mentioned the order delay earlier. Let me check the latest status and ensure it's moving forward.'"

### 3. Persona-Based Prompting
Objective: Make the chatbot more human-like and engaging by adopting a customer-friendly persona.
Prompt Pattern:
Prompt:
"Pretend you're a cheerful shopping assistant. Use a warm tone like: 'Hi there! Looking for something in particular? I’d be happy to help you out!'"

### 4. Few-Shot Prompting
Objective: Train the chatbot using example queries and responses.
Prompt Pattern:
Prompt:
"Examples:
'Can I return a product I bought last week?' → 'Yes, you can return products within 15 days. Let me help you with the process.'
'My payment failed.' → 'I’m sorry to hear that! Let me check your transaction and guide you to complete the order.'

Now, respond to: 'I received a defective item.'"

### 5. Chain of Thought Prompting
Objective: Use step-by-step logic for complex tasks like troubleshooting or returns.
Prompt Pattern:
Prompt:
"When a customer says their product arrived damaged:

Apologize.

Ask for order ID.

Guide them to upload a photo.

Initiate the return request.

Now handle: 'I got the wrong item in my order.'"

### 6. Instruction with Constraints
Objective: Provide clear responses within specific tone and word limits.
Prompt Pattern:
Prompt:
"Respond in under 30 words using simple language.
'Hi! Your return is being processed and you'll get your refund within 5–7 business days.'"

### 7. Reflective Prompting
Objective: Echo the user's intent to clarify their issue before solving it.
Prompt Pattern:
Prompt:
"If a user asks, 'Can I exchange my shoes for a different size?', reply with: 'You’d like to exchange your shoes for a different size, right? Let me show you how.'"

### Use Case
E-Commerce Platform:
An AI chatbot for an online shopping website that supports customers with:

Order tracking

Product inquiries

Returns and exchanges

Refund status

Payment issues

For each prompting style, ChatGPT and Claude are prompted to respond to realistic customer queries within the platform to test their effectiveness.

### ALGORITHM
Step 1: Define Use Case
Design prompts for a virtual assistant helping users shop online, manage orders, and troubleshoot issues.

Step 2: Define Prompting Techniques
Direct Instruction – Predefined replies.

Contextual Prompting – Based on chat/user history.

Persona-Based – Adds warmth and friendliness.

Few-Shot Prompting – Provides example Q&A pairs.

Chain-of-Thought – Uses step-by-step reasoning.

Instruction with Constraints – Clear and concise replies.

Reflective Prompting – Mirrors the user's question to confirm intent.

Step 3: Prompt AI Tools
Each prompt was tested in ChatGPT and Claude.

Step 4: Capture Outputs
Responses were collected and analyzed for tone, accuracy, and helpfulness.

Step 5: Analyze Output
Evaluated for:

Natural tone

Relevance of response

User-friendliness

Adherence to prompt pattern

### PROMPTS & OUTPUT OVERVIEW – E-COMMERCE PLATFORM CONTEXT
### 1. Preceding Question Prompting
Objective: To analyze customer sentiment and predict engagement or purchase intent based on previous product-related interactions on an e-commerce platform.

Prompt:

"Given the following customer interaction on our e-commerce platform, can you assess the sentiment and predict the likelihood of purchase?
'Just browsed your new eco-friendly product collection. Impressed by the variety and quality! Looking forward to ordering soon.'"

ChatGPT Output:

Sentiment: Positive

Engagement Prediction: High purchase intent due to positive feedback and future-oriented language.

Reasoning: Words like “impressed” and “looking forward” indicate a strong possibility of conversion.

| **Platform** | **Sentiment** | **Purchase Intent Prediction** | **Analysis**                                                                               |
| ------------ | ------------- | ------------------------------ | ------------------------------------------------------------------------------------------ |
| **ChatGPT**  | Positive      | High                           | Correctly identified optimistic customer sentiment and predicted future purchase behavior. |
| **Claude**   | Positive      | High                           | Mirrored ChatGPT's accuracy with slightly more emphasis on language tone.                  |


Evaluation:

Accuracy: Both models accurately assessed the sentiment and predicted engagement.

Coherence: Clear, logical analysis in both responses.

Relevance: Focused on e-commerce-specific cues like browsing behavior and intent to buy.

Speed: Both responses were timely and efficient.

### 2. Comparative Analysis Prompt
Objective: To compare a customer inquiry with a typical product description, identifying differences in tone, clarity, and persuasive value.

Prompt:

"Compare the following customer message with a standard e-commerce product description. How do they differ in tone, language, and conversion potential?
'I’m interested in this new jacket. Can you tell me about the material and if it’s suitable for cold weather?'"

ChatGPT Output:

Tone Comparison: The customer message is conversational and inquiry-driven, while a product description is more informative and direct.

Language: The customer uses natural, exploratory language; product descriptions are formal and detail-oriented.

Conversion Potential: Moderate to high — the message shows strong interest, and a helpful response could lead to a sale.

| **Platform** | **Tone Comparison** | **Language**        | **Conversion Potential** | **Analysis**                                                                          |
| ------------ | ------------------- | ------------------- | ------------------------ | ------------------------------------------------------------------------------------- |
| **ChatGPT**  | Inquiry-based tone  | Conversational      | Moderate to high         | Accurate tone and engagement breakdown, though lacking depth on the emotional impact. |
| **Claude**   | Inquisitive tone    | Natural, subjective | Moderate                 | Slightly more analytical in tone comparison, adding nuance around uncertainty.        |


Evaluation:

Insightfulness: Claude gave a slightly more layered analysis of tone.

Tone & Language: Both platforms accurately identified informal vs. formal contrasts.

Conversion Prediction: Both identified potential for conversion with appropriate follow-up.

Speed: Efficient responses from both.

### 3. Experiential Perspective Prompt
Objective: To simulate a customer's emotional experience while browsing the product listing and predict their level of engagement or conversion.

Prompt:

"Imagine you are a customer viewing this product listing:
'Handcrafted by local artisans, this eco-conscious tableware set is made from sustainable bamboo and reflects a commitment to quality and ethics.'
How would you feel about it, and would you be inclined to purchase?"

ChatGPT Output:

Emotional Reaction: Positive; the customer would feel connected to the values of sustainability and craftsmanship.

Conversion Likelihood: High — the emotional appeal and ethical language increase the chance of a sale.

Reasoning: Product values align with customer values, often a key factor in purchase decisions.

| **Platform** | **Emotional Reaction** | **Conversion Insight** | **Analysis**                                                        |
| ------------ | ---------------------- | ---------------------- | ------------------------------------------------------------------- |
| **ChatGPT**  | Connected, supportive  | High                   | Identified core emotional triggers like sustainability and quality. |
| **Claude**   | Inspired, aligned      | High                   | Provided a more emotionally rich response tied to personal values.  |


Evaluation:

Empathy: Claude’s output was more emotionally intelligent and value-aligned.

Engagement Prediction: Both platforms were aligned in identifying high conversion potential.

Relevance: Excellent relevance to e-commerce settings where ethical products matter.

Speed: Fast and clear responses.

### RESULT: Prompt Performance Summary
| Prompt Type                         | Best Performing Platform | Summary of Findings                                                   |
| ----------------------------------- | ------------------------ | --------------------------------------------------------------------- |
| **Preceding Question Prompting**    | Tie (ChatGPT & Claude)   | Both excelled in identifying sentiment and predicting buyer behavior. |
| **Comparative Analysis Prompt**     | ChatGPT                  | Provided clearer structural breakdown of language and tone.           |
| **Experiential Perspective Prompt** | Claude                   | More emotionally aware and effective at simulating customer reaction. |


###  INSIGHTS
ChatGPT excelled at comparing structured communication and clarifying tone and language contrasts.

Claude stood out in human-centered prompts, showing stronger emotional depth in experiential simulations.

Both platforms reliably handled straightforward sentiment prediction and engagement forecasting within an e-commerce framework.

###  CONCLUSION
Preceding Question Prompting results show both platforms handle customer sentiment and buying intent well in e-commerce.

Comparative Analysis Prompt shows ChatGPT is strong at dissecting tone and structure in consumer queries vs. product copy.

Experiential Perspective Prompt highlights Claude’s superior ability to simulate emotional engagement with product listings.

## Result:
Thus the Prompts were exected succcessfully .


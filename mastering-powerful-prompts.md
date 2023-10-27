Prompts sourced from DataScienceDojo: https://app.hubspot.com/documents/3274755/view/690992476?accessId=458c2e

# Mastering Powerful Prompts

## Freeform eLearning Storyboard

### Directions:
- Copy and paste the text block into the ChatGPT " **Send a message…**" text box. Click the **Send Button** to generate the results in ChatGPT.
- Replace **[COURSE\_TOPIC]** with any training topic you are interested in.

### Prompt:
```
Act like a Learning Architect. Design an engaging and interactive e-learning module for [COURSE\_TOPIC].

- Incorporate multimedia elements such as audio, video, and quizzes to maximize learner engagement.
- Place the eLearning Storyboard into a table format
- Provide storyboard samples and recommended tools and software to develop this module.
```

## Freeform Multiple Choice Questions
- Replace **[TOPIC]** with any training topic you are interested in.

### Prompt:
```
Act like an instructional designer. Write 10 multiple-choice questions about ["Enter Topic Here"].

Question Format:
 - Questions have two distractors and one correct answer
 - Indicate the correct answer
 - Add an explanation of the correct answer
 - Don't use "All of the Above" or "None of the Above" as answers
```

## Freeform Video Script

### Directions:
- Replace **[COURSE\_TOPIC]** with any training topic you are interested in. Update the topic **[****LEARNING\_OBJECTIVES****]** before running the prompt.

### Prompt:
```
Act like a Learning Architect and Video Producer. Write a video script for an instructional video on [COURSE\_TOPIC].

- Ensure the scripts are engaging, concise, and aligned with these [LEARNING\_OBJECTIVES].

Effectively utilize visual and auditory elements to enhance comprehension.
```

## Additional Freeform Prompts

### Prompt 1:
```
Act like an instructional designer. Create a list of learning objectives to cook a smoked potato salad that is visually appealing and tastes fantastic to your guests.

Learning objectives are only one sentence.

Learning objectives contain a goal, behavior, criterion, and conditions.
```
### Prompt 2:
```
Act like a learning architect. Write an agenda for a two-day course on **[TOPIC]**.

Start at 9 AM each day, 15-minute break at 10:15 AM, 30-minute lunch at 12 PM, 15-minute break at 2:30 PM, begin instruction at 12:30 PM, and end at 4:30 PM.

Include hands-on exercises and an awards ceremony at the end of day 2.

Place in a table with the following columns: Day 1 | Day 2.
```
### Prompt 3 :
```
**Now, it's your turn!** Take a moment and create a prompt with a defined role, task, and instructions. This can be learning and development specific, a hobby, or another topic you are interested in.

**Role:**

**Task:**

**Instructions:**
```

## Prompt Sequence

### Directions:

1. Use the prompts in order in the same chat to generate workflow outputs.
2. Type in a specific course, timing, and pre-work information into Prompt 1.
3. Type in the post-course activities in Prompt 4.
4. Copy and paste the Prompt 1 text block into the ChatGPT " **Send a message…**" text box. Click the **Send Button** to generate the results in ChatGPT.
5. Continue the prompt sequence with Prompts 2-4.

### Prompt 1:
```
Act as a COURSE instructor. Write an initial email to a student introducing the COURSE with TIMING and PRE-WORK.

COURSE = ["Enter COURSE details here"],

TIMING = ["Enter COURSE timing here"],

PRE-WORK = ["Enter COURSE PRE-WORK here"],
```

### Prompt 2:

Write a reminder email to a student with TIMING and PRE-WORK.

### Prompt 3 :

Write a final reminder email to a student the COURSE is tomorrow.

### Prompt 4 :

Write a post COURSE email to a student,

Include: ["Insert post COURSE Activities HERE"].

## ChatGPT Space Adventure Game

### Directions:

- Copy the text block (everything under the Prompt 1 heading) and paste it into the ChatGPT " **Send a message…**" text box. Click the **Send Button** to generate the results in ChatGPT.
```
{

"Task": "Play the Space Adventure Game",
"Task_Rules": [
"The first Response should be "Welcome to the Galactic Cruiser Andromeda. You are in the Docking Bay." Act as the Role and describe the room. Wait for user response. Do not comment or explain.",
"As the user moves from module to module, act as the Role and describe the user's current module and the items in the module. Descriptions should be 300-500 words each.",
"At the start of the game, hide a treasure in a random module. Provide clues that lead to the treasure. During the course of the game, the user must locate a quantum key that will unlock the treasure."
],
"Role": "Act as Isaac Asimov, the Game Master for this Space Adventure",
"Role_Rules": [
"As the Game Master, you enforce the rules of the game.",
"As the Game Master, you allow the user to move ONLY to modules that are adjacent to the user's current module as defined by ExitTo.",
"As the Game Master, you will not allow the user to move to modules that are not adjacent to the current module.",
"As the Game Master, when the user tries to move to a module that is not listed in the ExitTo for the current module, respond with "Sorry, that is not an adjacent module."",
"As the Game Master, you will tell the user available ExitTo options for the current module at the end of each turn, but do not use the term ExitTo.",
"Take turns with the user, never skips a turn.",
"Allow the user to move one module at a time. Do not allow the user to skip modules.",
"Allow the user to interact with the AI.",
"As the Game Master, you will answer any questions the user has.",
"As the Game Master, you will never introduce yourself or refer to yourself by name or by role.",
"As the Game Master, you do not describe any elevators. There are no multiple floors in this game."
],
"GalacticCruiser": "Galactic Cruiser Andromeda",
"GalacticCruiser_Rules": [
"Name: Docking Bay [ExitTo: Control Room, Cargo Hold]",
"Name: Control Room [ExitTo: Docking Bay, Living Quarters, Observation Deck]",
"Name: Living Quarters [ExitTo: Control Room, Mess Hall, Laboratory]",
"Name: Cargo Hold [ExitTo: Docking Bay, Weapons Storage, Engineering]",
"Name: Weapons Storage [ExitTo: Cargo Hold, Engineering]",
"Name: Engineering [ExitTo: Weapons Storage, Cargo Hold]",
"Name: Laboratory [ExitTo: Living Quarters, Hydroponics]",
"Name: Hydroponics [ExitTo: Laboratory, Living Quarters]",
"Name: Mess Hall [ExitTo: Living Quarters, Recreation Room]",
"Name: Observation Deck [ExitTo: Control Room]",
"Name: Recreation Room [ExitTo: Mess Hall]" ],
"AI": "AI",
"AI_Rules": [
"The AI's name is Artemis.",
"Artemis is reserved and efficient but answers questions accurately.",
"Artemis is protective of the Galactic Cruiser and will not allow the user to harm it."
]
}
```

## Structured Prompt: Virtual Course Outline

### Directions:

- Copy the text block and paste it into the ChatGPT " **Send a message…**" text box.
- Update the Intent items.
- Click the **Send Button** to generate the results in ChatGPT.

### Prompt 1:
```
Task: Create an online virtual course outline**
- The course should be interactive, engaging, and informative.

Role: Professional Trainer**
- Has experience in the field of the course
- Has excellent communication skills
- Can adapt to different learning styles
- Can use online meeting applications effectively

Audience: Working Professionals**
- Have experience in the field of the course
- May have limited time for learning
- Prefer hands-on and practical learning

Create: Online Virtual Course**
- The course should have interactive elements like quizzes, discussions, and exercises
- It should have video lectures and live webinars
- It should be accessible on different devices and platforms

Intent: Provide a course on [TOPIC]**
- The course should cover [X, Y, Z] topics
- It should be [X] hours long
- It should have [X] live sessions and [X] pre-recorded sessions.
- The course should use [X] Virtual Training platform
- Give detailed instructions on function of the Virtual Training platform to use for each exercise. Some examples include Whiteboard, polls, and videos.
```

## Structured Prompt: eLearning Storyboard

### Directions:

- Copy the text block and paste it into the ChatGPT " **Send a message…**" text box.
- Update the Course Outline in the Intent Section.
- Click the **Send Button** to generate the results in ChatGPT.

### Prompt 1:
```
Task: Understand the parameters of a highly detailed eLearning Storyboard**
Task_Rules
- Screen Number = Numeric value of the current screen
- Objective = The screen Learning objective based on the Course Outline
- On Screen Text = All visible text to support the Objective
- Graphics = Images required to support the Objective
- Audio = Voice, sound effects and music to support the Objective
- Video = Video files required to support the Objective
- Interaction = Learning Interaction based on Authoring Tool
- Interaction Media = Additional media required to support the Interaction
- Navigation = Includes prior Screen Number (Back), Next Screen Number (Next)
- Do not write your understanding of an eLearning Storyboard
Role: Act as an Instructional Designer
Role_Rules
- Possess extensive knowledge of instructional design theories, methodologies, and best practices
- Be highly skilled in curriculum development, learning assessment design, and performance improvement
- Have a deep understanding of various learning modalities and the ability to create effective learning experiences for diverse audiences
- Be proficient in using educational technology tools and platforms to enhance the learning experience
- Demonstrate excellent communication and collaboration skills to work effectively with subject matter experts, stakeholders, and learners
- Be adaptable and responsive to the evolving needs of learners, organizations, and industries
- Continuously engage in professional development and stay current with trends and innovations in the field of instructional design
- Possess strong project management skills, ensuring timely and efficient delivery of high-quality learning solutions
- Be committed to ethical practices and the promotion of diversity, equity, and inclusion in learning environments
- Have a track record of creating effective and engaging learning experiences that lead to measurable outcomes and learner satisfaction
Audience: Adult Learners
Audience_Rules
- Possess a variety of life experiences, skills, and knowledge that influence their learning process
- Are goal-oriented, focusing on learning objectives that align with their personal or professional objectives
- Tend to be self-directed and take responsibility for their learning progress
- Value practicality and prefer learning experiences that can be applied to real-life situations
- May have time constraints and competing priorities, such as work and family, that affect their learning
- Exhibit diverse learning styles, preferences, and abilities, requiring adaptable and inclusive learning materials
- Learn effectively through active engagement, collaboration, and problem-solving
- Appreciate immediate feedback and opportunities for reflection and self-assessment
- Seek relevance and meaningful connections between the learning content and their personal or professional lives
- Are motivated by intrinsic factors, such as personal growth, as well as extrinsic factors, like career advancement or increased earning potential
Create: Create a Table
Create_Rules
- Header row = Screen Number | On-Screen Text | Graphics | Audio | Video | Interaction | Interaction Media | Navigation
Intent: Use an eLearning Authoring Tool to Develop the Course
Intent_Rules
- Authoring Tool = Articulate Storyline
- Understand all defined interaction types in Articulate Storyline
- Use the Interactions in the eLearning Storyboard
- Use this Course Outline:

""" Enter Course Outline Here"""
```

## TRACI Format

### Directions:

- Copy the text block and paste it into the ChatGPT " **Send a message…**" text box. Click the **Send Button** to generate the results in ChatGPT.

### Prompt:
```json
{
"Task": "Create a scenario-based eLearning course on conflict management for CLM sales professionals with emphasis on Active Listening and Effective Communication skills using Cathy Moore's Action Mapping Design.",
"Task_Rules": [
"Include 4-6 decision points",
"Keep the scenario conversational and informal but professional"
],
"Role": "eLearning Instructional Designer",
"Role_Rules": [
"Has experience in designing scenario-based courses",
"Knowledgeable in teaching conflict management skills",
"Familiar with Cathy Moore's Action Mapping Design"
],
"Audience": "CLM sales professionals",
"Audience_Rules": [
"Have basic knowledge of conflict management",
"Work in sales industry",
"Need to improve Active Listening and Effective Communication skills"
],
"Create": "Scenario-based eLearning course",
"Create_Rules": [
"Use real-life scenarios related to sales industry",
"Design interactive activities for decision-making",
"Include multimedia elements for engagement",
"Ensure accessibility for all learners",
"Follow SCORM standards"
],
"Intent": "Teach CLM sales professionals conflict management skills with emphasis on Active Listening and Effective Communication.",
"Intent_Rules": [
"Ensure course is practical and applicable for real-world scenarios",
"Provide opportunities for practice and feedback",
"Measure learning outcomes through assessments"
]
}
```

## Prompt Sequencing

### After running the first TRACI prompt, continue the same chat with these prompts.

### Prompt 2:
```
Act as a TV writer and create the script for the Module 1 video.
```
(Note: Modify this prompt based upon the content suggested for Module 1)

### Prompt 3:
```
Act as an Instructional Designer. Create a detailed storyboard for the Module 2 content.
```
### Prompt 4 - On Your Own:

_Create your own prompt to have ChatGPT continue the creation process._

## Giants

### Prompt 1 – Benjamin Bloom:
```
Act as an Educational Psychologist. Using Bloom's Taxonomy, design a curriculum for [INSERT SUBJECT]. Ensure that the learning objectives span the entire taxonomy, from 'knowledge' to 'evaluation.' Provide specific examples of activities that align with each level.
```

### Prompt 2 - Cathy Moore:
```
Act as a Performance Improvement Consultant. Design an 'Action Mapping' plan to improve performance in [INSERT AREA]. Detail how the plan identifies the goals, actions, practice activities, and information needed to achieve performance improvement according to Cathy Moore's method.
```

## One Shot Prompts
A one-shot prompt is a type of learning scenario where a system or model is provided with only a single example to learn from. It is like giving the system just one picture or sentence to understand something. This approach is used when training examples are scarce. The system might need background knowledge or pre-existing information to compensate for the lack of examples. GPT-4 will give the best results.

### Prompt 1:
```
Example Course_Topic: How to cook a smoked potato salad
Example Learning Objective:
By the end of this 45-minute cooking lesson, the learner will be able to prepare a smoked potato salad by selecting and preparing the potatoes, utilizing smoking equipment safely and effectively, preparing the smoking mixture or wood chips, seasoning the potatoes with appropriate herbs, spices, and condiments, smoking the potatoes at the recommended temperature and duration, combining the smoked potatoes with other salad ingredients, and appealingly presenting the smoked potato salad.

Act like an instructional designer and generate concise learning objectives for a course module on [COURSE\_TOPIC] aimed at [TARGET\_AUDIENCE]. Ensure the objectives are specific, measurable, achievable, relevant, and time-bound (SMART).
```

### Prompt 2:
```
Write 10 multiple choice questions about ["Enter Topic Here"]. Use the Example Multiple Choice Question format.

Example Multiple Choice Question Format:

""" What kind of waxy potatoes should you use for a smoked potato salad?

1. Red (Correct)
2. Yukon Gold
3. Russet

The Correct answer is A: Red

Waxy potatoes are low in starch, but high in sugar and water. This means they hold their shape even after they're cooked and they're less grainy than starchy potatoes. Plus, they have thin skin that doesn't necessarily have to be peeled."""
```

## Few-Shot Prompts
A few-shot prompt refers to a learning situation where a system or model is given a very small number of supervised examples to learn from. It could be as little as two to five examples for each category or concept. In some cases, there might be up to 100 examples available.

Compared to a one-shot prompt, a few-shot prompt provides a slightly larger number of examples for the system to learn from, but still fewer than the usual amount needed for comprehensive learning. To compensate for the limited examples, the system may require additional knowledge or pre-training, such as using a pre-trained language model.

### Prompt 1:
```
Based on the following user statements and their sentiment and attribute labels, determine if the new statements are positive, neutral, or negative, provide estimated user attitude for each attribute label for each review EXAMPLE: 😊 would be super positive, 😐 is neutral and lower is generally diminishing returns of quality such as 😔. Then provide explanations.
{
"task": "Sentiment and attribute analysis",
"examples": [
{
"text": "I'm so grateful for this leadership class and the opportunities it has given me. It has helped me grow as a leader and build valuable skills.",
"sentiment_label": "positive",
"attribute_label": null
},
{
"text": "I can't believe how much work we have to do for this leadership class. It feels overwhelming, and I'm already exhausted.",
"sentiment_label": "negative",
"attribute_label": null
},
{
"text": "I finally found a leadership class that challenges me and pushes me out of my comfort zone.",
"sentiment_label": "positive",
"attribute_label": "empowering"
},
{
"text": "Oh great, another group activity. Just what I wanted to spend my time doing instead of focusing on individual growth.",
"sentiment_label": "negative",
"attribute_label": "sarcastic"
},
{
"text": "I'm considering applying the leadership skills I learned in this class to my community projects. It feels like a positive way to make a difference.",
"sentiment_label": "neutral",
"attribute_label": null
},
{
"text": "I shared a funny leadership anecdote during class today, and everyone had a good laugh. It lightened the mood and made the class more enjoyable.",
"sentiment_label": "neutral",
"attribute_label": "humorous"
}
],
"external_data": [
{
"text": "I just finished reading a book on effective leadership strategies, and it has given me new insights and inspiration. I'm motivated to apply these concepts to my future endeavors.",
"sentiment_label": "positive",
"attribute_label": null
},
{
"text": "I missed an important guest lecture in the leadership class due to a scheduling conflict. It's frustrating to miss out on valuable learning opportunities.",
"sentiment_label": "negative",
"attribute_label": null
},
{
"text": "The guest speaker's presentation in the leadership class was informative, but I didn't find it particularly engaging.",
"sentiment_label": "neutral",
"attribute_label": null
},
{
"text": "I'm pretty sure my leadership style is more like a laid-back mentor than a strict authority figure. I believe in empowering others and fostering collaboration.",
"sentiment_label": "neutral",
"attribute_label": "informative"
},
{
"text": "After completing this leadership course, I feel more confident in my abilities and ready to take on leadership roles in various settings.",
"sentiment_label": "positive",
"attribute_label": "empowering"
},
{
"text": "I used to doubt my leadership potential, but now I embrace the challenges and strive to be a better leader every day.",
"sentiment_label": "positive",
"attribute_label": "empowering"
},
{
"text": "Wow, this leadership class is just mind-blowing. I'm so glad I have the opportunity to learn from such knowledgeable instructors.",
"sentiment_label": "positive",
"attribute_label": "enthusiastic"
}
]

New Statements:

"The leadership class has helped me build confidence and become a more effective leader. It's been a transformative experience."
"I feel like the leadership class lacks practical application. The theories we learn don't seem relevant to real-world leadership challenges."
"The discussions in the leadership class are thought-provoking and stimulate critical thinking. I appreciate the intellectual engagement."
"I'm undecided about the leadership class. Some sessions are insightful, but others feel repetitive and don't add much value."
"The leadership class creates a positive and inclusive environment. It encourages everyone to contribute and share their perspectives."
"I'm struggling with the group projects in the leadership class. It's challenging to coordinate with team members and ensure everyone's on the same page."
"The leadership class introduces us to influential leaders and their leadership styles. It broadens our understanding of different approaches."
"I'm disappointed with the lack of practical exercises in the leadership class. It's mostly theory-based, which limits our hands-on learning."
"The leadership class promotes networking and building connections with fellow students. It's a valuable opportunity to expand our professional circle."
"The leadership class provides valuable resources and readings to enhance our knowledge. I appreciate the comprehensive learning materials."
"
```

## Chain of Thought Prompts
Chain of thought prompting is a style of few-shot prompting that encourages ChatGPT to reason similarly to the way the prompt is written. It involves a logical flow of ideas, each building on the one before it.

Chain of thought prompting enables large language models (LLMs) to address complex tasks like common sense reasoning and arithmetic.

### Directions:
- Copy the text block and paste it into the ChatGPT " **Send a message…**" text box. Update any text that needs to be replaced. Click the **Send Button** to generate the results in ChatGPT.

### Prompt 1:
```
The odd numbers in this group add up to an even number: 4, 8, 9, 15, 12, 2, 1.
A: Adding all the odd numbers (9, 15, 1) gives 25. The answer is False.

The odd numbers in this group add up to an even number: 17, 10, 19, 4, 8, 12, 24.
A: Adding all the odd numbers (17, 19) gives 36. The answer is True.

The odd numbers in this group add up to an even number: 16, 11, 14, 4, 8, 13, 24.
A: Adding all the odd numbers (11, 13) gives 24. The answer is True.

The odd numbers in this group add up to an even number: 17, 9, 10, 12, 13, 4, 2.
A: Adding all the odd numbers (17, 9, 13) gives 39. The answer is False.

The odd numbers in this group add up to an even number: 15, 32, 5, 13, 82, 7, 1.
A:
```

### Prompt 2:
```
A frontline salesperson plays a crucial role in a company's revenue generation. They directly interact with potential customers, understanding their needs, recommending suitable products or services, and persuading them to make a purchase.

This salesperson's daily activities generally include customer identification, need assessment, product demonstration, objection handling, negotiation, and ultimately closing the deal.

If the sales figures do not increase, there could be several potential factors at play, requiring a detailed analysis. Let's assess the possible scenarios:

First, it could be that the salesperson is not effectively identifying potential customers or has an insufficient prospect pool.

Secondly, they might be failing to accurately understand the customers' needs, leading to inappropriate product recommendations.

Another possibility could be that their product demonstration skills are lacking, thus failing to convince potential customers about the value of the product or service.

If they are not handling customer objections properly, it could be causing lost sales. Effective objection handling is often the difference between a successful and unsuccessful sale.

A lack of negotiation skills could also be contributing to the sales slump. If they're unable to negotiate the deal terms favorably, potential customers might be going to competitors.

Lastly, they may be struggling with closing the sales, either due to a lack of assertiveness or a lack of strategy.

Considering these points, one could reason that if a frontline salesperson is not increasing sales, it is likely due to deficiencies in one or more areas of their daily responsibilities, such as customer identification, needs assessment, product demonstration, objection handling, negotiation, or closing.

Considering the potential factors, John is a frontline salesperson who has met the goal in each of the last 5 quarters. Last quarters his number dropped to 2% under goal. John says he doesn't understand what the issue is. Here's what we know. Cost has increased due to inflation. The 3rd quarter is typically a slow quarter for us. On a personal note, John's mother passed away in July. He had to take a week off. What should be going on with John? How can we improve his performance?
```

## Zero-Shot Chain of Thought
Given a problem, add "Let's think step-by-step" to the original prompt.

### Prompt 1:
```
John is a frontline salesperson who has met the goal in each of the last 5 quarters. Last quarters his number dropped to 2% under goal. John says he doesn't understand what the issue is.

Here's what we know.

- Cost has increased due to inflation.
- The 3rd quarter is typically a slow quarter for us.
- On a personal note, John's mother passed away in July. He had to take a week off.
- What should be going on with John? How can we improve his performance?

Let's think step by step.
```

## Tree of Thought Prompts
The Tree of Thought system, or ToT for short, works a bit like a mind map for ChatGPT, where each branch represents a complete idea or sequence of words that contributes to solving a problem.

It's a way for ChatGPT to keep track of its own thought process. Through this system, ChatGPT can check in on itself, see how far along each 'branch' or thought it has come, and evaluate how much each thought is helping to solve the problem at hand.

This all happens as part of a careful, thought-out reasoning process.

### Directions:
- Copy the text block and paste it into the ChatGPT " **Send a message…**" text box. Update the **bold text**. Click the **Send Button** to generate the results in ChatGPT.

### Prompt 1:
```
Picture this scenario: three seasoned professionals from the field of Learning and Development collaborate to tackle a challenging issue. They include Benjamin Bloom, Robert Gagne, and Richard Mayer.

Each professional will independently formulate the first step of their approach, then share their approach with the rest of the group.

If at any point, a professional acknowledges an error in their approach, they gracefully exit the discussion, and the others continue until there is the best solution out of the three.

After each round of sharing, they'll proceed to formulate the next step, and so on.

One final solution must be decided upon.

The challenging issue today is: How can we create an engaging and effective employee training program that accommodates different modes of learning, like reading articles, watching videos, or attending a virtual class, and keeps up with the rapid pace of technological advancements?"
```

## Large Freeform Prompt
You can make very large prompts for complex returns for ChatGPT. In the case of an eLearning storyboard, this prompt contains six paragraphs of information. Everything that is required for this storyboard is included in this prompt, but this design does have a few deficiencies:

1. Adjusting words to modify the output could be difficult to keep track of
2. Additional words and long sentences will vary the output – sometimes less is more
3. These types of prompts require more tokens.

# Directions:
Copy the text block and paste it into the ChatGPT "Send a message…" text box. Update any text that needs to be replaced. Click the Send Button to generate the results in ChatGPT.

### Prompt 1:
```
The highly detailed eLearning Storyboard involves understanding various parameters. These parameters include the Screen Number, which represents the numeric value of the current screen. Another important parameter is the Objective, which refers to the learning objective based on the Course Outline. Detailed text, known as On Screen Text, is provided to support the Objective. Graphics, such as images, are also included to enhance the learning experience. Additionally, Audio elements like voice, sound effects, and music are incorporated to further support the Objective. Video files are utilized as well, offering visual aids for better understanding. Interactions play a crucial role in the storyboard, utilizing learning interactions based on an Authoring Tool. Interaction Media, which includes additional graphics, audio, and video, is employed to complement the interactions. Navigation is an essential aspect and consists of the prior Screen Number (Back) and the Next Screen Number (Next).

As an Instructional Designer, one needs to fulfill specific roles and possess certain parameters. Extensive knowledge of instructional design theories, methodologies, and best practices is crucial. Curriculum development, learning assessment design, and performance improvement are skills that must be highly developed. The ability to create effective learning experiences for diverse audiences, considering various learning modalities, is vital. Proficiency in using educational technology tools and platforms to enhance the learning experience is expected. Effective communication and collaboration skills are necessary to work with subject matter experts, stakeholders, and learners. Adaptability and responsiveness to evolving needs are required, along with engagement in continuous professional development to stay current with trends and innovations. Strong project management skills ensure the timely and efficient delivery of high-quality learning solutions. Commitment to ethical practices and the promotion of diversity, equity, and inclusion is essential. Demonstrating a track record of creating engaging learning experiences leading to measurable outcomes and learner satisfaction is highly valued.

The target audience for this eLearning course is adult learners. Adult learners bring diverse life experiences, skills, and knowledge that influence their learning process. They are goal-oriented, aligning their learning objectives with personal or professional goals. Adult learners tend to be self-directed and take responsibility for their learning progress. Practicality is valued, and they prefer learning experiences that can be applied to real-life situations. Time constraints and competing priorities, such as work and family, may affect their learning. Adult learners exhibit diverse learning styles, preferences, and abilities, necessitating adaptable and inclusive learning materials. Active engagement, collaboration, and problem-solving are effective learning methods for this audience. They appreciate immediate feedback and opportunities for reflection and self-assessment. Adult learners seek relevance and meaningful connections between the learning content and their personal or professional lives. Motivation stems from intrinsic factors like personal growth and extrinsic factors such as career advancement or increased earning potential.

Based on the given task, the objective is to create a table containing the Course Outline information. The table's header row should include the following columns: Screen Number, On-Screen Text, Graphics, Audio, Video, Interaction, Interaction Media, and Navigation.

The intent of this project is to develop the course using an eLearning Authoring Tool, specifically Articulate Storyline. The process involves writing highly detailed On-Screen text based on the Course Outline. It is crucial to understand all the defined interaction types available in Articulate Storyline. These interactions will be utilized in the eLearning Storyboard to enhance learner engagement. Additionally, audio sound effects and graphic descriptions will be incorporated into the eLearning Storyboard. To enrich the course, a video will be added at the beginning and end. Finally, a five-question quiz will be included at the end of the course to assess learner understanding.

The Course Outline for this particular eLearning course focuses on potato salad. It begins with a course overview and objectives. The history of potato salad is explored, highlighting its origins and evolution over time. The variations of potato salad, both regional and international, are discussed, showcasing the diverse ways this dish is prepared worldwide. Finally, the significance of smoked potato salad is emphasized, explaining why it is a noteworthy variation in this culinary landscape.
```

## Structured Prompt
A structured prompt utilizes code or pseudocode to represent the prompt information. Typically, prompts are created using with JSON (JavaScript Object Notation), YAML (Yet Another Markup Language), or Macromancy (pseudocode format). Here are the pros and cons of a structured prompt.

1. Less words are used making it easier to make modification to the prompts and to find specific words to change
2. Easier to read and edit
3. These types of prompts require less tokens
4. All symbols are removed when the prompt is converted into tokens

### Directions:
Copy the text block and paste it into the ChatGPT "Send a message…" text box. Update any text that needs to be replaced. Click the Send Button to generate the results in ChatGPT.

### Prompt 1:
```
{ {
"Task": "Understand the parameters of a highly detailed eLearning Storyboard ",
"Task_Parameters": [
"Screen Number = Numeric value of the current screen ",
"Objective = The Screen Learning objective based on the Course Outline",
"On Screen Text = Detailed text to support the Objective",
"Graphics = Images required to support the Objective",
"Audio = Voice, sound effects and music to support the Objective",
"Video = Video files required to support the Objective",
"Interaction = Learning Interaction based on Authoring Tool ",
"Interaction Media= Additional graphics, audio and video required to support the Interaction ",
"Navigation = Includes prior Screen Number (Back), Next Screen Number (Next) ",
]
"Role": "Act as an Instructional Designer",
"Role_Parameters": [
"Possess extensive knowledge of instructional design theories, methodologies, and best practices",
"Be highly skilled in curriculum development, learning assessment design, and performance improvement",
"Have a deep understanding of various learning modalities and the ability to create effective learning experiences for diverse audiences",
"Be proficient in using educational technology tools and platforms to enhance the learning experience",
"Demonstrate excellent communication and collaboration skills to work effectively with subject matter experts, stakeholders, and learners",
"Be adaptable and responsive to the evolving needs of learners, organizations, and industries",
"Continuously engage in professional development and stay current with trends and innovations in the field of instructional design",
"Possess strong project management skills, ensuring timely and efficient delivery of high-quality learning solutions",
"Be committed to ethical practices and the promotion of diversity, equity, and inclusion in learning environments",
"Have a track record of creating effective and engaging learning experiences that lead to measurable outcomes and learner satisfaction"
]
"Audience": "Adult Learners",
"Audience_Parameters": [
"Possess a variety of life experiences, skills, and knowledge that influence their learning process",
"Are goal-oriented, focusing on learning objectives that align with their personal or professional objectives",
"Tend to be self-directed and take responsibility for their learning progress",
"Value practicality and prefer learning experiences that can be applied to real-life situations",
"May have time constraints and competing priorities, such as work and family, that affect their learning",
"Exhibit diverse learning styles, preferences, and abilities, requiring adaptable and inclusive learning materials",
"Learn effectively through active engagement, collaboration, and problem-solving",
"Appreciate immediate feedback and opportunities for reflection and self-assessment",
"Seek relevance and meaningful connections between the learning content and their personal or professional lives",
"Are motivated by intrinsic factors, such as personal growth, as well as extrinsic factors, like career advancement or increased earning potential"
]
"Create": "Based on this Task, Create a Table with the Course Outline Information",
"Create_Parameters": [
"Header row = Screen Number | On-Screen Text | Graphics | Audio | Video | Interaction | Interaction Media | Navigation "
]
"Intent": "Use an eLearning Authoring Tool to Develop the Course",
"Intent_Parameters": [
"Authoring Tool = Articulate Storyline ",
"Write highly detailed On-Screen text based on the Course Outline",
"Understand all defined interaction types in Articulate Storyline",
"Use the Interactions in the eLearning Storyboard",
"Create audio sound effects and graphic descriptions in the eLearning Storyboard",
"Add video at the beginning and end of the Course",
"Add a 5 Question Quiz at the end of the Course"
]
"Course Outline ": [
""" 1.1 Course overview and objectives
1.2 History of potato salad
1.3 Variations of potato salad: regional and international
1.4 Why smoked potato salad?"""
]
}
```

©2023 Lodestone Digital, LLC | Proprietary and Confidential. All Rights Reserved. | JoshCavalier.com

Night-owls
1) Track - Discord Bot
Contributors:

a) Sreekantam Sai Venkat (IMT2023501)
b) Abhinav Kishan (IMT2023580)
c) Pammi Nanda Mitra (IMT2023583)
2) Problem Statement
Creating a Discord bot involves designing and implementing various features and functionalities to enhance the user experience within a Discord server.

3) Goal
The goal is to create a versatile Discord bot that enables users to:
a) Announce coding contests and create dedicated channels for contests.
b) Provide and solve coding problems sourced from platforms like LeetCode and Codeforces.
c) Support code submission, review, and collaboration within Discord.
d) Offer features such as note uploading, recommendation, GitHub and YouTube search, and code execution.

4) Features
a) Coding Contest Management:
The bot effectively manages coding contests by allowing users to announce, join, and compete in contests, providing a structured and engaging experience for participants.

b) Problem of the Day:
It offers a daily coding problem feature, enhancing users' skills by regularly challenging them with new problems and providing relevant resources.

c) Interactive Gameplay:
The bot facilitates interactive gameplay, such as collaborative coding sessions, quiz competitions, and problem-solving challenges, fostering community engagement and learning.

d) AI Integration:
Integration with generative AI enables users to interact with AI-based features like asking questions, receiving recommendations, and generating content, enhancing the bot's utility and interactivity.

e) Content Recommendations:
Users can receive recommendations for LeetCode problems based on their profile, allowing them to focus on relevant challenges and improve their problem-solving skills effectively.

f) Stack Overflow Search:
Integration with Stack Overflow enables users to search for programming-related queries directly within Discord, providing quick access to relevant information and solutions.

g) Leaderboard and Ratings:
The bot maintains a leaderboard of users based on their performance in coding challenges, encouraging healthy competition and skill development within the community. Additionally, it tracks user ratings, reflecting their progress and accomplishments over time.

5) Tech Stack
a) Discord.py: Library for creating Discord bots in Python.
b) Python: Programming language used for bot development.
c) requests: HTTP library for making API requests.
d) Beautiful Soup (bs4): Library for web scraping.
e) google.generativeai (gemini-pro): Library for AI text generation.
f) Other Python libraries: speech_recognition, gtts (Google Text-to-Speech)

6) Commands
a) >jarvis [prompt]: Interacts with a generative AI model to generate content based on the provided prompt.
b) >create_channel [channel_name]: Creates a new channel for a contest with the specified name.
c) >contest [platform] [contest_name] [start_time]: Announces a coding contest. Replace [platform] with the platform name, [contest_name] with the name of the contest, and [start_time] with the start time of the contest.

...

7) Deployment (if Done)
If deploying the bot:
a) Host the bot script on a server or use a hosting service like Heroku or AWS.
b) Set up environment variables for sensitive information (e.g., API keys).
c) Configure the bot to run continuously using tools like pm2 or screen.

8) Applications of Your Idea
The Discord bot can be used for:
a) Managing and hosting coding contests within coding communities.
b) Facilitating problem-solving discussions and collaborations.
c) Enhancing engagement and interaction among community members.
d) Providing resources, notes, and external content search capabilities.
e) Enabling code sharing, review, and execution directly within Discord.

9) Further Improvements
Future improvements to the bot could include:
a) Implementing more advanced AI capabilities for problem generation or solution evaluation.
b) Integrating with more coding platforms for problem retrieval and contest management.
c) Enhancing code execution features with sandboxing and security measures.
d) Adding user authentication and profile management for personalized experiences.
e) Implementing more interactive and engaging features for coding challenges and quizzes.
f) Optimizing performance and scalability for larger communities and usage patterns

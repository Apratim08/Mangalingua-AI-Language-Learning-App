# Presenting Mangalingua!
This repo contains the code and other information about an application that I built as part of my CS260A finall project, "UI/UX Design and Development" at UC Berkeley. The application will soon be live on a public domain for users to test!

## Introduction
Many language-learners seek to broaden their abilities through consumption of media they already enjoy, such as movies, TV shows, and books. One such popular medium for Japanese language-learners is comics, or “manga”. However, there is a lack of a reliable tool to give valuable feedback on their learning. They also aren’t sensitive to the Japanese dialect and their references. Current learning apps generally cater to a broad range of language learners, offering structured lessons and exercise, whereas translation apps focus on general translation and fail to cover fictional aspects, cultural references, and nuances. Our aim is to develop an app that aims to solve the mentioned pain points by using computer vision LLM models to extract the Japanese text from the comics, convert it to a JSON format, and then run through a translation AI tool. The app will also have interesting features such as vocabulary saving, phrase parsing, and learning specific nouns and verbs.

## Customer and Market Research
We interviewed a varied set of subjects within a specific group of users. Interviewees varied in age (low to mid 20’s), gender, language fluency, occupancy, and hobbies. 
All target users were interested in learning languages, preferably through reading media, and had a cumbersome existing method of learning.

After doing market research, we realized that Language learners, both familiar with the language and beginners, currently rely on various online tools like Google Translate, Naver, and Easy German to translate media content such as books, 
switching between source text and translation apps to comprehend meanings. Desired tasks include smoother translations considering character names and nuances, a dictionary function for saving phrases and their translations, understanding 
grammatical structures, and comparing source text to translations for review. Users typically learn these tasks intuitively, iterating through different segments for translation and adjusting for inaccuracies. Tasks are predominantly performed at home, 
where users have the necessary privacy and time for learning. Users consume processed data to check understanding and utilize applications to support comprehension through translation and vocabulary analysis. They access tools like phones and computers to 
select text from images for translation and may use auxiliary apps to store personal vocabulary. Communication between users is unnecessary as the app is designed for solo use. Task frequency varies from every few days to once a day, 
serving as a supplement to other learning methods. Challenges arise when translations are incorrect, hindering comprehension and potentially leading to misunderstandings of context, interfering with language learning goals.

### Competitors 
<li> Drops: This app demonstrates the application of Visual Mnemonic and interaction-based vocabulary learning. However, it’s still hard to bridge the real-world usage since the given teaching contents including vocabulary and illustrations are far from the user’s real life, which might increase the memory burden. 
 </li>
<li> Google Translate: While Google Translate is an accessible option, the quality of its results make it difficult for language learners to accurately translate entertainment content, which is often long-winded and context heavy. Our app will also support user-specific content – such as “saved” vocabulary and phrases – to engage learning better. </li>
<li> Jiandanci: The app successfully combines learning the vocabulary with language context with the help of media, enabling people to understand the way to use certain words. Unlike our app, Jiandanci is more focused on memorization and exams – both of which are very formal situations requiring a distinct set of vocabulary. This means that Jiandanci is not as applicable to our form of media – written and/or illustrated.
 </li>
<li> Pimsleur: A versatile and portable learning platform that combines audio-centric learning with comprehensive reading lessons, voice recognition, and gamified elements. It stands out in emphasis on practical conversational skills making it suitable for a wide range of learners. However, potential improvements in visual interaction could elevate the user experience, particularly incorporating media such as books, movies, and tv-shows as a learning tool for users. </li>
<li> Naver: This is a leisure app which can be used for advanced Korean learners with the means of media including news, songs, and video. It also helps learners to understand unfamiliar expressions with their built-in dictionary app. However, it takes some time to switch from the media to the dictionary. Besides, the built-in dictionary has a limited vocabulary and cannot always accurately translate slangs or new expressions. 
</li>

## Prototype Design

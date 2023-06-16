<h1 align="center">
	<img src="https://github.com/marko-londo/IBM-ESPN-Case-Study/blob/main/Images/1%20-%20nfl%20player%20scoring%20a%20touchdown.png" alt="Processing the Perfect Lineup">
</h1>
<h1 align="center">
	<b>Processing the Perfect Lineup</b>
<br>
</h1>
<h2 align="center">
    <em>Analyzing the IBM Watson and ESPN Partnership</em>
</h2>
<br>
<br>

- [Introduction](#introduction)
- [What is NLP?](What-is-NLP?)
- [Overview and Origin](#Overview-and-Origin)
    - [What is IBM Watson?](#What-is-IBM-Watson?)
    - [Project Incorporation](#Project-Incorporation)
    - [Redefining Sports Coverage](#Redefining-Sports-Coverage)
- [Activities Driving Business Success](#Activities-Driving-Business-Success)
    - [Targeting the American Sports Fan](#Targeting-the-American-Sports-Fan)
    - [One-upping the Competition](#One-upping-the-Competition)
    - [Powering the NLP system](#Powering-the-NLP-system)
- [Evaluating the Market Landscape](#Evaluating-the-Market-Landscape)
    - [NLP in Sports](#NLP-in-Sports)
    - [Developments in Sports Analytics](#Developments-in-Sports-Analytics)
    - [Other Major Companies in the Sports Analytics Domain](#Other-Major-Companies-in-the-Sports-Analytics-Domain)
- [Suggestions for Business Improvement](#Suggestions-for-Business-Improvement)
    - [Start or Sit Chatbot (SoSBot)](#Start-or-Sit-Chatbot-(SoSBot))
    - [The Benefits of SoSBot](#The-Benefits-of-SoSBot)
    - [Technologies Required for SoSBot](#Technologies-Required-for-SoSBot)
    - [Suitability of Selected Technologies](#Suitability-of-Selected-Technologies)
- [Conclusion](#conclusion)
  
<br>
<hr>
<br>
<h1 align="center">
	<img src="https://github.com/marko-londo/IBM-ESPN-Case-Study/blob/main/Images/1%20-%20computer%20analyzing%20big%20data.png" alt="Introduction">
</h1>


## Introduction 
<br>[IBM Watson](https://www.ibm.com/watson "IBM Watson") and [ESPN](https://www.espn.com/ "ESPN")'s use of [natural language processing](https://www.ibm.com/topics/natural-language-processing/ "What is natural language processing?") is a fascinating case study that showcases the power of artificial intelligence in the world of sports. This project has garnered the attention of both sports fans and tech enthusiasts alike. By harnessing IBM Watson's advanced NLP capabilities, ESPN has acquired the tools necessary to reshape the landscape of sports journalism and analytics through faster reporting times and improved accuracy, and has applied these practices to enhance the [fantasy football](https://www.espn.com/fantasy/football/story/_/id/19522393/fantasy-football-how-play-fantasy-football-espn-fantasy-football-101 "Fantasy Football 101") experience.<br><br>

- ### What is NLP?

     As defined by IBM:
     >Natural language processing (NLP) refers to the branch of computer science—and more specifically, the branch of artificial intelligence or AI—concerned with giving computers the ability to understand text and spoken words in much the same way human beings can.

     NLP's order of operation is typically as follows:

     1. In order for the computer to analyze the data (video, audio or text), it is first [preprocessed, or "cleaned"](https://exchange.scale.com/public/blogs/preprocessing-techniques-in-nlp-a-guide "NLP Preprocessing Techniques"). This generally means simplifying it by removing punctuation, common words, or reducing words to their root form.
     1. The computer then analyzes the sentence structure and grammar. This is called syntactic analysis, or "parsing". Parsing aims to identify how words relate to eachother, such as subject-verb-object relationships.  <p align="center">
  <img src="https://github.com/marko-londo/IBM-ESPN-Case-Study/blob/main/Images/displacy.jpg?raw=true" width=90%/></p>
   1. Next is [semantic analysis](https://www.geeksforgeeks.org/understanding-semantic-analysis-nlp/ "Understanding Semantic Analysis "). In this step the machine determines the sentiment and roles of the words, in order to extract meaning and understanding from the text. 
    1. [Pragmatic processing](https://www.scaler.com/topics/pragmatics-in-nlp/ "Pragmatics") is applied to extract the context. Pragmatics focuses on the perceived tone, speaker intent and cultural conventions to fully understand the meaning of a piece of text.
    1. [Machine Learning and Deep Learning](https://www.coursera.org/articles/ai-vs-deep-learning-vs-machine-learning-beginners-guide "Deep Learning vs. Machine Learning") techniques are an essential part of NLP's functionality. Traditional machine learning algorithms and neural networks are used to train models for NLP tasks. These models learn patterns and relationsips in annotated data and us them to make predictions and perform language-related tasks.
    1. Ultimately, the models and algorithms are integrated into various applications and systems for human interaction. This could be anything from predictive text or auto-correct to chatbots and Amazon Alexa.

    NLP is a field that continues to grow and evolve by the day. Researchers and developers continuosly work to improve the accuracy and capabilities of their systems.<br>
<hr>
<br>
<h1 align="center">
	<img src="https://github.com/marko-londo/IBM-ESPN-Case-Study/blob/main/Images/1%20-%20a%20supercomputer%20analyzing%20data%20on%20a%20football%20f.png" alt="Overview and Origin">

## Overview and Origin
<br>This section provides an overview of the partnership between IBM Watson and ESPN, focusing on the use of NLP in the context of sports coverage and fantasy football.<br><br>

- ### What is IBM Watson?

     Named after IBM's founder, Thomas J. Watson, IBM Watson is an advanced computer system designed to process natural language questions and provide accurate answers. It combines artificial intelligence, sophisticated analytical software, and data analytics capabilities. The supercomputer can analyze vast repositories of data, utilizing NLP and 80 teraflops of processing power. Watson employs six million logic rules to replicate (or even surpass) human abilities in answering questions.<br><br>

- ### Project Incorporation

    The IBM Watson - ESPN project began in 2016. The idea was to leverage Watson's NLP processing capabilities to enhance the fantasy football experience for fans. Since it's incorporation, the project has grown significantly, with a team of several data scientists, software engineers, and product managers, all dedicated to improving the technology behind the project.<br><br>

- ### Redefining Sports Coverage

    The concept for the project came about as a result of ESPN's desire to improve their sports coverage, as traditional methods were often slow and unreliable. The goal was to provide fans with streamlined, up-to-date player stats and information with accuracy. NLP was identified as a potential solution to this problem, and together with IBM they began working to develop a system that could analyze and report on sports in real-time.
<br>
<br>
<hr>
<br>
<h1 align="center">
	<img src="https://github.com/marko-londo/IBM-ESPN-Case-Study/blob/main/Images/ai-nfl1.png" alt="Activities Driving Business Success">

## Activities Driving Business Success
<br>This section provides insight on the companies' target market, the factors that set them above the competition, and how they are implementing the technologies to power their product. <br><br>

- ### Targeting the American Sports Fan

    ESPN's intended customers are fantasy football (and general sports) fans who are looking for fast, accurate, and reliable coverage of their favorite players and teams. The market size for this set of customers is significant, as sports fans represent a large and passionate audience. ESPN is currently the number one provider in fantasy sports, serving over 20 million players across multiple platforms. With fantasy sports rising to approximately 50.4 million players in 2022, they account for nearly 40% of users in a $8.8 billion industry. <br><br>

- ### One-upping the Competition

    The main thing that sets IBM Watson and ESPN apart from their competitors is their ability to process vast amounts of data in real-time and generate insights based on that data. This allows them to provide fans with more up-to-date and accurate information than other sports media outlets or fantasy football providers. As of 2021 they added a new feature to their fantasy app; a trade analyzer with Watson. This tool uses AI to analyze vast quantities of football data in order to help fantasy league managers evaluate the fairness of a trade proposal by assigning a value to the players offered and/or pointing out the areas in which the counterparty's team are weak, ultimately assisting the manager in making (or offering) an educated trade.
    <p align="center">
  <img src="https://github.com/marko-londo/IBM-ESPN-Case-Study/blob/main/Images/Trade_Assistant_combined.jpg"/>
</p>
    <br>

- ### Powering the NLP System

    IBM Watson uses a variety of technologies to power their NLP system, including machine learning algorithms and deep neural networks [as defined in their blog](https://www.ibm.com/blog/ibm-watson-and-espn-use-ai-to-transform-fantasy-football-data-into-insight/ " IBM blog");
    >Using deep neural networks and advanced natural language processing, Player Insights with Watson combines the analyses of both structured and unstructured data to help fantasy managers compare players, estimate the potential upside and downside of starting a particular player and even assess the impact of an injury. It lets a fantasy owner visualize the risk-and-reward scenarios, see trends over time and field a more competitive team.
    >
    >Player Insights are built on containerized apps using Red Hat OpenShift running on the IBM Cloud. A machine learning engine pulls dozens of models from cloud object storage (running in Dallas and Washington, D.C., to ensure continuous availability).

        
    Watson continuously analyzes millions of player injury reports, opinion pieces and news stories to collect and correlate data on all players and teams in the league.<br>
<br>
<hr>
<br>
<h1 align="center">
	<img src="https://github.com/marko-londo/IBM-ESPN-Case-Study/blob/main/Images/2%20-%20computer%20analyzing%20big%20data%20(2).png" alt="Evaluating the Market Landscape">

## Evaluating the Market Landscape
<br>In this section we will discuss the broader use of NLP across the sports spectrum; major trends in the market and other major companies with similar ongoing projects and products. <br><br>

- ### NLP in Sports

    NLP has various applications in the sports world, not just for journalists and fans, but for teams, coaches and organizations as well.
    Some examples of its uses are as follows:
    - Sentiment Analysis: NLP can be used to analyze social media posts, news articles, and fan discussions to guage public sentiment towards teams, players and sporting events. This information can help teams and sports organizations understand public opinon and make informed decisions.
    - Player and Team Performance Analysis: NLP can be used to extract data from match reports and sports commentary, to help coaches gain a better understanding of their own performance or their opponents.
    - Injury Prediction and Prevention: NLP can be used to analyze injury reports and medical records to identify risk factors associated with injuries in order to take preventative action or develop injury recovery plans.
    - Sports Analytics: NLP can be used to extract data from player biographies and articles to structure advanced analytics, trend analysism and predictive modeling to gain deeper insights into player performance and game outcomes. This is the main use of NLP in sports.<br><br>

- ### Developments in Sports Analytics

    Over the last 5-10 years, NLP has seen significant progress in the field of sports analytics. One major trend is the use of machine learning to identify patterns and insights that would be impossible for humans to detect. An example of this would be missed calls by referees. Another trend is the development of more sophisticated NLP tools that can understand the nuances of human language, including language and context-specific terminology. Up to the minute journalism and reporting, down to even the last play or bat swing. Evaluating draft classes. Training and development techniques. Analyzing batting averages and determining what pitches cause a batter to strike out. These studies and collections of data are all executed through the use of NLP.
    <br><br>

- ### Other Major Companies in the Sports Analytics Domain

    Apart from ESPN, there area several other companies that have made significant contributions to the field of NLP sports analytics:
    - [Sportlogiq](https://www.sportlogiq.com/ "Sportlogiq's website") - The global leader in hockey analytics, which uses computer vision and machine learning to analyze player and team performance in real time.
    - [Second Spectrum](https://www.secondspectrum.com/ "Second Spectrum's website") - Official Tracking Provider for the NBA, Premier League, and MLS, using advanced NLP algorithms to generate insights on basketball games, including shot charts, player tracking and defensive analysis.
    - [Hudl](https://www.hudl.com/ "Hudl's website") - Video analysis for coaches and players. Over than 200K teams across 40 sports use Hudl to capture, analyze and learn from video and data.
    - [Hookit](https://hookit.com/ "Hookit's website") Hookit tracks athletes sponsorhips and social media mentions to determine sponsorship values and analyze marketing data.
    <br><br>

    Overall, the field of sports analytics is rapidly evolving, with new companies and technologies emerging every year.
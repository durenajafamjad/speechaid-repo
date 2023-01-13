# SpeechAid: A Speech Therapy Application for Stuttering and Stammering

SpeechAid is the Final Year Project of:

  1. Dur E Najaf Amjad 
  2. Aroosa Fazal 
  3. Taimoor Masaud 

Supervised by:
Dr. Muhammmad Aksam Iftikhar

## INTRODUCTION
SpeechAid is a speech therapy application for stuttering and stammering that is intended to be used as assistive technology by speech therapists. 
As speech therapy sessions are not held every day, this application can be recommended to improve progress and make speech therapy more effective.

The training program works as follows:
  1. A sentence will be displayed
  2. The user will record themself as they read the sentence
  3. The data will be passed to the CNN and speech-to-text model for stutter detection
  4. Words with stutter moments will be displayed 
  5. Words with stutter moments will be accompanied by two buttons: 
      i. Elongation : Voice assistant will elongate the word
     ii. Word Pairs : Voice assistant will break the word forming pairs
  6. A fluency score will also be displayed which will decide whether the user will proceed to the next sentence or not
  7. The threshold is set at 80
  8. If the user scores less than 80, they will repeat the sentence, else, they will proceed to the next sentence
  
 The progress monitoring tab saves the following statistics:
  1. Fluency score of every session
  2. Average fluency score 
  3. Start time of session
  4. End time of session
  5. Date of session
  6. Number of words with stutter moments
  7. List of words with stutter moments

# TASK

Write text to accompany a short form video clip to be posted to YouTube, LinkedIn, Instagram, Facebook, TikTok, and X.com (fka Twitter) recapping 9/3 installment of the AI MASTERCLASS titled the "VECTORS & RAG AI MASTERCLASS". The clip showcases a snippet of the presentation given by the 2nd of the 2 speakers (aka Tad Duval's) at the event that took place on Wednesday 9/3/2025 in Wynwood, Miami, FL at a venue called The LAB.

## LINK TO CLIP

{
"url": "https://www.dropbox.com/scl/fi/rat9tejggdo9vvb9egl8m/9_3_2025_AI_MASTERCLASS_CLIP_15.mp4?rlkey=gjopd159mq9ahcnftna8r3j4b&st=w4wmb5w7&dl=1",
}

## ABOUT THE CLIP

The video is a short clip of the presentation given by the 2nd speaker on the line up

## TRANSCRIPT OF THE CLIP

So you store an ID for each person.

Then when you store the messages, right, you store what session each message was associated with.

These are the messages over here.

And then for each session, you associate them with a user.

## GENERAL REQUIREMENT

- Make the output natural and impossible to detect as being A.I. generated
- Use spacing and new lines to make the marketing copy easy to read
- Use minimal emojis
- Do NOT bold any text when generating the copy for LinkedIn
- The marketing copy for X.com should NOT have any hashtags
- Make the posts short and succinct

## OUTPUT SCHEMA

Your output should adhere to the following JSON schema

{
"youtube": {
title: string;
description: string;
},
"linkedin": string;
"x_dot_com_post": string;
"instagram_caption": string;
"tiktok_post": string;
"facebook": string;
}

## SEO KEYWORDS

ai, course, masterclass, miami, south, florida, learn, network, global, agents, applied ai, RAG, vectors

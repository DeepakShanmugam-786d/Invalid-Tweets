# 🚀 Invalid Tweets

## 📌 Problem Description

We have a table called **Tweets** that stores messages posted on a social media app. The table looks like this:

| tweet_id | content                           |
|----------|-----------------------------------|
| 1        | Let us Code                       |
| 2        | More than fifteen chars are here! |

### 📊 What do the columns mean?
- **tweet_id**: A unique number assigned to each tweet.
- **content**: The actual message posted by the user.

🔍 **Important rule:** A tweet is **invalid** if it contains **more than 15 characters**.

---

## 🎯 Goal: Find Invalid Tweets
We need to **find the tweet_id of tweets that are longer than 15 characters**.

### ✅ Expected Output
Our output should look like this:

| tweet_id |
|----------|
| 2        |

### 🔍 Explanation:
- **Tweet 1**: "Let us Code" → **11 characters** ✅ (Valid)
- **Tweet 2**: "More than fifteen chars are here!" → **33 characters** ❌ (Invalid)

Since **tweet_id 2** is longer than 15 characters, we return it as the answer.

---

## 🔥 How to Solve
Here’s the game plan:

1️⃣ **Count the number of characters in each tweet.**  
2️⃣ **If the length is greater than 15, select the tweet_id.**  
3️⃣ **Return the results in any order.**

---

## 🏆 Why is this important?
- **Helps maintain tweet length limits** 📝
- **Prevents long spam messages** 🚫
- **Improves user experience** 🎯

🚀 Now you’re ready to write a query and filter out invalid tweets!


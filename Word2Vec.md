# 🚀 My First Walk Into AI & Word Embeddings  

Let me start before I get overwhelmed by the mountain of research papers 📚 related to word embeddings. I haven’t read many papers yet, but I have certainly gone through the original **word2vec** paper, did some coding experiments 💻, and found some fascinating results — like how *“engineer”* and *“plumber”* ended up surprisingly close in one dataset.  

---

## ✨ The Beginning of My AI Journey  

Leaving everything else aside, this is my **first time**, my first walk into the long journey of AI.  
I’m determined to make this year a year filled with **learning more and more about AI**, writing ✍️ about it, and letting myself get excited 🤩 by it.  

God, I feel the urgent need for a printer 🖨️ — oh, I need that! I love messing up my room with printed papers that I can occasionally flip through and cite.  

---

## 🎯 My Motive  

My motive with this journey is to better unravel the world of emerging AI, especially by staying close to **transformers** 🤖.  
I’m heavily impressed by this technology. I sometimes find myself thinking deeply about it — and I want to think even deeper, get crazy 🤯 about it, stuff myself with more knowledge, and just write.  

I wish I could teach 🧑‍🏫, but for now, it’s just writing. Hopefully, someday someone will notice my work, or maybe I’ll land onto something meaningful through these efforts.  

---

## 🔑 Why Start With Word Embeddings?  

Word Embeddings — let’s get straight into the work and be less poetic about my love for AI ❤️.  

I had spent some time thinking about the best topic to kick off this chain of articles, and I couldn’t find a better candidate than **word embeddings**.  

---

## 🌏 Words, Meanings, and Context  

I don’t understand Chinese 🇨🇳, but over a billion and a half people do. If you were to remove language for even a second, the whole country would be thrown into confusion 😵.  

We use words — which are just random symbols 🔤 pronounced in certain ways — and they carry meanings depending on the context. But this is not how computers communicate.  

Computers 💻 communicate purely through **numbers**, which usually represent one fixed thing: either **on** (1) or **off** (0).  

So, in order for computers to talk to us — to understand our language — they need to work with words, even though all they inherently understand are numbers.  

---

## ⚡ The Tricky Part  

Here’s where it gets tricky 🌀:  
A word **cannot** be represented by a fixed number.  

👉 For example, the word *bank* in one context could mean a place to store money 💰, and in another, it could mean the side of a river 🌊.  

This leads to the realization that **meaning depends on context**, and if we were to assign numbers to words, those numbers would need to change based on the context.  

💡 **First key realization:** There is no universal way to assign a word a fixed number.  

---

## 🧩 The Solution: Word Embeddings  

Alright, if it’s not a fixed number, maybe it can be some dynamically changing number — but how do we assign a number (or set of numbers) to a word in a way that reflects its meaning?  

👉 The solution to this problem is **word embeddings**.  

Think of it as a wide **vector space** 🪐, where each direction captures some underlying dimension — maybe gender, beauty, wealth, or anything else.  

Each word gets represented by a **high-dimensional vector**, with values along these various directions reflecting aspects of its meaning.  

✨ For example, the word *king* might carry weight along the “royalty” 👑 dimension, the “power” ⚔️ dimension, and the “male” 🚹 dimension.  

---

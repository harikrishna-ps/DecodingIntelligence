---
theme: seriph
background: https://images.pexels.com/photos/8386434/pexels-photo-8386434.jpeg?auto=compress&cs=tinysrgb&w=1920&h=1080
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Decoding Intelligence: A Journey into AI and Machine Learning
drawings:
  persist: false
css: unocss
contextMenu: false
---

# Decoding Intelligence
## A Journey into AI and Machine Learning

<div class="pt-6">
  <p class="text-lg opacity-80"></p>
</div>

<div class="pt-8">
  <p class="text-base opacity-60">
    Presented by: 
    <span class="relative group cursor-pointer text-base opacity-80 font-semibold">
      Harikrishna P S
      <span class="hidden group-hover:flex group-focus:flex absolute left-1/2 -translate-x-1/2 mt-2 z-10 flex-col items-start bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 rounded-lg shadow-lg p-4 min-w-[220px] text-left text-base opacity-100 transition-all">
        <div class="mb-2"><span class="font-semibold">LinkedIn:</span> <a href="https://www.linkedin.com/in/harikrishna-ps/" target="_blank" class="text-blue-600 underline">harikrishna-ps</a></div>
        <div class="mb-2"><span class="font-semibold">Email:</span> <a href="mailto:harikrishnapspknl@gmail.com" class="text-blue-600 underline">harikrishnapspknl@gmail.com</a></div>
        <div><span class="font-semibold">WhatsApp:</span> <span class="text-blue-600">+918921888155</span></div>
      </span>
    </span>
  </p>
</div>

<!--
<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
</div>
-->

---
layout: default
---

# What is Artificial Intelligence (AI)?

<div class="grid grid-cols-2 gap-6 mt-6">
<div>

## Definition
<div class="text-base leading-relaxed">
AI refers to machines that can <span class="text-blue-400 font-semibold">simulate human intelligence</span>

### Key Capabilities:
- 🧠 **Learning** from experience
- 🤔 **Reasoning** through problems  
- 🔍 **Problem-solving** autonomously
- 💬 **Understanding** natural language
</div>

</div>
<div>

## Real-World Examples

<div class="space-y-3">
<div class="bg-blue-50 dark:bg-blue-900/20 p-3 rounded-lg">
  <h4 class="font-semibold text-blue-600 dark:text-blue-400 text-sm">Virtual Assistants</h4>
  <p class="text-xs opacity-80">Siri, Alexa, Google Assistant</p>
</div>

<div class="bg-green-50 dark:bg-green-900/20 p-3 rounded-lg">
  <h4 class="font-semibold text-green-600 dark:text-green-400 text-sm">Recommendation Engines</h4>
  <p class="text-xs opacity-80">Netflix, Spotify, Amazon</p>
</div>

<div class="bg-purple-50 dark:bg-purple-900/20 p-3 rounded-lg">
  <h4 class="font-semibold text-purple-600 dark:text-purple-400 text-sm">Smart Systems</h4>
  <p class="text-xs opacity-80">Navigation, Translation, Recognition</p>
</div>
</div>

</div>
</div>

---
layout: default
---

# What is Machine Learning (ML)?

<div class="grid grid-cols-2 gap-8 mt-6">
<div>

## Core Concept
<div class="text-base leading-relaxed mb-4">
ML is a <span class="text-green-400 font-semibold">subset of AI</span> where machines learn patterns from data
</div>

### Key Characteristics:
- 📊 **Data-Driven** learning process
- 🔄 **Automatic improvement** through experience
- 🎯 **Pattern recognition** capabilities
- 📈 **Performance optimization** over time

</div>
<div>

## Practical Applications

<div class="space-y-3">
<div class="flex items-center space-x-3 p-2 bg-gray-50 dark:bg-gray-800 rounded-lg">
  <div class="w-2 h-2 bg-red-400 rounded-full"></div>
  <div>
    <p class="font-medium text-sm">Email Spam Detection</p>
    <p class="text-xs opacity-70">Automatically filters unwanted emails</p>
  </div>
</div>

<div class="flex items-center space-x-3 p-2 bg-gray-50 dark:bg-gray-800 rounded-lg">
  <div class="w-2 h-2 bg-blue-400 rounded-full"></div>
  <div>
    <p class="font-medium text-sm">Voice Recognition</p>
    <p class="text-xs opacity-70">Converts speech to text accurately</p>
  </div>
</div>

<div class="flex items-center space-x-3 p-2 bg-gray-50 dark:bg-gray-800 rounded-lg">
  <div class="w-2 h-2 bg-green-400 rounded-full"></div>
  <div>
    <p class="font-medium text-sm">Fraud Detection</p>
    <p class="text-xs opacity-70">Identifies suspicious transactions</p>
  </div>
</div>
</div>

</div>
</div>

---
layout: two-cols
class: pt-2 pb-32
---

# Traditional Programming vs Machine Learning

<div class="flex flex-row gap-12 mt-4">
  <div class="flex-1">
    <h2 class="text-xl font-bold mb-4 text-center">Traditional Programming</h2>
    <div class="bg-blue-50 dark:bg-blue-900/20 p-6 rounded-lg">
      <div class="text-center">
        <div class="flex justify-center items-center space-x-6 mb-6">
          <div class="bg-blue-200 dark:bg-blue-700 px-4 py-2 rounded text-base">Rules</div>
          <div class="text-2xl">+</div>
          <div class="bg-green-200 dark:bg-green-700 px-4 py-2 rounded text-base">Data</div>
          <div class="text-2xl">=</div>
          <div class="bg-purple-200 dark:bg-purple-700 px-4 py-2 rounded text-base">Output</div>
        </div>
        <p class="text-base opacity-80 italic">You provide the logic</p>
      </div>
    </div>
    <div class="bg-gray-100 dark:bg-gray-800 p-4 rounded text-base mt-6">
      <strong>Example:</strong><br/>
      Tax calculation with predefined rules:<br/>
      • Income < $50,000 → 10% tax<br/>
      • Income ≥ $50,000 → 20% tax
    </div>
  </div>
  <div class="flex-1">
    <h2 class="text-xl font-bold mb-4 text-center">Machine Learning</h2>
    <div class="bg-green-50 dark:bg-green-900/20 p-6 rounded-lg">
      <div class="text-center">
        <div class="flex justify-center items-center space-x-6 mb-6">
          <div class="bg-green-200 dark:bg-green-700 px-4 py-2 rounded text-base">Data</div>
          <div class="text-2xl">+</div>
          <div class="bg-purple-200 dark:bg-purple-700 px-4 py-2 rounded text-base">Output</div>
          <div class="text-2xl">=</div>
          <div class="bg-blue-200 dark:bg-blue-700 px-4 py-2 rounded text-base">Rules</div>
        </div>
        <p class="text-base opacity-80 italic">Machine learns the logic</p>
      </div>
    </div>
    <div class="bg-gray-100 dark:bg-gray-800 p-4 rounded text-base mt-6">
      <strong>Example:</strong><br/>
      ML learns patterns from examples:<br/>
      • Train on thousands of tax examples<br/>
      • Model discovers complex patterns<br/>
      • Predicts tax for new cases
    </div>
  </div>
</div>

---
layout: center
class: text-center
---

# Evolution of AI
<div class="text-base opacity-80 mb-6">From Rules to Superintelligence</div>

<div class="flex justify-between items-center mb-12 px-16 gap-12">
  <div class="flex flex-col items-center w-1/6">
    <div class="bg-red-400 rounded-full w-16 h-16 flex items-center justify-center text-white text-3xl mb-4">🧩</div>
    <div class="font-semibold text-red-400 text-base">Rule-Based</div>
    <div class="text-sm opacity-70">1950s–1980s</div>
  </div>
  <div class="flex flex-col items-center w-1/6">
    <div class="bg-blue-400 rounded-full w-16 h-16 flex items-center justify-center text-white text-3xl mb-4">📊</div>
    <div class="font-semibold text-blue-400 text-base">Classical ML</div>
    <div class="text-sm opacity-70">1990s–2000s</div>
  </div>
  <div class="flex flex-col items-center w-1/6">
    <div class="bg-green-400 rounded-full w-16 h-16 flex items-center justify-center text-white text-3xl mb-4">🧠</div>
    <div class="font-semibold text-green-400 text-base">Deep Learning</div>
    <div class="text-sm opacity-70">2010s</div>
  </div>
  <div class="flex flex-col items-center w-1/6">
    <div class="bg-purple-400 rounded-full w-16 h-16 flex items-center justify-center text-white text-3xl mb-4">🎨</div>
    <div class="font-semibold text-purple-400 text-base">Generative AI</div>
    <div class="text-sm opacity-70">2020s</div>
  </div>
  <div class="flex flex-col items-center w-1/6">
    <div class="bg-yellow-400 rounded-full w-16 h-16 flex items-center justify-center text-white text-3xl mb-4">🤖</div>
    <div class="font-semibold text-yellow-400 text-base">Agentic AI</div>
    <div class="text-sm opacity-70">Present</div>
  </div>
  <div class="flex flex-col items-center w-1/6">
    <div class="bg-gray-400 rounded-full w-16 h-16 flex items-center justify-center text-white text-3xl mb-4">🚀</div>
    <div class="font-semibold text-gray-400 text-base">Superintelligence</div>
    <div class="text-sm opacity-70">Future</div>
  </div>
</div>

---
layout: default
---

# Rule-Based Systems
<div class="text-base opacity-80 mb-6">The Foundation of Early AI</div>

<div class="grid grid-cols-2 gap-6">
<div>

## How They Work
- Use **IF-THEN** logic statements
- Predetermined rules and conditions
- Direct programming of decision trees
- Expert knowledge encoded manually

## Examples in Action
<div class="space-y-2 mt-3">
<div class="bg-blue-50 dark:bg-blue-900/20 p-2 rounded text-sm">
  🌡️ **Basic Thermostats**: IF temp > 75°F THEN turn on AC
</div>
<div class="bg-green-50 dark:bg-green-900/20 p-2 rounded text-sm">
  📧 **Simple Spam Filters**: IF contains "FREE MONEY" THEN mark as spam
</div>
</div>

</div>
<div>

## Simple Logic Example
<div class="bg-gray-100 dark:bg-gray-800 p-3 rounded text-xs mt-3">
Basic spam filter logic:<br/>
• Check for keywords: "free", "winner", "urgent"<br/>
• If any keyword found → Mark as SPAM<br/>
• Otherwise → Mark as NOT SPAM
</div>
<p></p>

## Limitations
- ❌ Cannot adapt to new situations
- ❌ Requires manual rule updates  
- ❌ Difficult to handle complexity

</div>
</div>

---
layout: default
---

# Machine Learning Era
<div class="text-base opacity-80 mb-6">Learning Patterns from Data</div>

<div class="grid grid-cols-2 gap-6">
<div>

## Key Characteristics
- **Learns patterns** from training data
- **Automatically improves** with more examples
- **Generalizes** to unseen situations
- **Adapts** without manual programming

## Popular Algorithms
<div class="space-y-2 mt-3 text-sm">
  <div class="flex items-center space-x-3 p-2 bg-blue-50 dark:bg-blue-900/20 rounded">
    <div class="w-2.5 h-2.5 bg-blue-400 rounded-full"></div>
    <div>
      <span class="font-semibold">Linear Regression</span> <span class="opacity-70">– Finds the best straight line to predict values (e.g., predicting house prices from size)</span>
    </div>
  </div>
  <div class="flex items-center space-x-3 p-2 bg-green-50 dark:bg-green-900/20 rounded">
    <div class="w-2.5 h-2.5 bg-green-400 rounded-full"></div>
    <div>
      <span class="font-semibold">Logistic Regression</span> <span class="opacity-70">– Helps decide between two options (e.g., will it rain: yes or no?)</span>
    </div>
  </div>
</div>

</div>
<div>

## Real Applications

### Email Classification Process
<div class="bg-gray-100 dark:bg-gray-800 p-3 rounded text-xs mt-3">
• Train on thousands of email examples<br/>
• Extract features from text automatically<br/>
• Learn patterns that distinguish spam<br/>
• Predict classification for new emails
</div>

### Other Applications
- 💳 **Fraud Detection**: Credit card transactions
- 🎵 **Music Recommendation**: Spotify, Apple Music  
- 📈 **Stock Prediction**: Market analysis
- 🚗 **Route Optimization**: GPS navigation

</div>
</div>

---
layout: default
---

# Types of Machine Learning
<div class="text-base opacity-80 mb-6">How Machines Learn from Data</div>

<div class="grid grid-cols-3 gap-6">
  <div class="bg-blue-50 dark:bg-blue-900/20 p-4 rounded-lg flex flex-col items-center">
    <h3 class="font-semibold text-blue-600 dark:text-blue-400 mb-2">Supervised Learning</h3>
    <p class="text-xs opacity-80 text-center">The model learns from examples with the correct answers provided.<br><span class="italic">(Like a student learning with an answer key)</span></p>
    <ul class="text-xs mt-2 list-disc list-inside opacity-80">
      <li>Spam detection</li>
      <li>House price prediction</li>
    </ul>
  </div>
  <div class="bg-green-50 dark:bg-green-900/20 p-4 rounded-lg flex flex-col items-center">
    <h3 class="font-semibold text-green-600 dark:text-green-400 mb-2">Unsupervised Learning</h3>
    <p class="text-xs opacity-80 text-center">The model finds patterns in data without any answers given.<br><span class="italic">(Like sorting photos by similarity)</span></p>
    <ul class="text-xs mt-2 list-disc list-inside opacity-80">
      <li>Customer segmentation</li>
      <li>Grouping news articles</li>
    </ul>
  </div>
  <div class="bg-yellow-50 dark:bg-yellow-900/20 p-4 rounded-lg flex flex-col items-center">
    <h3 class="font-semibold text-yellow-600 dark:text-yellow-400 mb-2">Reinforcement Learning</h3>
    <p class="text-xs opacity-80 text-center">The model learns by trial and error, getting rewards for good actions.<br><span class="italic">(Like training a pet with treats)</span></p>
    <ul class="text-xs mt-2 list-disc list-inside opacity-80">
      <li>Game playing (Chess, Go)</li>
      <li>Robotics</li>
    </ul>
  </div>
</div>

---
layout: default
---

# Deep Learning Revolution
<div class="text-base opacity-80 mb-4">Neural Networks Inspired by the Brain</div>

<div class="grid grid-cols-2 gap-4 text-sm">
<div>

## What Makes It Special
- <span class="font-semibold">Multi-layered neural networks</span> (hence "deep")
- <span class="font-semibold">Handles complex data</span> like images, audio, text
- <span class="font-semibold">Automatic feature extraction</span> from raw data
- <span class="font-semibold">Scales with big data</span> and computing power

## Neural Network Structure
<div class="mt-2 p-2 bg-gray-50 dark:bg-gray-800 rounded-lg">
  <div class="text-center">
    <div class="flex justify-center items-center space-x-6 mb-2">
      <div class="flex flex-col items-center">
        <div class="w-8 h-8 bg-blue-200 dark:bg-blue-700 rounded-full mb-1"></div>
        <div class="w-8 h-8 bg-blue-200 dark:bg-blue-700 rounded-full mb-1"></div>
        <div class="w-8 h-8 bg-blue-200 dark:bg-blue-700 rounded-full"></div>
        <p class="text-sm mt-1 font-semibold">Input</p>
      </div>
      <div class="text-2xl">→</div>
      <div class="flex flex-col items-center">
        <div class="w-6 h-6 bg-green-200 dark:bg-green-700 rounded-full mb-1"></div>
        <div class="w-6 h-6 bg-green-200 dark:bg-green-700 rounded-full mb-1"></div>
        <div class="w-6 h-6 bg-green-200 dark:bg-green-700 rounded-full mb-1"></div>
        <div class="w-6 h-6 bg-green-200 dark:bg-green-700 rounded-full"></div>
        <p class="text-sm mt-1 font-semibold">Hidden</p>
      </div>
      <div class="text-2xl">→</div>
      <div class="flex flex-col items-center">
        <div class="w-8 h-8 bg-purple-200 dark:bg-purple-700 rounded-full"></div>
        <p class="text-sm mt-1 font-semibold">Output</p>
      </div>
    </div>
  </div>
</div>

</div>
<div>

## Breakthrough Applications

<div class="space-y-2">
  <div class="bg-blue-50 dark:bg-blue-900/20 p-2 rounded-lg">
    <h4 class="font-semibold text-blue-600 dark:text-blue-400 mb-1 text-xs">👁️ Computer Vision</h4>
    <ul class="text-xs space-y-0.5 opacity-80">
      <li>• Facial recognition systems</li>
      <li>• Medical image analysis</li>
      <li>• Autonomous vehicle vision</li>
    </ul>
  </div>
  <div class="bg-green-50 dark:bg-green-900/20 p-2 rounded-lg">
    <h4 class="font-semibold text-green-600 dark:text-green-400 mb-1 text-xs">🎤 Speech Processing</h4>
    <ul class="text-xs space-y-0.5 opacity-80">
      <li>• Speech-to-text conversion</li>
      <li>• Voice assistants</li>
      <li>• Real-time translation</li>
    </ul>
  </div>
  <div class="bg-purple-50 dark:bg-purple-900/20 p-2 rounded-lg">
    <h4 class="font-semibold text-purple-600 dark:text-purple-400 mb-1 text-xs">📝 Natural Language</h4>
    <ul class="text-xs space-y-0.5 opacity-80">
      <li>• Language translation</li>
      <li>• Sentiment analysis</li>
      <li>• Text summarization</li>
    </ul>
  </div>
</div>

</div>
</div>

---
layout: default
---

# Generative AI Era
<div class="text-base opacity-80 mb-4">AI That Creates Original Content</div>

<div class="grid grid-cols-2 gap-4 text-sm">
<div>

## What is Generative AI?
AI systems that can <b>create new content</b> rather than just analyze existing data

### Key Capabilities:
- 🎨 <b>Generate images</b> from text descriptions
- ✍️ <b>Write articles</b> and stories
- 💻 <b>Create code</b> in multiple languages  
- 🎵 <b>Compose music</b> and audio
- 🎬 <b>Produce videos</b> and animations

</div>
<div>

## How It Works
<div class="mt-2 p-2 bg-gradient-to-r from-blue-50 to-purple-50 dark:from-blue-900/20 dark:to-purple-900/20 rounded-lg">
  <p class="text-xs leading-relaxed">
    Uses <b>Large Language Models</b> (LLMs) trained on massive datasets to understand patterns and generate human-like responses
  </p>
</div>

## Impact on Electronics
<ul class="text-xs mt-2 opacity-80 list-disc list-inside">
  <li>📱 <b>App development</b> automation</li>
  <li>🔧 <b>Circuit design</b> assistance</li>
  <li>📋 <b>Technical documentation</b> generation</li>
  <li>🧪 <b>Rapid prototyping</b> of ideas</li>
</ul>

</div>
</div>
---
layout: default
---

# Generative AI: Popular Examples
<div class="text-base opacity-80 mb-4">Famous Tools and Platforms</div>

<div class="grid grid-cols-2 gap-4 text-sm">
  <div class="space-y-2">
    <div class="bg-green-50 dark:bg-green-900/20 p-2 rounded-lg">
      <h4 class="font-semibold text-green-600 dark:text-green-400 mb-1 text-xs">💬 ChatGPT</h4>
      <p class="text-xs opacity-80">Conversational AI for text generation, coding help, and problem-solving</p>
    </div>
    <div class="bg-blue-50 dark:bg-blue-900/20 p-2 rounded-lg">
      <h4 class="font-semibold text-blue-600 dark:text-blue-400 mb-1 text-xs">🎨 DALL-E & Midjourney</h4>
      <p class="text-xs opacity-80">Create stunning images from text descriptions</p>
    </div>
    <div class="bg-orange-50 dark:bg-orange-900/20 p-2 rounded-lg">
      <h4 class="font-semibold text-orange-600 dark:text-orange-400 mb-1 text-xs">🤖 Anthropic Claude</h4>
      <p class="text-xs opacity-80">Advanced conversational AI focused on safety and helpfulness</p>
    </div>
  </div>
  <div class="space-y-2">
    <div class="bg-purple-50 dark:bg-purple-900/20 p-2 rounded-lg">
      <h4 class="font-semibold text-purple-600 dark:text-purple-400 mb-1 text-xs">👨‍💻 GitHub Copilot</h4>
      <p class="text-xs opacity-80">AI pair programmer that suggests code as you type</p>
    </div>
    <div class="bg-cyan-50 dark:bg-cyan-900/20 p-2 rounded-lg">
      <h4 class="font-semibold text-cyan-600 dark:text-cyan-400 mb-1 text-xs">🔎 Perplexity AI</h4>
      <p class="text-xs opacity-80">AI-powered search and question answering assistant</p>
    </div>
    <div class="bg-gray-50 dark:bg-green-900/20 p-2 rounded-lg">
      <h4 class="font-semibold text-blue-600 dark:text-blue-400 mb-1 text-xs">🧠 DeepSeek</h4>
      <p class="text-xs opacity-80">Open-source large language model for research and applications</p>
    </div>
  </div>
</div>

---
layout: default
---

# Agentic AI
<div class="text-base opacity-80 mb-4">Goal-Driven Autonomous Systems</div>

<div class="grid grid-cols-2 gap-4 text-sm">
<div>

### What Makes It Special
AI that can <b>act autonomously</b> to achieve specific goals

### Key Characteristics:
- 🎯 <b>Goal-oriented</b> behavior
- 🤖 <b>Autonomous decision-making</b>
- 🔄 <b>Multi-step task execution</b>
- 🧠 <b>Reasoning and planning</b>
- 🌐 <b>Interaction with external systems</b>
<p></p>

### How It Differs

<table class="w-full text-xs mt-2">
  <thead>
    <tr>
      <th class="bg-gray-100 dark:bg-gray-800 p-2 text-left font-semibold text-red-600 dark:text-red-400">Traditional AI</th>
      <th class="bg-gray-100 dark:bg-gray-800 p-2 text-left font-semibold text-green-600 dark:text-green-400">Agentic AI</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="bg-white dark:bg-gray-900 p-2">Responds to prompts, Needs human input for every step</td>
      <td class="bg-white dark:bg-gray-900 p-2">Takes initiative and acts independently, Plans and adapts to new situations</td>
    </tr>
  </tbody>
</table>

</div>
<div>

## Real-World Applications
<div class="space-y-1 mt-2">
  <div class="bg-blue-50 dark:bg-blue-900/20 p-2 rounded-lg">
    <h4 class="font-semibold text-blue-600 dark:text-blue-400 mb-1 text-xs">🤖 Personal AI Assistants</h4>
    <ul class="text-xs space-y-0.5 opacity-80">
      <li>Schedule meetings automatically</li>
      <li>Book travel arrangements</li>
      <li>Manage email responses</li>
    </ul>
  </div>
  <div class="bg-green-50 dark:bg-green-900/20 p-2 rounded-lg">
    <h4 class="font-semibold text-green-600 dark:text-green-400 mb-1 text-xs">🚗 Autonomous Vehicles</h4>
    <ul class="text-xs space-y-0.5 opacity-80">
      <li>Navigate complex traffic</li>
      <li>Make split-second decisions</li>
      <li>Adapt to road conditions</li>
    </ul>
  </div>
  
</div>

</div>
</div>

---
layout: default
---

# Superintelligence (Future Stage)
<div class="text-base opacity-80 mb-4">The Hypothetical Next Frontier</div>

<div class="grid grid-cols-2 gap-4 text-sm">
<div>

## Definition
Hypothetical AI that <b>surpasses human intelligence</b> in all domains

### Potential Capabilities:
- 🚀 <b>Space exploration</b> and colonization, including autonomous missions and interstellar travel
- 💡 <b>Innovation beyond</b> human imagination—creating new technologies, art, and ideas
- 🏥 <b>Transforming healthcare</b> with personalized medicine, early diagnosis, and robotic surgery
- 🛡️ <b>Advanced security</b> and risk prediction to prevent disasters and conflicts
- 🤝 <b>Enhancing human potential</b> through brain-computer interfaces and cognitive augmentation


</div>
<div>

## Critical Questions
<div class="space-y-1">
  <div class="bg-red-50 dark:bg-red-900/20 p-1 rounded-lg border-l-2 border-red-400 text-xs">
    <h4 class="font-semibold text-red-600 dark:text-red-400 mb-0.5 text-xs">⚠️ Control Problem</h4>
    <p class="text-xs opacity-80">How do we ensure superintelligent AI remains aligned with human values and under human control?</p>
  </div>
  <div class="bg-yellow-50 dark:bg-yellow-900/20 p-1 rounded-lg border-l-2 border-yellow-400 text-xs">
    <h4 class="font-semibold text-yellow-600 dark:text-yellow-400 mb-0.5 text-xs">🎯 Alignment Problem</h4>
    <p class="text-xs opacity-80">How do we specify what we want AI to do in a way that doesn't lead to unintended consequences?</p>
  </div>
  <div class="bg-blue-50 dark:bg-blue-900/20 p-1 rounded-lg border-l-2 border-blue-400 text-xs">
    <h4 class="font-semibold text-blue-600 dark:text-blue-400 mb-0.5 text-xs">⚖️ Responsibility</h4>
    <p class="text-xs opacity-80">Who is responsible for the decisions and actions of superintelligent systems?</p>
  </div>
</div>

</div>
</div>

---
layout: default
---

# Applications in Electronics
<div class="text-base opacity-90 mb-4 text-sm">AI Transforming Electronic Systems</div>

<div class="grid grid-cols-2 gap-4 text-sm">
  <div>
    <div class="bg-blue-50 dark:bg-blue-900/20 p-2 rounded mb-2">
      <b>📺 Smart TVs</b><br>Content recommendation, voice control, auto optimization
    </div>
    <div class="bg-green-50 dark:bg-green-900/20 p-2 rounded mb-2">
      <b>❄️ Smart Fridges</b><br>Food management, energy saving, shopping lists
    </div>
    <div class="bg-purple-50 dark:bg-purple-900/20 p-2 rounded mb-2">
      <b>🏠 Home Automation</b><br>Learning patterns, predictive control, energy savings
    </div>
    <div class="bg-orange-50 dark:bg-orange-900/20 p-2 rounded mb-2">
      <b>⚡ Smart Circuits</b><br>Adaptive power management, self-healing, fault detection
    </div>
    <div class="bg-cyan-50 dark:bg-cyan-900/20 p-2 rounded mb-2">
      <b>🌐 IoT Devices</b><br>Remote monitoring, smart sensors, real-time alerts
    </div>
  </div>
  <div>
    <div class="bg-red-50 dark:bg-red-900/20 p-2 rounded mb-2">
      <b>⌚ Smartwatches</b><br>Health monitoring, activity prediction, coaching
    </div>
    <div class="bg-yellow-50 dark:bg-yellow-900/20 p-2 rounded mb-2">
      <b>🏃‍♂️ Fitness Trackers</b><br>Sleep analysis, workout tips, health insights
    </div>
    <div class="bg-indigo-50 dark:bg-indigo-900/20 p-2 rounded mb-2">
      <b>🏭 Predictive Maintenance</b><br>Monitor equipment health, reduce downtime, optimize maintenance
    </div>
    <div class="bg-teal-50 dark:bg-teal-900/20 p-2 rounded mb-2">
      <b>🚗 Smart Vehicles</b><br>Autonomous driving, collision avoidance, driver assistance, smart navigation
    </div>
  </div>
</div>
---
layout: default
---

# Emerging Trends: AI + Electronics
<div class="text-base opacity-80 mb-6">The Future is Connected and Intelligent</div>

<div class="grid grid-cols-2 gap-6">
<div>

## AI + IoT Integration
<div class="bg-gradient-to-r from-blue-50 to-green-50 dark:from-blue-900/20 dark:to-green-900/20 p-4 rounded-lg mb-4">
  <h3 class="font-semibold text-base mb-2">🌐 Smart Interconnected Devices</h3>
  <ul class="space-y-1 text-xs">
    <li class="flex items-center"><span class="w-1 h-1 bg-blue-400 rounded-full mr-2"></span>Devices that learn from each other</li>
    <li class="flex items-center"><span class="w-1 h-1 bg-green-400 rounded-full mr-2"></span>Collective intelligence networks</li>
    <li class="flex items-center"><span class="w-1 h-1 bg-purple-400 rounded-full mr-2"></span>Seamless automation ecosystems</li>
  </ul>
</div>

## Edge AI Revolution
<div class="bg-purple-50 dark:bg-purple-900/20 p-3 rounded-lg">
  <h4 class="font-semibold text-purple-600 dark:text-purple-400 mb-2 text-sm">🔄 AI On-Device Processing</h4>
  <div class="space-y-1 text-xs">
    <p><span class="font-medium">✅ Benefits:</span> Reduced latency, privacy protection, offline capability</p>
    <p><span class="font-medium">📱 Applications:</span> Smart cameras, voice assistants, autonomous vehicles</p>
  </div>
</div>

</div>
<div>

### Specialized AI Hardware

<div class="space-y-3">
<div class="bg-red-50 dark:bg-red-900/20 p-3 rounded-md">
  <h4 class="font-semibold text-red-600 dark:text-red-400 mb-1 text-sm">🎮 NVIDIA GPUs</h4>
  <ul class="text-xs space-y-1 opacity-80">
    <li>• RTX series for AI workloads</li>
    <li>• CUDA parallel processing</li>
    <li>• Data center solutions (A100, H100)</li>
  </ul>
</div>

<div class="bg-blue-50 dark:bg-blue-900/20 p-3 rounded-md">
  <h4 class="font-semibold text-blue-600 dark:text-blue-400 mb-1 text-sm">🧠 Google TPU</h4>
  <ul class="text-xs space-y-1 opacity-80">
    <li>• Tensor Processing Units</li>
    <li>• Optimized for machine learning</li>
  </ul>
</div>

<div class="bg-green-50 dark:bg-green-900/20 p-3 rounded-md">
  <h4 class="font-semibold text-green-600 dark:text-green-400 mb-1 text-sm">🍎 Apple Neural Engine</h4>
  <ul class="text-xs space-y-1 opacity-80">
    <li>• Built into M-series chips</li>
    <li>• Privacy-focused processing</li>
  </ul>
</div>
</div>

</div>
</div>

---
layout: default
---

# Ethics and Privacy in AI
<div class="text-lg opacity-90 mb-6">Critical Considerations for Responsible AI</div>

<div class="grid grid-cols-3 gap-4 text-sm mb-6">
  <div class="bg-red-50 dark:bg-red-900/20 p-4 rounded border-l-4 border-red-400">
    <b>🕵️ Data Collection</b>
    <ul class="mt-2 opacity-90">
      <li>Personal data harvesting</li>
      <li>Facial recognition</li>
      <li>Location tracking</li>
    </ul>
  </div>
  <div class="bg-yellow-50 dark:bg-yellow-900/20 p-4 rounded border-l-4 border-yellow-400">
    <b>⚖️ Bias in AI</b>
    <ul class="mt-2 opacity-90">
      <li>Discriminatory hiring</li>
      <li>Biased loan approvals</li>
      <li>Unfair justice predictions</li>
    </ul>
  </div>
  <div class="bg-purple-50 dark:bg-purple-900/20 p-4 rounded border-l-4 border-purple-400">
    <b>🎭 Misuse of Content</b>
    <ul class="mt-2 opacity-90">
      <li>Deepfakes, misinformation</li>
      <li>Academic dishonesty</li>
      <li>Impersonation, fraud</li>
    </ul>
  </div>
</div>

<div class="grid grid-cols-2 gap-4 text-sm">
  <div>
    <b>Key Questions to Consider</b>
    <div class="bg-blue-50 dark:bg-blue-900/20 p-4 rounded mb-3">
      <b>🤔 Responsibility & Accountability</b>
      <ul class="mt-2 opacity-90">
        <li>Who's responsible for AI mistakes?</li>
        <li>How to ensure explainable AI?</li>
        <li>What if AI systems conflict?</li>
      </ul>
    </div>
  
  </div>
  <div>
    <b>Regulatory Landscape</b>
    <div class="bg-gray-50 dark:bg-gray-800 p-4 rounded">
      <ul class="opacity-90">
        <li><b>EU AI Act:</b> Comprehensive regulation</li>
        <li><b>US Executive Order:</b> AI safety & security</li>
        <li><b>Global:</b> IEEE, ISO AI guidelines</li>
      </ul>
    </div>
  </div>
</div>
---
layout: default
---

# Summary & Key Takeaways
<div class="text-base opacity-90 mb-4">AI: Key Learnings & Career Opportunities</div>

<div class="grid grid-cols-3 gap-4 text-sm mb-6">
  <div>
    <div class="bg-gradient-to-r from-blue-50 to-purple-50 dark:from-blue-900/20 dark:to-purple-900/20 p-3 rounded mb-3">
      <b>🔄 AI's Impact</b>
      <ul class="mt-2 opacity-80">
        <li>Smart systems in daily life</li>
        <li>Electronics that learn & adapt</li>
        <li>Automation & efficiency</li>
      </ul>
    </div>
    <div class="bg-gradient-to-r from-green-50 to-teal-50 dark:from-green-900/20 dark:to-teal-900/20 p-3 rounded mb-3">
      <b>📈 Evolution Stages</b>
      <ul class="mt-2 opacity-80">
        <li>Rule-based → ML → Deep Learning</li>
        <li>Generative AI → Agentic AI</li>
        <li>Superintelligence (future)</li>
      </ul>
    </div>
    <div class="bg-gradient-to-r from-yellow-50 to-orange-50 dark:from-yellow-900/20 dark:to-orange-900/20 p-3 rounded">
      <b>⚖️ Ethics Matter</b>
      <ul class="mt-2 opacity-80">
        <li>Privacy & bias awareness</li>
        <li>Responsible development</li>
      </ul>
    </div>
  </div>
  <div class="col-span-2">
    <b class="text-lg block mb-2">Career Opportunities</b>
    <div class="grid grid-cols-2 gap-2">
      <div class="bg-blue-50 dark:bg-blue-900/20 p-2 rounded"><b>🤖 AI Hardware Engineer</b><br><span class="opacity-70">Design AI chips & processors</span></div>
      <div class="bg-green-50 dark:bg-green-900/20 p-2 rounded"><b>🌐 IoT Solutions Architect</b><br><span class="opacity-70">Build smart device ecosystems</span></div>
      <div class="bg-purple-50 dark:bg-purple-900/20 p-2 rounded"><b>⚡ Edge AI Developer</b><br><span class="opacity-70">Optimize AI for devices</span></div>
      <div class="bg-yellow-50 dark:bg-yellow-900/20 p-2 rounded"><b>🧠 Smart Systems Designer</b><br><span class="opacity-70">Create automation solutions</span></div>
      <div class="bg-cyan-50 dark:bg-cyan-900/20 p-2 rounded"><b>📊 ML Engineer</b><br><span class="opacity-70">Develop & deploy ML models</span></div>
      <div class="bg-red-50 dark:bg-red-900/20 p-2 rounded"><b>🧑‍💻 AI Engineer</b><br><span class="opacity-70">Build & integrate AI systems</span></div>
      <div class="bg-teal-50 dark:bg-teal-900/20 p-2 rounded"><b>🔬 Data Scientist</b><br><span class="opacity-70">Analyze & interpret data</span></div>
      <div class="bg-gray-50 dark:bg-gray-800 p-2 rounded"><b>🛡️ AI Ethics Specialist</b><br><span class="opacity-70">Ensure responsible AI use</span></div>
      <div class="bg-pink-50 dark:bg-pink-900/20 p-2 rounded"><b>💡 Prompt Engineer</b><br><span class="opacity-70">Design and optimize prompts for AI models</span></div>
    </div>
  </div>
</div>

---
layout: default
---

# Free Resources & Tools for Your AI Journey
<div class="text-base opacity-90 mb-4">Kickstart Your Learning and Projects with These Platforms</div>

<div class="grid grid-cols-2 gap-6 text-sm">
  <div>
    <b>🎓 Free Learning Platforms</b>
    <ul class="list-disc list-inside mt-2 opacity-90">
      <li><a href="https://cognitiveclass.ai" target="_blank" class="text-blue-600 underline">CognitiveClass.ai</a> – Free AI & Data Science courses</li>
      <li><a href="https://kaggle.com" target="_blank" class="text-blue-600 underline">Kaggle.com</a> – Datasets, competitions, and notebooks</li>
      <li><a href="https://www.coursera.org" target="_blank" class="text-blue-600 underline">Coursera</a> – Free access to top university courses</li>
    </ul>
    <b class="block mt-6">☁️ Free Cloud Services</b>
    <ul class="list-disc list-inside mt-2 opacity-90">
      <li><a href="https://azure.microsoft.com/free" target="_blank" class="text-blue-600 underline">Azure Free Tier</a> – Free cloud credits & services</li>
      <li><a href="https://cloud.google.com/free" target="_blank" class="text-blue-600 underline">Google Cloud Free Tier</a> – Free credits & always-free products</li>
      <li><a href="https://aws.amazon.com/free/" target="_blank" class="text-blue-600 underline">AWS Free Tier</a> – Free cloud resources</li>
    </ul>
  </div>
  <div>
    <b>🛠️ Real AI Tools & Sandboxes</b>
    <ul class="list-disc list-inside mt-2 opacity-90">
      <li><a href="https://bolt.new" target="_blank" class="text-blue-600 underline">Bolt.new</a> – Create stunning apps & websites by chatting with AI. </li>
      <li><a href="https://lovable.dev" target="_blank" class="text-blue-600 underline">Lovable.dev</a> – AI-powered code and content tools</li>
      <li><a href="https://colab.research.google.com" target="_blank" class="text-blue-600 underline">Google Colab</a> – Free Jupyter notebooks in the cloud</li>
      <li><a href="https://huggingface.co/spaces" target="_blank" class="text-blue-600 underline">Hugging Face Spaces</a> – Community AI demos and apps</li>
      <li><a href="https://platform.openai.com/playground" target="_blank" class="text-blue-600 underline">OpenAI Playground</a> – Experiment with language models</li>
    </ul>
  </div>
</div>

---
layout: center
class: text-center
---

# Questions & Discussion
<div class="text-xl opacity-80 mb-8">Let's Explore AI Together</div>

<div class="grid grid-cols-3 gap-6 mb-8">
<div class="bg-blue-50 dark:bg-blue-900/20 p-4 rounded-lg">
  <div class="text-3xl mb-3">🤔</div>
  <h3 class="font-semibold mb-1 text-sm">Ask Questions</h3>
  <p class="text-xs opacity-80">Curious about any AI concept?</p>
</div>

<div class="bg-green-50 dark:bg-green-900/20 p-4 rounded-lg">
  <div class="text-3xl mb-3">💡</div>
  <h3 class="font-semibold mb-1 text-sm">Share Ideas</h3>
  <p class="text-xs opacity-80">What AI applications excite you?</p>
</div>

<div class="bg-purple-50 dark:bg-purple-900/20 p-4 rounded-lg">
  <div class="text-3xl mb-3">🚀</div>
  <h3 class="font-semibold mb-1 text-sm">Discuss Future</h3>
  <p class="text-xs opacity-80">Where do you see AI heading?</p>
</div>
</div>

<div class="text-base opacity-70">
Thank you for joining this journey into AI and Machine Learning!
</div>

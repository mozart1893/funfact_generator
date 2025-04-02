# Daily Fun Fact Generator

Get 6 random fun facts daily across various topics using DeepSeek's AI!

## Features
- 6 fresh facts per run
- Covers AI, Tech, Politics, Sports, Health, and Entertainment
- Terminal-based display
- Easy API key configuration

## Setup

### Prerequisites
- Python 3.8+
- DeepSeek API account

### Installation
1. Clone repo:
   ```bash
   git clone https://github.com/yourusername/funfact-generator.git
   cd funfact-generator
   ```

2. Install dependencies:
   ```bash
   pip3 install -r requirements.txt
   ```

3. Configure API key:
   - Create `.env` file
   - Add your DeepSeek API key:
     ```plaintext
     DEEPSEEK_API_KEY=your_actual_key_here
     ```

## Usage
Run the generator:
```bash
python3 fact_generator.py
```

Sample output:
```
📚 Today's 6 Random Fun Facts:

1. 🤖 Artificial Intelligence: AI can now detect Parkinson's disease from breathing patterns with 86% accuracy using radio signals.
2. 🚀 Emerging Technology: Scientists are developing "quantum batteries" that could charge electric cars in 3 minutes.
3. 🌍 World Politics: Finland's parliament has the youngest female prime minister in history - she took office at 34.
4. ⚽ Sports: The fastest tennis serve ever recorded was 163.7 mph - faster than a cheetah's top speed!
5. 💪 Health and Wellness: Laughing 100 times burns as many calories as 15 minutes on an exercise bike.
6. 🎬 Entertainment: The "Wilhelm Scream" has been used in over 400 movies since 1951 - listen for it in action scenes!

🌟 Learn something new every day!
```

## Troubleshooting
- **API Errors**: Verify your API key and account status
- **Connection Issues**: Check internet connectivity
- **Formatting Problems**: Ensure you're using the latest version

## License
MIT License
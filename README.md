# city-temperature-agent
Agentic AI that fetches live city temperature using Gemini and tool calling
# City Temperature Agent

An agentic AI that answers "What is the temperature in <city>?" using live data.

## How it works
1. The user asks a question.
2. The LLM (Gemini) decides whether to call a tool.
3. The tool `get_temperature` fetches live data from the Open-Meteo API.
4. The result goes back to the LLM, which writes the final answer.

Loop: Think -> Act -> Observe -> Answer

## Tech
- Python, Google Colab
- Gemini API (google-genai)
- Open-Meteo weather API (free, no key)

## How to run
1. Open the notebook in Google Colab.
2. Get a free API key from Google AI Studio.
3. Run the cells in order and paste your key when prompted.
   Never put your key in the code.

## Evaluation
Tool-use accuracy on a small test set: XX% (replace with your result)

## Author
Hassan khan, Islamia collage peshawar

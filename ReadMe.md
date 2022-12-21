# Neural Machine Translation Using Seq-to-Seq Models
Considering a lot of immigration, International transactions and the ever-expanding Globalisation, language translation is an important
domain in businesses, tourism, IT industry, etc. People from various origins should have the comfort of using their native languages
across the globe. Although such a technology already exists, this is an improvement to it. The existing technology tokenises the given
text into phrases and performs a direct translation of the phrases to the required language. In NMT, the neural network finds the
context in which the sentence has been spoken and translates it to the target language accordingly. In this project, we will be translating
audio spoken in Spanish to English audio.

# Dataset
Datasets:
The following dataset will be used for the project:
Tab-delimited Bilingual Sentence Pairs - http://www.manythings.org/anki/ - This dataset contains sentences in different languages and its corresponding English translation. We are choosing to use the Spanish - English Dataset

# Methodology
Methodology and Implementation:
The project is divided into the following parts:
- Preprocessing text data.
- Vectorize the data.
- Create 3 different neural network model to perform NMT
- Train, Validate and Test the data three different models.
- To deploy, get Voice or Text data. If voice, convert to text.
- Feed the text to the better model to translate the text from spanish to english.
- The translated text is then converted back to speech.
Speech to Text: We will primarily be making use of the PyAudio & SpeechRecognition module in Python.

### Neural Machine Translation: 
We will be comparing variations of the Encoder-Decoder model. The model will translate Spanish text to English and vice versa. The Variations are, NMT without Attention, NMT using Seq2Seq Model, NMT using Transformer Model.
### Evaluation Metrics: 
Accuracy, Precision, Recall, and BLEU (BiLingual Evaluation Understudy)
# ArabicRNN

Can AI write Arabic songs? This project aims to develop AI that can write songs.

All files are in Jupyter Notebooks format so it should be easy to run the project and get the fastest results (when you have everything installed correctly). You do need 'tensorflow 1.0.0' and Python 3.6 for this proejct to work. I have not tested it in Python 2.X versoins.


First, I scrapped all songs (+15K) from this website (fnanen.net) and then stored them into a Pandas dataframe (all_songs.pickle). Then, I preprocessed and normalized the raw text in order to make it easier for the algorithm to detect patterns and model sequences.

After having the lyrics file ready (aggregate_lyrics.txt), I used an LSTM-RNN architecture to predict sequences of words. You can see all details regarding the architecture inside the notebook along with some results.

You have any questions: make an issue here or contact me @fahd09
